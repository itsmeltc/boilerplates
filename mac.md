# macOS Tweaks

| Step | Location | Notes |
| --- | --- | --- |
| Run through macOS installer | | Disable metrics and enable FileVault |
| Note down FileVault decryption key | | |
| Install all updates | About This Mac >> Software Update | Reboot and recheck until no more updates |
| Turn on dock hiding | System Preferences >> Dock | |
| Change computer hostname | System Preferences >> Sharing | Remove name/username |
| Enable trackpad tap to click | System Preferences >> Trackpad | |
| Enable mouse secondary click | System Preferences >> Mouse | |
| Enable mouse swipe gestures | System Preferences >> Mouse | |
| Enable three finger drag | System Preferences >> Accessibility >> Mouse & Trackpad >> Trackpad Options | |
| Set mouse tracking speed to 8 (fast) | System Preferences >> Mouse | |
| Set key repeat speed to 10 (fast) | System Preferences >> Keyboard | |
| Set delay until repeat to 10 (short) | System Preferences >> Keyboard | |
| Disable Spotlight keyboard shortcuts | System Preferences >> Keyboard | |
| Remap Caps Lock to Control | System Preferences >> Keyboard | |
| Enable Firewall | System Preferences >> Security | Enable stealth mode |
| Set require password to immediately | System Preferences >> Security | |
| Change screen saver start time to 1 minute | System Preferences >> Desktop & Screen Saver | |
| Set bottom left hot corner to start screen saver | System Preferences >> Desktop & Screen Saver | |
| Set top left hot corner to Mission Control | System Preferences >> Desktop & Screen Saver | |
| Under Language & Region, set first day of week to Monday | System Preferences >> Language & Region | |
| Add and set preferred language to English (United Kingdom) | System Preferences >> Language & Region | Keep "English" as secondary then reboot |
| Disable Guest User account | System Preferences >> Users & Groups | |
| Display login window as name and password | System Preferences >> Users & Groups | |
| Set resolution to More Space | System Preferences >> Displays | |
| Show volume button in menu bar | System Preferences >> Sound | |
| Show Bluetooth button in menu bar | System Preferences >> Bluetooth | |
| Hide date and time in menu bar | System Preferences >> Date & Time | |
| Hide battery status in menu bar | System Preferences >> Power Saver | |
| Show home folder in Finder preferences | Finder Preferences >> Advanced | |
| Show all filename extensions | Finder Preferences | |
| Build locate database | sudo launchctl load -w /System/Library/LaunchDaemons/co m.apple.locate.plist | |
| Prevent iPhone from auto-syncing with iTunes | iTunes Preferences >> Devices | |

# Browser

| Application | Source | Notes |
| --- | --- | --- |
| Firefox | mozilla.org/en-GB/firefox | Sync bookmarks with Firefox Account |
| Enable bookmarks toolbar | | |
| Disable Firefox Home Content | Firefox Preferences >> Home | |
| Add search bar in toolbar | Firefox Preferences >> Search | |
| Remove all search engines but Google | Firefox Preferences >> Search | |
| Set Content Blocking to Strict | Firefox Preferences >> Privacy & Security | |
| Enable Do Not Track | Firefox Preferences >> Privacy & Security | |
| Disable password management | Firefox Preferences >> Privacy & Security | |
| Disable data collection | Firefox Preferences >> Privacy & Security | |
| HTTPS Everywhere for Firefox | eff.org/https-everywhere | |
| LastPass for Firefox | lastpass.com/lastpassffx | |
| Privacy Badger for Firefox | eff.org/privacybadger | |
| uBlock Origin for Firefox | addons.mozilla.org/en-GB/firefox/addon/ublock-origin | |
| Hangouts for Firefox | google.com/tools/dlpage/hangout | |
| Chrome | google.co.uk/chrome/browser/desktop | |
| Authy for Chrome | authy.com | |

# Dev

| Step | Location | Notes |
| --- | --- | --- |
| Xcode | App Store | sudo xcode-select --install |
| Sublime | sublimetext.com | Apply license |
| WiFi Explorer | App Store | |
| Heroku CLI | devcenter.heroku.com/articles/heroku-command-line | |
| AWS CLI | pip3 install awscli --upgrade --user | | 
| Google Cloud SDK | cloud.google.com/sdk/docs/quickstart-mac-os-x | | 
| Homebrew | brew.sh | |
| python3 | brew install python3 | zsh conf priorities python3 for running python |
| python2 | brew install python@2 | |
| virtualenv | pip3 install virtualenv | |
| virtualenvwrapper | pip3 install virtualenvwrapper | |
| iTerm2 | iterm2.com | |
| Enable blinking cursor, opacity, and opaque background colours | iTerm2 Preferences >> Profiles | |
| Disable per-pane title bar and dim of inactive split panes | iTerm2 Preferences >> Appearance | |
| Enable Natural Text Editing | iTerm2 Preferences > Profiles > Keys > Load Preset | |
| Enable ⌘+Arrow shortcuts | iTerm2 Preferences > Keys > Key Mappings: ⌘+← 0x01; ⌘+→ 0x05 | |
| zsh | brew install zsh | |
| oh-my-zsh | github.com/robbyrussell/oh-my-zsh | |
zsh-autosuggetions | github.com/zsh-users/zsh-autosugge stions | |
| Meslo Powerline font | github.com/powerline/fonts | Set iTerm profile font to Meslo
| archey | brew install archey | |
| asciinema | brew install asciinema | |
| ffmpeg | brew install ffmpeg | |
| radtest | brew install freeradius-server | |
| git | brew install git | |
| gpg | brew install gpg | |
| tig | brew install tig | |
| htop | brew install htop | |
| ipcalc | brew install ipcalc | |
| iperf | brew install iperf | |
| mtr | brew install mtr | |
| nmap | brew install nmap | |
| p7zip | brew install p7zip | |
| tmux | brew install tmux | |
| tree | brew install tree | |
| vim | brew install vim | |
| watch | brew install watch | |
| wget | brew install wget | |
| python | brew install python | |
| python3 | brew install python3 | |
| ruby | brew install ruby | |
| pathogen | | wget from GH vim.org/scripts/script.php?script_id=2332| | 
| nerdtree | github.com/scrooloose/nerdtree| | 
| vim-airline | github.com/vim-airline/vim-airline| | 
| vim-multiple-cursors | github.com/terryma/vim-multiple-cursors| | 
| cocoapods | sudo gem install cocoapods --pre| |
| Sync Xcode directory | | | 
| VirtualBox | virtualbox.org/wiki/Downloads | | 
| Wireshark | wireshark.org | | 
| Docker | hub.docker.com/editions/community/docker-ce-desktop-mac | | 

# Productivity

| Step | Location | Notes |
| --- | --- | --- |
| Alfred | alfredapp.com | Set keyboard shortcut to ⌘+Space | 
| Franz | meetfranz.com | | 
| Things 3 | App Store | |
| Evernote | evernote.com/download | Set font to Mono Regular 14; Disable context | 
| Spotify | spotify.com/us/download | | 
| MediaHuman Audio Converter | mediahuman.com/audio-converter | 
| Google Drive | drive.google.com | | 
| iStat Menus | bjango.com/mac/istatmenus | |
| Slate | github.com/jigish/slate | Config; enable Accessibility in Privacy preferences | 
| SnappyApp | AppStore | | 
| TeamViewer | teamviewer.com/en/download/mac | | 
| TftpServer | ww2.unime.it/flr/tftpserver | | 
| Forticlient | forticlient.com | | 
| HMA | vpn.hidemyass.com/vpncontrol/pages/download | | 
| Tor | torproject.org | Set security level to high | 
| Avira | avira.com | | 
