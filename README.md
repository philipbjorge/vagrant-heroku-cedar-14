# Vagrant Heroku Cedar-14 Box

Based off project: https://github.com/jackdb/pg-app-dev-vm

* Ubuntu 14.04
* PosgreSQL 9.4
* NodeJS 0.10.25 (for ExecJS)
* Ruby (currently 2.2.3)
* Rubygems (currently 2.4.8)
* Imagemagick
* Phantomjs (for poltergeist gem)

This box is published in Atlas as 'lazygray/heroku-cedar-14' and can be used simply by
adding `config.vm.box = 'lazygray/heroku-cedar-14'` to your `Vagrantfile`.
