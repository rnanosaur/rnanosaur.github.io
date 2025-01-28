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

* https://mmistakes.github.io/minimal-mistakes/
* https://github.com/mmistakes/mm-github-pages-starter
* https://ptc-it.de/enabling-cookie-consent-with-jekyll-minimal-mistakes/
* https://ptc-it.de/add-favicon-to-mm-jekyll-site/
* https://www.aleksandrhovhannisyan.com/blog/how-to-add-a-copy-to-clipboard-button-to-your-jekyll-blog/
* Make a table from csv file https://jekyllrb.com/tutorials/csv-to-table/

## Other

* https://emojipedia.org/
* https://realfavicongenerator.net/
* https://docs.github.com/en/free-pro-team@latest/github/managing-files-in-a-repository/3d-file-viewer

## Google TAG manager

* https://www.analyticsmania.com/post/track-pdf-downloads-with-google-tag-manager-ga/
* https://www.datadrivenu.com/track-downloads-google-analytics/

## Website license

This website is under license [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International][cc-by-nc-nd].
<!-- LICENSE START -->
<!-- LICENSE END -->
<!-- CREDITS START -->
## Contact Information

If you have any questions or inquiries, please contact us at [raffaello@nanosaur.ai](mailto:raffaello@nanosaur.ai).
<!-- CREDITS END -->
[cc-by-nc-nd]: https://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://i.creativecommons.org/l/by-nc-nd/4.0/80x15.png