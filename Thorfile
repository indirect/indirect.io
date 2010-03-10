class Default < Thor
  desc "deploy", "Updates the server with the lastest changes"
  def deploy
    $stdout.sync = true
    system("git push")
    system("ssh id 'cd /home/intuitivedirection.com/web && git clean -f && git pull'")
  end
end
