class Deploy < Thor::Group
  desc "Updates the server with the lastest changes"

  def run_deploy
    $stdout.sync = true
    system("git push")
    system("ssh id 'cd /home/intuitivedirection.com/web && git clean -f && git pull'")
  end
end
