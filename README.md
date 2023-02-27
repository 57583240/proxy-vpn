# proxy-ovpn
The source files of 2 docker containers are strored here: remote, local. Following the example from the official documentation, these containers are combined by docker-compose.yml file. The repository is set up with unit tests and docker hub deployment. [CI/CD](https://docs.docker.com/language/nodejs/configure-ci-cd/).

Inside this repository are 4 utilities designed to encrypt Internet traffic, anonymize it and dislocate. Checkmarks indicate the degree of readiness for commercial use:
 - [ ] remote ovpn
 - - [x] hub-template except # git
 - [ ] local ovpn
  - - [ ] hub-template
 - [ ] remote proxy
  - - [ ] hub-template
 - [ ] local proxy
  - - [ ] hub-template
# proxy-vpn
The source files of 2 docker containers are stored here: i/proxy, i/openvpn. Following the example from the official documentation, these containers are combined by docker-compose.yml file. The repository is set up with unit tests and docker hub deployment. [CI/CD](https://docs.docker.com/language/nodejs/configure-ci-cd/).