# macOS Setup and Tweaks

|Step |Location |Notes |
|--- |--- |--- |
|Run through macOS installer | |Disable metrics and enable FileVault |
|Note down FileVault decryption key | | |
|Install all updates |About This Mac >> Software Update |Reboot and recheck until no more updates |
|Turn on dock hiding |System Preferences >> Dock | |
|Change computer hostname |System Preferences >> Sharing |Remove name/username |
|Enable trackpad tap to click |System Preferences >> Trackpad >> Point & Click | |
|Enable trackpad two finger secondary click |System Preferences >> Trackpad >> Point & Click | |
|Enable trackpad swipe between pages |System Preferences >> Trackpad >> More Gestures | |
|Enable mouse secondary click |System Preferences >> Mouse | |
|Enable mouse swipe gestures |System Preferences >> Mouse | |
|Enable three finger drag |System Preferences >> Accessibility >> Mouse & Trackpad >> Trackpad Options | |
|Set mouse tracking speed to 8 (fast) |System Preferences >> Mouse | |
|Set key repeat speed to 10 (fast) |System Preferences >> Keyboard | |
|Set delay until repeat to 10 (short) |System Preferences >> Keyboard | |
|Disable Spotlight keyboard shortcuts |System Preferences >> Keyboard |Used by Alfred later |
|Enable Firewall |System Preferences >> Security |Enable stealth mode |
|Set require password to immediately |System Preferences >> Security | |
|Change screen saver start time to 1 minute |System Preferences >> Desktop & Screen Saver | |
|Set bottom left hot corner to start screen saver |System Preferences >> Desktop & Screen Saver | |
|Set top left hot corner to Mission Control |System Preferences >> Desktop & Screen Saver | |
|Under Language & Region, set first day of week to Monday |System Preferences >> Language & Region | |
|Under Language & Region, set date formart to dd/mm/yyyy |System Preferences >> Language & Region | |
|Under Language & Region, set number format to decimal point |System Preferences >> Language & Region | |
|Add and set preferred language to English (United Kingdom) |System Preferences >> Language & Region |Keep "English" as secondary then reboot |
|Disable Guest User account |System Preferences >> Users & Groups | |
|Display login window as name and password |System Preferences >> Users & Groups | |
|Set resolution to More Space |System Preferences >> Displays | |
|Show volume button in menu bar |System Preferences >> Control Centre | |
|Show Bluetooth button in menu bar |System Preferences >> Control Centre | |
|Set Time menu bar status to analogue |System Preferences >> Control Centre | |
|Hide battery status in menu bar |System Preferences >> Control Centre | |
|Show home folder in Finder preferences |Finder Preferences >> Advanced | |
|Show all filename extensions |Finder Preferences | |
|Remove Focus profiles and disable sharing across devices |System Preferences >> Focus | |
|Build locate database |sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.locate.plist | |
|Prevent iPhone from auto-syncing with iTunes |iTunes Preferences >> Devices | |

# Browser

|Application |Source |Notes |
|--- |--- |--- |
|Firefox |mozilla.org/en-GB/firefox |Sync bookmarks with Firefox Account |
|Enable bookmarks toolbar | | |
|Disable Firefox Home Content |Firefox Preferences >> Home | |
|Add search bar in toolbar |Firefox Preferences >> Search | |
|Remove all search engines but Google |Firefox Preferences >> Search | |
|Set Content Blocking to Strict |Firefox Preferences >> Privacy & Security | |
|Enable Do Not Track |Firefox Preferences >> Privacy & Security | |
|Disable password management |Firefox Preferences >> Privacy & Security | |
|Disable data collection |Firefox Preferences >> Privacy & Security | |
|HTTPS Everywhere for Firefox |eff.org/https-everywhere | |
|LastPass for Firefox |lastpass.com/lastpassffx | |
|Privacy Badger for Firefox |eff.org/privacybadger | |
|uBlock Origin for Firefox |addons.mozilla.org/en-GB/firefox/addon/ublock-origin | |
|Hangouts for Firefox |google.com/tools/dlpage/hangout | |
|Chrome |google.co.uk/chrome/browser/desktop | |
|Authy Desktop |authy.com | |

# Dev

|Step |Source |Notes |
|--- |--- |--- |
|Xcode |App Store |sudo xcode-select --install |
|Sublime |sublimetext.com |Apply license |
|WiFi Explorer |App Store | |
|Heroku CLI |devcenter.heroku.com/articles/heroku-command-line | |
|AWS CLI |pip3 install awscli --upgrade --user | |
|Google Cloud SDK |cloud.google.com/sdk/docs/quickstart-mac-os-x | |
|Homebrew |brew.sh | |
|python3 |brew install python3 | |
|python2 |brew install python@2 | |
|virtualenv |pip3 install virtualenv | |
|virtualenvwrapper |pip3 install virtualenvwrapper | |
|iTerm2 |iterm2.com | |
|Enable blinking cursor, opacity, and opaque background colours |iTerm2 Preferences >> Profiles | |
|Check silence bell |iTerm2 Preferences >> Profiles >> Default >> Terminal | |
|Disable per-pane title bar and dim of inactive split panes |iTerm2 Preferences >> Appearance | |
|Enable Natural Text Editing |iTerm2 Preferences > Profiles > Keys > Load Preset | |
|Enable ⌘+Arrow shortcuts |iTerm2 Preferences > Keys > Key Mappings: ⌘+← 0x01; ⌘+→ 0x05 | |
|zsh |brew install zsh | |
|oh-my-zsh |github.com/robbyrussell/oh-my-zsh | |
|zsh-autosuggetions |github.com/zsh-users/zsh-autosuggestions | |
|zsh-syntax-highlighting |github.com/zsh-users/zsh-syntax-highlighting | |
|Meslo Powerline font |github.com/powerline/fonts |Set iTerm profile font to Meslo |
|pyenv |brew install pyenv|github.com/pyenv/pyenv#installation |
|archey |brew install archey | |
|asciinema |brew install asciinema | |
|ffmpeg |brew install ffmpeg | |
|radtest |brew install freeradius-server | |
|git |brew install git | |
|gpg |brew install gpg | |
|tig |brew install tig | |
|htop |brew install htop | |
|ipcalc |brew install ipcalc | |
|iperf |brew install iperf | |
|mtr |brew install mtr | |
|nmap |brew install nmap | |
|rsvg-convert |brew install rsvg-convert | |
|p7zip |brew install p7zip | |
|tmux |brew install tmux | |
|tree |brew install tree | |
|vim |brew install vim | |
|watch |brew install watch | |
|wget |brew install wget | |
|rename |brew install rename | |
|python |brew install python | |
|python3 |brew install python3 | |
|ruby |brew install ruby | |
|pathogen | |wget from GH vim.org/scripts/script.php?script_id=2332| |
|nerdtree |github.com/scrooloose/nerdtree| |
|vim-airline |github.com/vim-airline/vim-airline| |
|vim-multiple-cursors |github.com/terryma/vim-multiple-cursors| |
|cocoapods |sudo gem install cocoapods --pre| |
|Sync Xcode directory | | |
|VirtualBox |virtualbox.org/wiki/Downloads | |
|Wireshark |wireshark.org | |
|Docker |hub.docker.com/editions/community/docker-ce-desktop-mac | |

# Other

|Step |Source |Notes |
|--- |--- |--- |
|Alfred |alfredapp.com |Set keyboard shortcut to ⌘+Space |
|Audacity |https://github.com/audacity/audacity/ | |
|Disk Inventory X |derlien.com/downloads | |
|Evernote |evernote.com/download |Set font to Mono Regular 14; Disable context |
|Franz |meetfranz.com | |
|Garmin Express |garmin.com/sv-SE/software/express/mac/ | |
|get_iplayer |github.com/get-iplayer/get_iplayer | |
|Google Drive |drive.google.com | |
|Handbrake |handbrake.fr/downloads.php | |
|iStat Menus |files.bjango.com/istatmenus5/istatmenus5.32.zip | |
|MediaHuman Audio Converter |mediahuman.com/audio-converter | |
|Plex |plex.tv/media-server-downloads/#plex-app | |
|Postman |postman.com/downloads/ | |
|Slate |web.archive.org/web/20200814034452/http://slate.ninjamonkeysoftware.com/Slate.dmg |Config; enable Accessibility in Privacy preferences |
|SnappyApp |App Store | |
|Spotify |spotify.com/us/download | |
|TeamViewer |teamviewer.com/en/download/mac | |
|TftpServer |ww2.unime.it/flr/tftpserver | |
|Things 3 |App Store | |
|VLC |videolan.org/vlc/download-macosx.html | |
|Zwift |zwift.com/eu/download | |
