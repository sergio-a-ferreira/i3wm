* * *
# i3wm #

<p align="center">
<img alt="Logo" src="assets/banner.svg" style="width:95%; height:120px;">
</p>

i3 window manager configuration files and scriptsr.

* * * 

#### Getting Started ####

My i3wm session configurations, [forked from the base EndeavourOS distro](https://raw.githubusercontent.com/endeavouros-team/endeavouros-i3wm-setup/master/.config/i3/config), with some personal modifications and tweaks.

- changed eos window color theming to a brown / orange / yellow base
- changed i3bar to have transparency and compy with the new color theming
- enabled resizing with arrow keys
- changed some application keybindings

To change any configuration, please see the [official i3 reference](http://i3wm.org/docs/userguide.html).

#### Prerequisites ####

It's based on the default eos-i3wm, with i3gaps; so no prerequisites needed as long as you have i3gaps installed.

- enabled picom compositor for tranparency
- uses google Noto and FontAwesome
- some keybindings changed to "my" applications
	- pcmanfm
	- printscreen and flameshot

#### Installation / Deployment ####

Clone the repository:

```
cd
git clone https://github.com/sergio-a-ferreira/i3wm.git
```

If you want to keep a backup of your current configuration just rename your i3 directory first:

```
mv ~/.config/i3 ~/.config/i3_backup
```

Replace your ~/.config/i3 directory:

```
mv ~/i3wm ~/.config/i3 
```

Instead, you can link the repository enabling versioning changes:

```
ln -s ~/i3wm ~/.config/i3 
```


#### Authors ####

* **Sergio Ferreira** - *Initial work* - [sergio-a-ferreira](https://github.com/sergio-a-ferreira/i3wm.git)

See also [endeavouros-i3wm-setup](https://raw.githubusercontent.com/endeavouros-team/endeavouros-i3wm-setup/master/.config/i3/config)

#### License ####

This project is licensed under the Unlicense - see the [LICENSE](LICENSE) file for details

