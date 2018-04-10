[![Build Status](https://travis-ci.org/drtrigon/docker-sketchbook.svg?branch=master)](https://travis-ci.org/drtrigon/docker-arduino)

(docker status? also in docker-arduino and sketchbook)

https://github.com/drtrigon/docker-arduino

## Setup
Overload Origin with Both Remotes in order to clone and set this repo up use:
```
$ git clone file://///data/mount/gvfs/smb-share:server=.../01git/docker-sketchbook.git
$ cd docker-sketchbook
$ git remote set-url --add origin https://github.com/drtrigon/docker-sketchbook.git
```
you can check the settings with:
```
$ git remote -v
origin  /data/mount/gvfs/smb-share:server=.../01git/docker-sketchbook.git/ (fetch)
origin  /data/mount/gvfs/smb-share:server=.../01git/docker-sketchbook.git/ (push)
origin  https://github.com/drtrigon/docker-sketchbook.git (push)
```
(needs one single pull/push only)
