---
layout: post
permalink: /readme/
---

# Saray's personal academic website

This is the repository for my personal academic website. The website is built using Jekyll and hosted on GitHub Pages. The website uses [Bootstrap](https://getbootstrap.com/) and my own custom CSS for styling. Feel free to use this repository as a template for your own academic website, just keep the footer reference to this repository.

This repository is forked from [Andreu Matoses](https://github.com/AndreuMatoses/andreumatoses.github.io), check out his extensive readme [HERE](README_Andreu.md).

## How to preview the website locally

GitHub pages builds the website upon pushing to the `main` branch. However, if you want to preview the website locally before pushing, you can do so by following these steps:

1. Fork and then Clone the repository

2. Install build dependencies (you can also build it with ruby, but it is much easier with docker):
    - [Docker](https://docs.docker.com/get-docker/)
    - [Docker Compose](https://docs.docker.com/compose/install/)

3. Run the following command in the root directory of the repository:

    ```shell
    docker compose up
    ```

This will launch the website at `http://localhost:4000` with live-reload enabled. Hence, you should be able to make changes to any file and they should appear automatically on your local instance upon saving that file.