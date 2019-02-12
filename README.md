# Bezirksregionenprofile deploy

[![Build Status](https://travis-ci.org/technologiestiftung/bezirksregionenprofile-deploy.svg?branch=master)](https://travis-ci.org/technologiestiftung/bezirksregionenprofile-deploy)

Automated deployment of [bezirksregionenprofile](https://github.com/technologiestiftung/bezirksregionenprofile) to AWS Elastic Beanstalk using travis and Docker

![diagram](/assets/diagram.png)

## Prerequisites

- Docker
- Docker Hub Account
- AWS Account
- Travis Account
  
## How To

### Run

```bash
docker-compose up --build
```

Open [http://localhost:3000](http://localhost:3000)

### Deploy

