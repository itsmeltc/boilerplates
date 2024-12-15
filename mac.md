# macOS Setup and Tweaks

|Step |Location |Notes |
|--- |--- |--- |
|Run through macOS installer | |Disable metrics and enable FileVault |
|Note down FileVault decryption key | | |
|Install all updates |About This Mac >> Software Update |Reboot and recheck until no more updates |
|Turn on dock hiding |System Settings >> Dock | |
|Change computer hostname |System Settings >> General |Remove name/username |
|Enable trackpad tap to click |System Settings >> Trackpad >> Point & Click | |
|Enable trackpad two finger secondary click |System Settings >> Trackpad >> Point & Click | |
|Enable trackpad swipe between pages |System Settings >> Trackpad >> More Gestures | |
|Enable mouse secondary click |System Settings >> Mouse | |
|Enable mouse swipe gestures |System Settings >> Mouse | |
|Enable three finger drag |System Settings >> Accessibility >> Pointer Control >> Mouse & Trackpad >> Trackpad Options | |
|Set mouse tracking speed to 8 (fast) |System Settings >> Mouse | |
|Set key repeat speed to 10 (fast) |System Settings >> Keyboard | |
|Set delay until repeat to 10 (short) |System Settings >> Keyboard | |
|Disable Spotlight keyboard shortcuts |System Settings >> Keyboard |Used by Alfred later |
|Enable Firewall |System Settings >> Network |Enable stealth mode |
|Set require password to immediately |System Settings >> Lock Screen | |
|Change screen saver start time to 1 minute |System Settings >> Lock Screen | |
|Set bottom left hot corner to start screen saver |System Settings >> Desktop & Dock >> Hot Corners | |
|Set top left hot corner to Mission Control |System Settings >> Desktop & Dock >> Hot Corners | |
|Set first day of week to Monday |System Settings >> Language & Region | |
|Set date formart to dd/mm/yyyy |System Settings >> Language & Region | |
|Set number format to decimal point |System Settings >> Language & Region | |
|Add and set preferred language to English (United Kingdom) |System Settings >> Language & Region |Keep "English" as secondary then reboot |
|Disable Guest User account |System Settings >> Users & Groups | |
|Display login window as name and password |System Settings >> Lock Screen | |
|Disable show user name and photo |System Settings >> Lock Screen | |
|Set resolution to More Space |System Settings >> Displays | |
|Always show volume button in menu bar |System Settings >> Control Centre | |
|Show Bluetooth button in menu bar |System Settings >> Control Centre | |
|Hide battery status in menu bar |System Settings >> Control Centre | |
|Hide date, day of the week, and set time menu bar status to analogue |System Settings >> Control Centre | |
|Remove Focus profiles and disable sharing across devices |System Settings >> Focus | |
|Show home folder in Finder |Finder >> Settings | |
|Show hard disks in Finder |Finder >> Settings | |
|Show all filename extensions |Finder >> Settings >> Advanced | |
|Build locate database |sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.locate.plist | |
|Prevent iPhone from auto-syncing with iTunes |iTunes Preferences >> Devices | |

# Browser

|Application |Source |Notes |
|--- |--- |--- |
|Firefox |mozilla.org/en-GB/firefox |Sync bookmarks with Firefox Account |
|Enable bookmarks toolbar | | |
|Open previous windows and tabs |Firefox Preferences >> General | |
|Set homepage, new windows, and new tabs to Blank Page |Firefox Preferences >> Home | |
|Disable Firefox Home Content |Firefox Preferences >> Home | |
|Add search bar in toolbar |Firefox Preferences >> Search | |
|Remove all search engines but Google |Firefox Preferences >> Search | |
|Set Content Blocking to Strict |Firefox Preferences >> Privacy & Security | |
|Tell websites not to sell my data and enable Do Not Track |Firefox Preferences >> Privacy & Security | |
|Disable password management |Firefox Preferences >> Privacy & Security | |
|Disable payment method autofill |Firefox Preferences >> Privacy & Security | |
|Disable data collection |Firefox Preferences >> Privacy & Security | |
|Enable HTTPS Only mode|Firefox Preferences >> Privacy & Security | |
|DuckDuckGo Privacy Essentials |addons.mozilla.org/en-GB/firefox/addon/duckduckgo-for-firefox | |
|Enhancer for YouTube |addons.mozilla.org/en-GB/firefox/addon/enhancer-for-youtube | |
|Facebook Container |addons.mozilla.org/en-GB/firefox/addon/facebook-container | |
|Privacy Badger for Firefox |eff.org/privacybadger | |
|Tab Reloader (page auto refresh) |addons.mozilla.org/en-GB/firefox/addon/tab-reloader | |
|Toucan |jointoucan.com | |
|uBlock Origin for Firefox |addons.mozilla.org/en-GB/firefox/addon/ublock-origin | |
|Hangouts for Firefox |google.com/tools/dlpage/hangout | |
|Chrome |google.co.uk/chrome/browser/desktop | |

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
|Adobe Creative Cloud |creativecloud.adobe.com/apps/download/creative-cloud | |
|Alfred |alfredapp.com |Set keyboard shortcut to ⌘+Space |
|Audacity |github.com/audacity/audacity/ | |
|Audible |apps.apple.com/us/app/audible-audio-entertainment/id379693831 | |
|Disk Inventory X |derlien.com/downloads | |
|Evernote |evernote.com/download |Set font to Mono Regular 14; Disable context |
|Franz |meetfranz.com | |
|Garmin Express |garmin.com/sv-SE/software/express/mac/ | |
|get_iplayer |github.com/get-iplayer/get_iplayer | |
|Google Drive |drive.google.com | |
|Handbrake |handbrake.fr/downloads.php | |
|iStat Menus |files.bjango.com/istatmenus5/istatmenus5.32.zip |Or from backup |
|Joplin |joplinapp.org/download | |
|MediaHuman Audio Converter |mediahuman.com/audio-converter | |
|Plex |plex.tv/media-server-downloads/#plex-app | |
|PressReader |apps.apple.com/us/app/pressreader-news-magazines/id313904711 | |
|Postman |postman.com/downloads/ | |
|Slate |web.archive.org/web/20200814034452/http://slate.ninjamonkeysoftware.com/Slate.dmg (or backup) |Config; enable Accessibility in Privacy preferences |
|Snappy.app |App Store |Or from backup |
|Spotify |spotify.com/us/download | |
|TeamViewer |teamviewer.com/en/download/mac | |
|TftpServer |ww2.unime.it/flr/tftpserver | |
|Things 3 |App Store | |
|VLC |videolan.org/vlc/download-macosx.html | |
|Zwift |zwift.com/eu/download | |
