# Welcome to Sentry Prometheus Exporter 👋
![Version](https://img.shields.io/badge/version-v0.1-blue.svg?cacheSeconds=2592000)
[![License: GNU General Public License v2.0](https://img.shields.io/badge/License-GNU%20General%20Public%20License%20v2.0-yellow.svg)](https://github.com/italux/sentry-prometheus-exporter/blob/master/LICENSE)
![Dockehub Build](https://img.shields.io/docker/cloud/automated/italux/sentry-prometheus-exporter)
![Dockehub build status](https://img.shields.io/docker/cloud/build/italux/sentry-prometheus-exporter)

> Export sentry project's metrics consistent with the Prometheus exposition formats

## Getting Started

### Prerequisites

- python >= 3.7.9

### Install
```sh
pip install -r requirements.txt
```

### Run
```sh
export SENTRY_BASE_URL="https://sentry.io/api/0/"
export SENTRY_AUTH_TOKEN="[REPLACE_TOKEN]"
export SENTRY_EXPORTER_ORG="[organization_slug]"
```
```sh
python exporter.py
```

### Docker

```sh
docker-compose build
```
```sh
docker-compose up -d
```

## 📒 Documentation

https://italux.github.io/sentry-prometheus-exporter/

## Author

👤 **Italo Santos**

* Website: http://italosantos.com.br
* Twitter: [@italux](https://twitter.com/italux)
* Github: [@italux](https://github.com/italux)
* LinkedIn: [@italosantos](https://linkedin.com/in/italosantos)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

- Please check the [Contributing Guide](https://github.com/italux/sentry-prometheus-exporter/blob/master/CONTRIBUTING.md)
- Feel free to check [issues page](https://github.com/italux/sentry-prometheus-exporter/issues). 

## Show your support

Give a ⭐️ if this project helped you!


## 📝 License

Copyright © 2021 [Italo Santos](https://github.com/italux).

This project is [GNU General Public License v2.0](https://github.com/italux/sentry-prometheus-exporter/blob/master/LICENSE) licensed.

***
_This README was generated with by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
