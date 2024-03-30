# TrivialToDo

A LLM-based Schedule Manager

## Installation

We recommend using docker to run the application. To do so, you need to have docker installed on your machine. If you don't have docker installed, you can download it from [here](https://www.docker.com/products/docker-desktop).

### Clone the repository

```bash
git clone https://github.com/TrivialToDo/TrivialToDo.git
cd TrivialToDo
```

### Add your keys

In `wechat/Dockerfile`, replace `YOUR_WECHATY_PUPPET_PADLOCAL_TOKEN` with your own token. You can get a token by following the instructions [here](https://wechaty.js.org/docs/puppet-services/).

In `docker-compose.yml`, replace `YOUR_MYSQL_ROOT_PASSWORD`, `YOUR_MYSQL_PASSWORD` and `YOUR_OPENAI_API_KEY` with your own passwords and API key. You can get an OpenAI API key by following the instructions [here](https://platform.openai.com/account/api-keys).

### Build the docker image

```bash
docker-compose build
```

### Run the application

```bash
docker-compose up
```

The application should now be running on `http://localhost:23512`.