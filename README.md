# docker-compose Library

A library of applications packaged with docker compose and sane defaults, allowing for for one-click startup and testing.

Note: these have not yet been heavily tested. These files should be considered to be in beta.

## Usage

Unless otherwise mentioned in the subdirectory's README, all apps can be run by changing to the application's subdirectory, and running `docker-compose up -d`.

## Applications
  * GLauth - a lightweight LDAP server
  * Gitea - git server in Golang
  * Filezilla - FTP / SFTP / FTPS client in docker, over VNC
  * Watchtower - Docker auto upgrades
  * Emby - Media server

## Applications In Progress
  * Webcron - place to run simple cronjobs in a container (such as CURLing a url on a schedule)
  * Smokeping - network latency monitoring and tracking tool
  * Unifi Controller - Ubiquity wifi controller
  * [NextCloud](https://hub.docker.com/r/benyanke/nextcloud) - File sharing, syncing, and collaboration tool - an effective Dropbox replacement
  * [Taiga](https://hub.docker.com/r/benyanke/taiga) - Agile project management tool
  * DavMail
  * FreeRadius - RADIUS authentication server
  * Photoprism - google photos alternative
  * Passbolt - Web password manager
  
## Applications Scheduled to be Added

  * Traefik - including traefik labels added to each app in this repo for quick deployment
  * OpenVPN Server
  * [ubuntu-workstation](https://hub.docker.com/r/benyanke/ubuntu-workstation)
  * Emby Media Server
  * Synapse / Matrix Chat Server
  * Collabora
  * Wordpress
  * DB Backup Tool
  * Minio - S3 replacement
  * Quassel Core - IRC central client
  * Etherpad
  * A web IDE
  * Apache Guacamole - Browser-based RDP
  * OnlyOffice - Google docs replacement
  * Wallabag - 
  * A remote desktop container
  * Rocketchat - Slack replacement
  * Cypht - webmail
  * Firefox bookmarks sync server
  * TinyTiny RSS
  * Radicale
  * [NAV Network Admin](https://github.com/Uninett/nav)
  * Agendav - CalDav web interface, similar to Google Calendar
  * Wekan
  * Promethius
  * routr sip server

## Moonshot
  * Cluster for MySQL
  * Cluster for Postgres
  * Cluster for Redis





See also this for more ideas:
https://github.com/benyanke/templates/tree/master
