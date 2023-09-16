# DS-project
 The DS project oulu course
## Project Instructions:

Install docker and deploy the auth server.
When the auth server is deployed. Replay the "LoadServerURL" in index.js by the auth server ip.
 ```docker
docker build -t ai_server .
docker run -it -p {portHTTP}:{7000} ai_server
```
Origin repo:
https://github.com/nguyenhoanganh194/AI-server
