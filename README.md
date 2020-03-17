# docker-ts3

Minimal docker image for running a TeamSpeak 3 server

## Usage

1. Pull image: `docker pull kldzj/ts3`
1. Run container: `docker run -d -p 9987:9987/udp -p 10011:10011 -p 30033:30033 --name=ts3-test kldzj/ts3`
1. Check logs: `docker logs -f ts3-test`

---

By using this image you agree to the TeamSpeak [Terms of Service](https://www.teamspeak.com/en/privacy-and-terms/).
