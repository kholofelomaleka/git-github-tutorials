# git-github-tutorials
  - Simple git &amp; github tutorials/crash course from freeCodeCamp.org

# CREATE ssh-key
  - Generate ssh-keys
	-> ssh-keygen -t ed25519 -C "kholofelo.maleka@yahoo.com"
  
  - Get ssh-agent id & Assign private key
	-> eval "$(ssh-agent -s)"
	-> ssh-add ~/.ssh/id_ed25519

  - Copy the local .pub keys to GitHub
	-> Settings -> Add SSH keys and paste
 
  - DONE
