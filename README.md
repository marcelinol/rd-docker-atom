# rd-docker-atom

A dockerized Atom with ESLint, Rubocop, Reek, Beautify and Cucumber plugins already installed.

## How to install?
```
curl -sSL https://raw.githubusercontent.com/ResultadosDigitais/rd-docker-atom/master/install.sh | sudo sh
```

## Installation & Usage

### On Linux

After install, you are good to use it. To launch Atom, just type the following command in the desired directory:

```
rd-atom .
```

### On macOS El Captain +

#### :one: Install Docker for Mac :arrow_right: only if you don't have a previously installation

Install docker using `brew cask install docker` or directly from the website [here](https://docs.docker.com/docker-for-mac/).

#### :two: Install XQuartz

You can install XQuartz using homebrew with `brew cask install xquartz` or directly from the website [here](https://www.xquartz.org/). At the time of writing, I had 2.7.11 installed on my machine with OSX El Capitan. 

### :red_circle: **After installing XQuartz restart your machine (reboot your computer).** :red_circle:

#### :three: Run XQuartz

Start XQuartz from command line using `open -a XQuartz`. In the XQuartz preferences, go to the “Security” tab and make sure you’ve got “Allow connections from network clients” ticked. :arrow_down:

![image](https://media.giphy.com/media/3oKIPcYYSgNt1UTYUo/giphy.gif)

* Close XQuartz (cmd+Q)

#### :four: Make sure that your environment is up! :whale:

Docker should be running on your computer before executing `rd-atom`.

For example, before everything I need to:
1. open [Docker Quickstart Terminal](https://docs.docker.com/toolbox/toolbox_install_mac/)
2. run `docker-machine start`

#### :five: Run RD-ATOM

Just run `rd-atom .` on a specific directory or to open a specific file.
