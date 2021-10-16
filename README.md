# Ulauncher Github

<!-- [![Ulauncher Extension](https://img.shields.io/badge/Ulauncher-Extension-green.svg?style=for-the-badge)](https://ext.ulauncher.io/-/github-brpaz-ulauncher-github) -->
<!-- [![CircleCI](https://img.shields.io/circleci/build/github/brpaz/ulauncher-github.svg?style=for-the-badge)](https://circleci.com/gh/brpaz/ulauncher-github) -->
![License](https://img.shields.io/github/license/mt-system/ulauncher-github?color=33a4cf&style=for-the-badge)
![Fork](https://img.shields.io/github/forks/brpaz/ulauncher-github?color=33a4cf&label=fork%20of%20brpaz&logo=github&style=for-the-badge)


> [ulauncher](https://ulauncher.io/) Extension that provides quick access to common [GitHub](https://github.com) functionality like your repositories or gists.

## Usage

![demo](demo.gif)

## Features

- Search public repos
- Search uers
- Quick access to your profile pages, Issues, Pull Requests etc
- List your repos, organizations and gists.

## Requirements

- [ulauncher 5](https://ulauncher.io/)
- Python > 3
- PyGithub Extension (install with `pip3 install pygithub`)

## Install

Open ulauncher preferences window -> extensions -> add extension and paste the following url:

`https://github.com/mt-system/ulauncher-github`

## Usage

- Before usage you need to configure your Github "access_token" in plugin preferences. You can get one [here](https://github.com/settings/tokens).

### Keywords

Besides the main "gh" keyword, which triggers the main extension workflow, this extension have some other keywords that allows you access some of most used actions quickly.

- gists - Access to your Gists
- ghr -> Access to your Repos
- ghs -> Do a public repository search

## Notes

- Repositories, Stars and Gists are cached for 1 day. You can clear your cache, restarting ulauncher or selecting "Refresh cache" from the extension main menu.

## Development

```
git clone https://github.com/mt-system/ulauncher-github
make link
```

The ```make link``` will create a symbolic link to the ulauncher extensions folder.

Next, stop Ulauncher if running and run the following command:

```
make dev
```

This will start Ulauncher from the command line with all extensions disabled. In the output you will see something like this:

```
 VERBOSE=1 ULAUNCHER_WS_API=ws://127.0.0.1:5054/com.github.milottit.ulauncher-github PYTHONPATH=/usr/lib/python3.8/site-packages /usr/bin/python3 /home/$USER/.local/share/ulauncher/extensions/com.github.milottit.ulauncher-github/main.py
```

Run this, command in another terminal window, to laucnh the GitHub Extension.


## TODO

- Cache user repositories, gists and organizations in background for faster results.

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
## 🥰 Support the project

If this project was useful to you in some form, I would be glad to have your support.  It will help to keep the project alive and to have more time to work on Open Source.

The simplest form of support is to give a ⭐️ to this repo.

<!-- You can also contribute with [GitHub Sponsors](https://github.com/sponsors/milottit).

[![GitHub Sponsors](https://img.shields.io/badge/GitHub%20Sponsors-Sponsor%20Me-red?color=33a4cf&style=for-the-badge)](https://github.com/sponsors/milottit)
 -->

Or if you prefer a one time donation to the project, you can simple:

<a href="https://www.buymeacoffee.com/milottit"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=milottit&button_colour=33a4cf&font_colour=fff&font_family=Comic&outline_colour=fff&coffee_colour=97C2D3"></a>

## 📝 License

Copyright © 2021 [Thomas Milotti](https://github.com/milottit).

This project is [MIT](https://opensource.org/licenses/MIT) licensed.
