# :sauropod: nanosaur.ai - [![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]
<!-- INTRO START -->
[![Discord](https://img.shields.io/discord/797461428646707211?style=social&logo=discord&label=Discord)](https://discord.gg/rCHgeUpUj9) [![GitHub rnanosaur stars](https://img.shields.io/github/stars/rnanosaur?style=social)](https://github.com/rnanosaur) [![GitHub rbonghi followers](https://img.shields.io/github/followers/rbonghi?label=rbonghi)](https://github.com/rbonghi) [![LinkedIn](https://img.shields.io/badge/LinkedIn:-raffaello--bonghi-0077B5?style=social)](https://www.linkedin.com/in/raffaello-bonghi) [![robo.panther](https://img.shields.io/badge/Follow:-robo.panther-E4405F?style=social&logo=instagram)](https://www.instagram.com/robo.panther)

**nanosaur** The smallest [NVIDIA Jetson](https://developer.nvidia.com/buy-jetson) dinosaur robot, **open-source**, fully **3D printable**, based on [**ROS 2**](https://www.ros.org/) & [**Isaac ROS**](https://developer.nvidia.com/isaac-ros-gems).

*Designed & made by [Raffaello Bonghi](https://rnext.it)*

[![nanosaur](https://nanosaur.ai/assets/images/banner.jpg)](https://nanosaur.ai)

Meet nanosaur:

* 🦕 Website: [nanosaur.ai](https://nanosaur.ai)
* 🦄 Do you need any help? [Discord](https://discord.gg/rCHgeUpUj9)
* 🧰 For technical details follow [wiki](https://github.com/rnanosaur/nanosaur/wiki)
* 🐳 nanosaur [Docker Hub](https://hub.docker.com/u/nanosaur)
* ⁉️ Something wrong? Open an [issue](https://github.com/rnanosaur/nanosaur/issues)
<!-- INTRO END -->
<!-- CI START -->
## CI & CD

| package | CI | Downloads | Health |
|:-------:|:--:|:---------:|:------:|
| [![PyPI - Version](https://img.shields.io/pypi/v/nanosaur?label=nanosaur)](https://badge.fury.io/py/nanosaur) | [![Lint and Fix](https://github.com/rnanosaur/nanosaur_pkg/actions/workflows/flake8-lint.yml/badge.svg)](https://github.com/rnanosaur/nanosaur_pkg/actions/workflows/flake8-lint.yml) | [![PyPI - Downloads](https://img.shields.io/pypi/dm/nanosaur)](https://pypistats.org/packages/nanosaur) | [![nanosaur](https://snyk.io/advisor/python/nanosaur/badge.svg)](https://snyk.io/advisor/python/nanosaur) |

<!-- CI END -->
## Run locally

If you have **docker** and **docker-compose** you can use only this command

```console
docker compose up
```

**Note:** If you are updating `config.yml` or `_config.dev.yml` please **restart** container.

## Install ruby and run on your host

If you want install all environment on your desktop you need to install **ruby**:

<https://gorails.com/setup/ubuntu/20.04#ruby-rbenv>

* Using rbenv
* version 2.7.3

When is done, please run:

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
* Make a table from csv file [https://jekyllrb.com/tutorials/csv-to-table/](https://jekyllrb.com/tutorials/csv-to-table/)

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
