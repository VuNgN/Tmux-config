# Tmux-config
Original Project from https://github.com/gpakosz/.tmux 

# Installation

## Install Tmux

### Ubuntu

```bash
sudo apt install tmux
```

## Install Powerline fonts

### Ubuntu

```bash
sudo apt-get install fonts-powerline
```

## Install config file

```bash
$ cd ~/
$ git clone https://github.com/VuNgN/Tmux-config.git
$ cp Tmux-config/.tmux.conf .
$ cp Tmux-config/.tmux.conf.local .
$ tmux source-file ~/.tmux.conf
```

# Configuration

If all packages was installed, open your Tmux and it should look like that: 

![img1](https://user-images.githubusercontent.com/60380217/144832633-f2f146d0-4f22-4c05-bb30-b87e7c21b6cd.png) ![change-pane](https://user-images.githubusercontent.com/60380217/144832625-dbb74794-1047-4272-b5ef-5ea745ed2302.gif)

![img2](https://user-images.githubusercontent.com/60380217/144832641-e1b776bd-418e-4308-bffe-3c92b23e2811.png)

While this configuration tries to bring sane default settings, you may want to
customize it further to your needs. Instead of altering the `~/.tmux.conf` file
and diverging from upstream, the proper way is to edit the `~/.tmux.conf.local`
file.

Please refer to the sample `.tmux.conf.local` file to know more about variables
you can adjust to alter different behaviors. Pressing `<prefix> e` will open
`~/.tmux.conf.local` with the editor defined by the `$EDITOR` environment
variable (defaults to `vim` when empty).

![img3](https://user-images.githubusercontent.com/60380217/144832646-21dc7c13-21bf-4560-a5e2-ca6291fa886b.png)
