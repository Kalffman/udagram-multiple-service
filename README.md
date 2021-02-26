# Udagram Multiple Service ( API / FrontEnd)

## How to run

### UDAGRAM-API


1. You need to set these environment variables:
    - POSTGRES_USERNAME
    - POSTGRES_PASSWORD
    - POSTGRES_HOST
    - POSTGRES_DB
    - AWS_BUCKET
    - AWS_REGION
    - AWS_PROFILE
    - JWT_SECRET
    - URL
    - API_HOST


2. After that, you can run these commands in root project folder

```bash
cd udagram-api

npm install

npm run dev
```

### UDAGRAM-FRONTEND

1. First you need to install ionic for development mode in you global environment

```bash
npm install -g ionic
```

2. After, go to root project folder an run next steps in your terminal

```bash
cd udagram-frontend

ionic build

ionic serve
```

### Enjoy

You need to setup in your machine [NodeJs](https://nodejs.org/en/download/package-manager/)