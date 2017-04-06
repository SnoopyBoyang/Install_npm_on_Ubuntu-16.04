# Install_npm_on_Ubuntu-16.04
用于安装Ubuntu版微信前期工作
**声明：内容载于[Install npm on Ubuntu 16.04](https://www.rosehosting.com/blog/install-npm-on-ubuntu-16-04/)

npm is a JavaScript package manager which can be used to install, share, and distribute code as well as to manage dependencies in your projects. It is written entirely in JavaScript as an inspiration from the other similar projects like PEAR for PHP or CPAN for Perl. In this tutorial, we will show you how to install npm on a Linux VPS running Ubuntu 16.04 as an operating system.

The very first thing you need to do is to [connect to your Linux VPS via SSH](https://www.rosehosting.com/blog/connect-to-your-linux-vps-via-ssh/) and upgrade your system software to the latest version available. You can do that by using the following command:

> sudo apt-get update && sudo apt-get -y upgrade

The upgrade process could take from few seconds to few minutes depending on the software that needs to be upgraded. Once your system is up to date, you can proceed with the other steps of this tutorial.

npm is bundled with Node.js, so to install **npm** you only need to install Node.js on your [Ubuntu VPS](https://www.rosehosting.com/ubuntu-vps.html). To **install Node.js 4.x LTS on Ubuntu 16.04**, run the following commands:

> curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -

> sudo apt-get install -y nodejs

Alternatively, to **install Node.js 6.x on Ubuntu 16.04**, which is the current version of Node.js, run the commands below:

> curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -

> sudo apt-get install -y nodejs

To verify that the installation is successful you can check the version of npm:

> npm -v

The output should be similar to the one below:

> # npm -v

> 2.15.9

A good way to start using npm is to read the npm help page or the npm documentation. To check the npm help page, enter the following command:

> npm help

Here is the npm help page:

’‘’
# npm help

Usage: npm 

where  is one of:
    access, add-user, adduser, apihelp, author, bin, bugs, c,
    cache, completion, config, ddp, dedupe, deprecate, dist-tag,
    dist-tags, docs, edit, explore, faq, find, find-dupes, get,
    help, help-search, home, i, info, init, install, issues, la,
    link, list, ll, ln, login, logout, ls, outdated, owner,
    pack, ping, prefix, prune, publish, r, rb, rebuild, remove,
    repo, restart, rm, root, run-script, s, se, search, set,
    show, shrinkwrap, star, stars, start, stop, t, tag, team,
    test, tst, un, uninstall, unlink, unpublish, unstar, up,
    update, upgrade, v, version, view, whoami

npm  -h     quick help on 
npm -l           display full usage info
npm faq          commonly asked questions
npm help   search for help on 
npm help npm     involved overview

Specify configs in the ini-formatted file:
    /root/.npmrc
or on the command line via: npm  --key value
Config info can be viewed via: npm help config

npm@2.15.9 /usr/lib/node_modules/npm
‘’‘

The npm documentation is available at [https://docs.npmjs.com/](https://docs.npmjs.com/).

Of course, you don’t have to do any of this if you use one of our [Linux VPS hosting](https://www.rosehosting.com/linux-vps-hosting.html) services, in which case you can simply ask our expert Linux admins to **install npm** for you. They are available 24×7 and will take care of your request immediately.
