To install a copy of the Cryptnet Fork of Diaspora:

make a directory on your computer for install, something like ~/Web/diaspora
from there:

git clone -b master https://YOUR_GIT_USERNAME@github.com/RAM518/diaspora.git diaspora
git remote add upstream https://github.com/diaspora/diaspora.git

first we set up the mysql db and a blank pod for testing before we go live:

sudo apt-get update
sudo apt-get install build-essential git curl imagemagick libmagickwand-dev nodejs \
             redis-server libcurl4-openssl-dev libxml2-dev libxslt-dev libmysqlclient-dev





