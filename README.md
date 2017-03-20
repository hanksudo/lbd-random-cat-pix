# Random cat pix

Simple web app to show random cat on web.

## Run

```bash
docker image build -t hanksudo/random-cat-pix .
docker container run -p 8888:5000 --name cat hanksudo/random-cat-pix

open http://localhost:8888
```
