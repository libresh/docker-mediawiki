# docker-mediawiki
Mediawiki docker image for mediawiki service

# What is MediaWiki?

MediaWiki is a free and open-source wiki app, used to power wiki websites such
as Wikipedia, Wiktionary and Commons, developed by the Wikimedia Foundation and
others.

> [wikipedia.org/wiki/MediaWiki](https://en.wikipedia.org/wiki/MediaWiki)

# How to use this image

    docker run --name some-mediawiki --link some-mysql:mysql -d synctree/mediawiki

The following environment variables are also honored for configuring your
MediaWiki instance:

 - `-e MEDIAWIKI_DB_NAME=...` (defaults to "mediawiki")
