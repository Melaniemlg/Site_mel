# Where is my directory ?

cd '.\Documents\sauvegarde yggdrasil\MG_ Editor & Foreign Rights Agent\Réseaux sociaux et identité graphique\Site internet\Site_mel\'


# DEV
docker-compose up --build

# How to publish the website ?

in the directory Site_Mel
run :
```
docker-compose run hugo -D
```
this should output something like this :

Start building sites …

                   | EN
-------------------+------
  Pages            |  70
  Paginator pages  |   4
  Non-page files   |   0
  Static files     | 137
  Processed images |   0
  Aliases          |   3
  Sitemaps         |   1
  Cleaned          |   0

Total in 25325 ms

Then, go to Github software, select repository mg-editor-agent.

Git add/commit/push.

Your website is now online. Hurray.

# DEPLOY
sudo hugo -D
git add public/
git push
@onRemote
git pull


