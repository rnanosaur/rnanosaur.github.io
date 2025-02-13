# 🦕 nanosaur.ai [![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]
<!-- SOCIAL START -->
[![Sponsor](https://img.shields.io/badge/Sponsor-30363D?logo=GitHub-Sponsors&logoColor=#white)](https://github.com/sponsors/rbonghi) [![Discord](https://img.shields.io/discord/797461428646707211?style=social&logo=discord&label=Discord)](https://discord.gg/rCHgeUpUj9) [![GitHub rnanosaur stars](https://img.shields.io/github/stars/rnanosaur?style=social)](https://github.com/rnanosaur) [![GitHub rbonghi followers](https://img.shields.io/github/followers/rbonghi?label=rbonghi)](https://github.com/rbonghi) [![LinkedIn](https://img.shields.io/badge/LinkedIn:-raffaello--bonghi-0077B5?style=social)](https://www.linkedin.com/in/raffaello-bonghi) [![robo.panther](https://img.shields.io/badge/Follow:-robo.panther-E4405F?style=social&logo=instagram)](https://www.instagram.com/robo.panther)
<!-- SOCIAL END -->
<!-- INTRO START -->
**nanosaur** The smallest [NVIDIA Jetson](https://developer.nvidia.com/buy-jetson) dinosaur robot, **open-source**, fully **3D printable**, based on [**ROS 2**](https://www.ros.org/) & [**Isaac ROS**](https://developer.nvidia.com/isaac-ros-gems).

*Designed & made by [Raffaello Bonghi](https://rnext.it)*

[![nanosaur](https://nanosaur.ai/assets/images/banner.jpg)](https://nanosaur.ai)

Meet nanosaur:

* 🦕 Website: [nanosaur.ai](https://nanosaur.ai)
* 🦄 Do you need any help? [Discord](https://discord.gg/rCHgeUpUj9)
* 🧰 For technical details, follow [wiki](https://github.com/rnanosaur/nanosaur/wiki)
* 🐳 nanosaur [Docker Hub](https://hub.docker.com/u/nanosaur)
* ⁉️ Something wrong? Open an [issue](https://github.com/rnanosaur/nanosaur/issues)
<!-- INTRO END -->
<!-- CI START -->
## CI & CD

| 📦 package | 🏗️ CI | Downloads | Health |
|:----------:|:-----:|:---------:|:------:|
| [![GitHub Release](https://img.shields.io/github/v/release/rnanosaur/nanosaur?label=nanosaur)](https://nanosaur.ai) | [![Release nanosaur](https://github.com/rnanosaur/nanosaur/actions/workflows/release.yml/badge.svg)](https://github.com/rnanosaur/nanosaur/actions/workflows/release.yml) | [![GitHub forks](https://img.shields.io/github/forks/rnanosaur/nanosaur)](https://nanosaur.ai) | --- |
| [![PyPI - Version](https://img.shields.io/pypi/v/nanosaur?label=nanosaur-cli)](https://badge.fury.io/py/nanosaur) | [![Lint and Fix](https://github.com/rnanosaur/nanosaur_pkg/actions/workflows/flake8-lint.yml/badge.svg)](https://github.com/rnanosaur/nanosaur_pkg/actions/workflows/flake8-lint.yml) | [![PyPI - Downloads](https://img.shields.io/pypi/dm/nanosaur)](https://pypistats.org/packages/nanosaur) | [![nanosaur](https://snyk.io/advisor/python/nanosaur/badge.svg)](https://snyk.io/advisor/python/nanosaur) |
| [![Website Badge](https://img.shields.io/badge/Website-green)](https://nanosaur.ai) | [![pages-build-deployment](https://github.com/rnanosaur/rnanosaur.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/rnanosaur/rnanosaur.github.io/actions/workflows/pages/pages-build-deployment) | --- | --- |

|    | 🐳 Image | Platform | Downloads | Size |
|:-:|:-------:|:------:|:---------:|:----:|
| 🦕 | [nanosaur/nanosaur:simulation](https://hub.docker.com/r/nanosaur/nanosaur) | x86_64 🖥️ | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/nanosaur)](https://hub.docker.com/r/nanosaur/nanosaur) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/nanosaur/simulation)](https://hub.docker.com/r/nanosaur/nanosaur) |
| 🖼️ | [nanosaur/perception:simulation](https://hub.docker.com/r/nanosaur/perception) | x86_64 🖥️ | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/perception)](https://hub.docker.com/r/nanosaur/perception) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/perception/simulation)](https://hub.docker.com/r/nanosaur/perception) |
| 👨‍💻 | [nanosaur/simulation:isaac-sim](https://hub.docker.com/r/nanosaur/simulation) | x86_64 🖥️ | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/simulation)](https://hub.docker.com/r/nanosaur/simulation) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/simulation/isaac-sim)](https://hub.docker.com/r/nanosaur/simulation) |
| 👨‍💻 | [nanosaur/simulation:gazebo](https://hub.docker.com/r/nanosaur/simulation) | x86_64 🖥️ | [![Docker Pulls](https://img.shields.io/docker/pulls/nanosaur/simulation)](https://hub.docker.com/r/nanosaur/simulation) | [![Docker Image Size (tag)](https://img.shields.io/docker/image-size/nanosaur/simulation/gazebo)](https://hub.docker.com/r/nanosaur/simulation) |

<!-- CI END -->
## Run locally

You can use only this command if you have **docker** and **docker-compose**.

```console
docker compose up
```

**Note:** If you are updating `config.yml` or `_config.dev.yml` please **restart** container.

## Install ruby and run on your host

If you want to install the entire environment on your desktop, you need to install **ruby**:

<https://gorails.com/setup/ubuntu/20.04#ruby-rbenv>

* Using rbenv
* version 2.7.3

When it is done, please run:

```console
bundle
```

to run on your local machine, please execute:

```console
rake serve
```

eq of: `bundle exec jekyll serve --config _config.yml,_config.dev.yml --incremental --livereload`

## Theme reference

* [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)
* [mm-github-pages-starter](https://github.com/mmistakes/mm-github-pages-starter)
* [Enabling Cookie Consent with Jekyll Minimal Mistakes](https://ptc-it.de/enabling-cookie-consent-with-jekyll-minimal-mistakes/)
* [Add favicon to MM Jekyll site](https://ptc-it.de/add-favicon-to-mm-jekyll-site/)
* [How to add a copy to clipboard button to your Jekyll blog](https://www.aleksandrhovhannisyan.com/blog/how-to-add-a-copy-to-clipboard-button-to-your-jekyll-blog/)
* Make a table from CSV file [https://jekyllrb.com/tutorials/csv-to-table/](https://jekyllrb.com/tutorials/csv-to-table/)

## Other

* [Emojipedia](https://emojipedia.org/)
* [realfavicongenerator](https://realfavicongenerator.net/)
* [3D File Viewer Documentation](https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/3d-file-viewer)

## Google TAG manager

* [Track PDF Downloads with Google Tag Manager](https://www.analyticsmania.com/post/track-pdf-downloads-with-google-tag-manager-ga/)
* [Track Downloads with Google Analytics](https://www.datadrivenu.com/track-downloads-google-analytics/)

## Website license

This website is under license [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International][cc-by-nc-nd].
<!-- CREDITS START -->
## Contact Information

If you have any questions or inquiries, please contact us at [raffaello@nanosaur.ai](mailto:raffaello@nanosaur.ai).
<!-- CREDITS END -->
[cc-by-nc-nd]: https://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png
