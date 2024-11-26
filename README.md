# ᴅ ᴏ ᴛ ꜰ ɪ ʟ ᴇ ꜱ
some simple slapped-together dotfiles from [this reddit post](https://new.reddit.com/r/unixporn/comments/1gzglvz/xfce4_monochrome_xfce_with_blur/), should look something like this:  

![rice](https://i.redd.it/tjhdoqmm713e1.png)

> [!WARNING]  
> this is my first time posting dotfiles and i have no idea what i am doing, feel free to point out any mistakes

### ᴅᴇᴘᴇɴᴅᴇɴᴄɪᴇꜱ (arch)
Official repo: `alacritty flameshot papirus-icon-theme xfce4-whiskermenu-plugin ttf-jetbrains-mono-nerd`  
AUR: `papirus-folders picom-ibhagwan-git`, `waterfox-bin` (optional)

### ɪɴꜱᴛᴀʟʟᴀᴛɪᴏɴ (manual only)
it's pretty straightforward, just copy .configs and .themes to the home directory,  
copy picom config to `/etc/xdg/picom.conf`,  
run `papirus-folders -t Papirus-Dark -C white -u` to make folders white,  
then you can set up waterfox: copy "*chrome*" folder to the profile folder, use [this theme](https://addons.mozilla.org/en-US/firefox/addon/monochroma/) and import mtab config  
* (you can use firefox instead, but i haven't tested it, so idk)