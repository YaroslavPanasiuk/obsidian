- [x] зробити firefox
- [x] services battery
- [x] configure thunar
- [x] add right click menu
- [x] add swipe up tray
- [x] waybar setup with ags
- [ ] rewrite scripts
- [x] write backup script
- [x] astal ~~notifications~~
- [x] default apps
- [x] hyprlock
- [x] mpvpaper
- [x] rofi theme
- [x] hypridle
- [x] samba
- [x] move virt-manager, wal, dock config to nixos
- [ ] update install script
- [ ] add udev rule

- vs code
- thunar
- firefox
- telegram
- bible
- disk analyse
- terminal
- steam

1. apps: Telegram Bible obsidian
2. code: nixos projects file config
3. thunar: nixos documents download shared 
4. steam: Terraria TmodLoader Hollow knight
5. power: 
6. firefox: yt ytmusic chatgpt github
7. nixos actions (rebuild, switch)
8. screen copy screen area, record with no audio, with audio input, with audio output

Привіт, Богдане. Я, на жаль, не зможу в неділю сказати проповідь, бо треба бути у Львові. Буду там служити

I have following flake input that I use in home-manager: 

    hyprpanel = {
      url = "github:Jas-SinghFSU/HyprPanel";
      inputs.nixpkgs.follows = "nixpkgs";
    };

I should fetch hyprpanel from github on the latest commit that was submitted 20 hours ago. But It actually fetches an earlier commit. How to fix this?