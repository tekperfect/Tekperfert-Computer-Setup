# DevOps: Computer Setup

1. [Welcome](#welcome)
1. [Prerequisites](#prerequisites)
1. [Terminal](#terminal)


## Welcome

Welcome to the Tekperfect: DevOps program. This will be the start of your learning journey to
becoming a fellow DevOps Engineer. However before every great journey we need to prepare, here is a step to step guide to installing packanges, and preparing your computer for the journey ahead.

This setup guide will be along the lines of unix based system. But due to the recent addition of WSL you can follow along too.

## Prerequisites

There is none!


## Package Manager

So first thing first let's install a package manager. Package managers are extremmly useful and allows us to install and appropiate tools and we'll be using [brew](https://brew.sh/)

Paste this in your macOS Terminal or Linux shell prompt.

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

Now that you have homebrew let's install all the other packages, and no worries we have a script for that!

```bash
curl -s -L https://raw.githubusercontent.com/alfonsoh/scripts/master/bash/devops-setup.sh | bash
```

This will install: `wget`, `caskroom/cask` , `docker`, `python3`, `git`, `kubernates`, and `virtual box` 


## Terminal

You will be spending a lot of your time within the terminal so lets make the experince more enjoyable [ it'll make you look like a pro too! ]:

Let's install [`oh-my-zsh`](https://github.com/ohmyzsh/ohmyzsh)


**via curl**
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

More info on the [github page](https://github.com/ohmyzsh/ohmyzsh)



