# pmwiki
Create a directory for the project:
-Copy the URL for the repository.
-Open Git Bash.
-mkdir pmwiki_docker
-Change the current working directory to pmwiki_docker
-Type git clone, and then paste the URL you copied earlier.
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY


# run
```
mkdir -p wiki.d
chown 33:33 -R wiki.d
docker compose up -d 
```

# browser
open http://x.x.x.x:33080
