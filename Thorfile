class Default < Thor
  desc "deploy", "Updates the server with the lastest changes"
  def deploy
    $stdout.sync = true
    system("git push")
    system("rsync -avz -essh public/ id:/home/indirect.io/web/public")
  end
  
  desc "browse", "Opens the site in a web browser"
  def browse
    `open http://indirect.io`
  end
end
