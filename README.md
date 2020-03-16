# docker-ts3
Minimal docker image for running a TeamSpeak 3 server

## Usage
1. Clone: `git clone https://github.com/kldzj/docker-ts3.git`
1. Build and tag: `docker image build -t docker-ts3:1.0 .`
1. Run: `docker run -d -p 9987:9987/udp -p 10011:10011 -p 30033:30033 --name=ts3-test docker-ts3:1.0`

---

By using this image you aggree to the TeamSpeak [Terms of Service](https://www.teamspeak.com/en/privacy-and-terms/).
