# Ubuntu iHaskell Jupyter Lab
__Docker Image - Ubuntu Jupyter Lab with Haskell &amp; Python Kernels__


- Build and run a container from the `heathrobertson/ihaskell:latest` Docker images.

```bash
docker run --name ihaskell \
-p 8888:8888 \
-v $(pwd):/home  \
heathrobertson/ihaskell:latest
```


- Build the Docker image from a local `Dockerfile`.

```bash
docker build -t heathrobertson/ihaskell:latest .
```


___
![ToiletHill Logo](https://raw.githubusercontent.com/heathdrobertson/toilethill.io/master/assets/images/logo/ToiletHill.png)


### Heath Robertson
Email: CodeHappens@ToiletHill.io
| Github: [HeathDRobertson](https://github.com/heathdrobertson)
| Dockerhub: [HeathDRobertson](https://hub.docker.com/u/heathdrobertson)
| Twitter: [@HeathDRobertson](https://twitter.com/HeathDRobertson)
| Telegram: [@HeathDRobertson](https://t.me/heathdrobertson)
| Work: [HeathRobertson.com](https://heathrobertson.com)
| Website: [ToiletHill.io](https://ToiletHill.io)
