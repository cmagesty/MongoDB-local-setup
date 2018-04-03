# MongoDB-local-setup
A guide to setting up mongoDB locally on a mac

1. Download mongoDB from the mongoDB download center: https://www.mongodb.com/download-center#enterprise
2. Move the download folder to User folder.
3. Set up path in  .bash_profile
  `export PATH="~/mongodb-osx-x86_64-enterprise-3.6.3/bin:$PATH"`
4. create a db director from the root, by defulat mongodb looks for /data/db
  `sudo mkdir -p /data/db`
5. give it proper rwx
  `sudo chmod 755 /data/db`
  if a problem presists run
  `sudo chown $USER /data/db`
6. start mongoDB
  `mongod`
7. Connect to mongo
  `mongo`
