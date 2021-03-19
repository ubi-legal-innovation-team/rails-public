First of all make sure you've created a rails app

```bash
rails new APP_NAME
```

## Setup

Add Rails' default public:

```
rm -rf public
rm -rf vendor
curl -L https://github.com/ubi-legal-innovation-team/rails-public/archive/master.zip > public.zip
unzip public.zip -d public && rm public.zip && mv public/rails-public-master public
```

**On Ubuntu/Windows**: if the `unzip` command returns an error, please install it first by running `sudo apt install unzip`.
