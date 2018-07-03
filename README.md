# WordPress/Docker Starter Project

*Starter project template for local WordPress &amp; Docker development.*

**NOTE:** This project does not include WordPress files as they may be different per project. \
WordPress files should go inside the `/public` folder which becomes the root server folder.

**Requirements:**
- Docker &amp; Docker Compose

# Getting Started

I have tried to keep this project as basic and simple as possible. \
For your own benefit, I'd encourage you to get a basic understanding of how Docker works.

1. Make sure you have `Docker` and `docker-compose` [installed](https://www.docker.com/community-edition#/download).
2. Clone this repository locally.
3. Modify the `docker-compose.yml` file to match your desired local setup.
5. Install [WordPress](https://wordpress.org/) in the `/public` directory.
4. Execute `docker-compose up -d` from the root directory of the repository.
