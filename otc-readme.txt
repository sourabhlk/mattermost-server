Steps to build:

- Create directory mattermost under ~/go/src/github.com. cd to this directory.
Without this we get build errors.

- Clone mattermost-server from sushpradi github:
git clone https://github.com/sushpradi/mattermost/mattermost-server.git

- Clone mattermost-webapp from mattermost
git clone https://github.com/mattermost/mattermost-webapp.git

- build server & webapp:
make run

- Build package:
make package

- Use package to create docker image. Deploy it to private registry.

