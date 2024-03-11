## Sentry Telegram
Tested environment
> Self-Hosted Sentry 24.2.0 base on docker compose

## Install
```shell
vi sentry/enhance-image.sh #see https://develop.sentry.dev/self-hosted/#configuration

apt-get update
apt-get install -y git
pip install git+https://github.com/tianci-sh/sentry-telegram.git@v24.2.0
```

## Result
![Sentry Telegram Integration](https://github.com/tianci-sh/sentry-telegram/blob/master/images/image.png "Sentry Telegram Integration")
![Telegram Message](https://github.com/tianci-sh/sentry-telegram/blob/master/images/image-2.png "Telegram Message")
