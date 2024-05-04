<br>

<div align="center">
  <a href="https://hydralauncher.site">
    <img src="./resources/icon.png" width="144"/>
  </a>
  <h1 align="center">Hydra Launcher</h1>
  <p align="center">
    <strong>Hydra is a game launcher with its own embedded bittorrent client and a self-managed repack scraper.</strong>
  </p>
  <p>
    <a href="https://discord.gg/hydralauncher">
      <img src ="https://img.shields.io/discord/1220692017311645737?style=flat&logo=discord&label=Hydra&labelColor=%231c1c1c"/>
    </a>
    <a href="https://github.com/hydralauncher/hydra">
      <img src="https://img.shields.io/github/actions/workflow/status/hydralauncher/hydra/build.yml" />
    </a>
    <a href="https://github.com/hydralauncher/hydra">
      <img src="https://img.shields.io/github/package-json/v/hydralauncher/hydra" />
    </a>
  </p>

![Hydra Catalogue](./docs/screenshot.png)

</div>

<br>

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
- [Contributing](#contributing)
- [Running](#running)
- [Build](#build)

## About

**Hydra** is a **Game Launcher** with its own embedded **BitTorrent Client** and a **self-managed repack scraper**.
<br>
The launcher is written in TypeScript (Electron) and Python, which handles the torrenting system by using libtorrent.

## Features

- Self-Managed repack scraper among all the most reliable websites on the [Megathread]("https://www.reddit.com/r/Piracy/wiki/megathread/")
- Own embedded bittorrent client
- How Long To Beat (HLTB) integration on game page
- Downloads path customization
- Repack list update notifications
- Windows, Linux and MacOS support
- Constantly updated
- And more ...

## Installation

Follow the steps below to install:

1. Download the latest version of Hydra from the [Releases](https://github.com/hydralauncher/hydra/releases/latest) page.
   - Download only .exe if you want to install Hydra on Windows.
   - Download .deb or .rpm or .zip if you want to install Hydra on Linux. (depends on your Linux distro)
2. Run the downloaded file.
3. Enjoy Hydra!

## Contributing

### Join our Discord

We concentrate our discussions on our [Discord](https://discord.gg/hydralauncher) server.

Join, grab the Collaborator role, go the dev channel and we talk to us and share your ideas.

### Install Node.js

Ensure you have Node.js installed on your machine. If not, download and install it from [nodejs.org](https://nodejs.org/).

### Install Yarn

Yarn is a package manager for Node.js. If you haven't installed Yarn yet, you can do so by following the instructions on [yarnpkg.com](https://classic.yarnpkg.com/lang/en/docs/install/).

### Fork and clone your repository

1. Fork the repository [(click here to fork now)](https://github.com/hydralauncher/hydra/fork)
2. Clone your forked code `git clone https://github.com/your_username/hydra`

### Install Node Dependencies

Navigate to the project directory and install the Node dependencies using Yarn:

```bash
cd hydra
yarn
```

### Install Python 3.9

Ensure you have Python 3.9 installed on your machine. You can download and install it from [python.org](https://www.python.org/downloads/release/python-3919/).

### Install Python Dependencies

Install the required Python dependencies using pip:

```bash
pip install -r requirements.txt
```

## Environment variables

You'll need an SteamGridDB API Key in order to fetch the game icons on installation.
If you want to have onlinefix as a repacker you'll need to add your credentials to the .env

Once you have it, you can paste the `.env.example` file and put it on `STEAMGRIDDB_API_KEY`, `ONLINEFIX_USERNAME`, `ONLINEFIX_PASSWORD`.

## Running

Once you've got all things set up, you can run the following command to start both the Electron process and the bittorrent client:

```bash
yarn dev
```

## Build

### Build the bittorrent client

Build the bittorrent client by using this command:

```bash
python torrent-client/setup.py build
```

### Build the Electron application

Build the Electron application by using this command:

On Windows:

```bash
yarn build:win
```

On Linux:

```bash
yarn build:linux
```

## Contributors

<!-- readme: contributors -start -->
<table>
<tr>
    <td align="center">
        <a href="https://github.com/hydralauncher">
            <img src="https://avatars.githubusercontent.com/u/164102380?v=4" width="100;" alt="hydralauncher"/>
            <br />
            <sub><b>Hydra</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/zamitto">
            <img src="https://avatars.githubusercontent.com/u/167933696?v=4" width="100;" alt="zamitto"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/JackEnx">
            <img src="https://avatars.githubusercontent.com/u/167036558?v=4" width="100;" alt="JackEnx"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Magrid0">
            <img src="https://avatars.githubusercontent.com/u/73496008?v=4" width="100;" alt="Magrid0"/>
            <br />
            <sub><b>Magrid</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/fhilipecrash">
            <img src="https://avatars.githubusercontent.com/u/36455575?v=4" width="100;" alt="fhilipecrash"/>
            <br />
            <sub><b>Fhilipe Coelho</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/jps14">
            <img src="https://avatars.githubusercontent.com/u/168477146?v=4" width="100;" alt="jps14"/>
            <br />
            <sub><b>José Luís</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/shadowtosser">
            <img src="https://avatars.githubusercontent.com/u/168544958?v=4" width="100;" alt="shadowtosser"/>
            <br />
            <sub><b>Null</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/pmenta">
            <img src="https://avatars.githubusercontent.com/u/71457671?v=4" width="100;" alt="pmenta"/>
            <br />
            <sub><b>João Martins</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/ferivoq">
            <img src="https://avatars.githubusercontent.com/u/36544651?v=4" width="100;" alt="ferivoq"/>
            <br />
            <sub><b>FeriVOQ</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/xbozo">
            <img src="https://avatars.githubusercontent.com/u/119091492?v=4" width="100;" alt="xbozo"/>
            <br />
            <sub><b>Guilherme Viana</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/eltociear">
            <img src="https://avatars.githubusercontent.com/u/22633385?v=4" width="100;" alt="eltociear"/>
            <br />
            <sub><b>Ikko Eltociear Ashimine</b></sub>
        </a>
    </td></tr>
<tr>
    <td align="center">
        <a href="https://github.com/Netflixyapp">
            <img src="https://avatars.githubusercontent.com/u/91623880?v=4" width="100;" alt="Netflixyapp"/>
            <br />
            <sub><b>Netflixy</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/Hachi-R">
            <img src="https://avatars.githubusercontent.com/u/58823742?v=4" width="100;" alt="Hachi-R"/>
            <br />
            <sub><b>Hachi</b></sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/FerNikoMF">
            <img src="https://avatars.githubusercontent.com/u/76095334?v=4" width="100;" alt="FerNikoMF"/>
            <br />
            <sub><b>Firdavs</b></sub>
        </a>
    </td></tr>
</table>
<!-- readme: contributors -end -->

## License

Hydra is licensed under the [MIT License](LICENSE).
