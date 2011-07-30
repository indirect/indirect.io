class Default < Thor
  desc "deploy", "Updates the server with the lastest changes"
  def deploy
    $stdout.sync = true
    system("git push")
    system("rsync -avz -essh public/ id:/home/intuitivedirection.com/web/public")
  end
end
