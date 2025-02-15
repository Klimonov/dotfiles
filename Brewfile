# See `brew leaves` and `brew bundle dump`

# Essentials
brew 'mas'
cask 'iterm2'
brew 'vim'	# Must be before macvim
cask 'macvim'

# Install packages
brew 'autoconf'
brew 'automake'
brew 'bash'
brew 'bash-git-prompt'
brew 'bluetoothconnector'
brew 'cmake'
brew 'difftastic'
brew 'dos2unix'
brew 'get_iplayer'
brew 'gh'
brew 'gifsicle'
brew 'git'
brew 'git-extras'
brew 'git-lfs'
# brew 'git-subrepo'
brew 'git-utils'	# Conflicts with git-extras and removes it. git-extras is more important
brew 'gnupg'
brew 'gradle'
brew 'grc'
brew 'grep'
brew 'hub'
brew 'jenv'
brew 'jq'
brew 'lesspipe'
brew 'lsusb'
brew 'lz4'
brew 'maven'
brew 'mercurial'
brew 'node'
brew 'p7zip'
brew 'pinentry-mac'
brew 'pngcrush'
brew 'pstree'
brew 'ruby'
brew 'sl'
brew 'source-highlight'
brew 'telnet'
brew 'tmux'
brew 'tree'
brew 'unrar'
brew 'yarn'
brew 'youtube-dl'
brew 'yt-dlp'

tap 'aws/tap'
brew 'aws-sam-cli'
brew 'awscli'

# Conflicts
# These packages conflict, and git-utils will be unlinked
# Make sure to brew link --overwrite git-utils after
# git-extras is more important (git-incoming, etc.)
brew 'git-utils'
brew 'git-extras'

# Completion packages
brew 'bash-completion@2'
brew 'brew-cask-completion'
brew 'bundler-completion'
brew 'docker-completion'
brew 'docker-compose-completion'
# Already part of docker-machine
# brew 'docker-machine-completion'
brew 'gem-completion'
brew 'maven-completion'
brew 'open-completion'
brew 'pip-completion'
brew 'rake-completion'
brew 'ruby-completion'

# Casks
# Must come before anyone else using mono-mdk, as it installs its own version
# which is older. Installing mono-mdk will install the up to date version
cask 'visual-studio'
cask 'mono-mdk'

cask '1password'
# cask '1password6'
cask 'alfred'
cask 'avibrazil-rdm'
cask 'backblaze'
cask 'bartender'
cask 'bbc-iplayer-downloads'
cask 'beyond-compare'
cask 'camtasia'
cask 'dash'
cask 'deepl'
cask 'discord'
cask 'dotnet-sdk'
cask 'dropbox'
cask 'ferdi'
cask 'freedome'
cask 'github'
cask 'gitter'
cask 'google-chrome'
cask 'haptickey'
# cask 'hyperdock'
# Either dockview or dockmate. Both paid, appstore?
# Or just use App Expose on the dock icon - but this doesn't show full screen windows
cask 'hyperswitch'
cask 'jd-gui'
cask 'jetbrains-toolbox'
cask 'keybase'
cask 'logitech-presentation'
cask 'mcgimp'
cask 'openemu'
cask 'openinterminal'
cask 'p4v'
cask 'parallels'
cask 'pinta'
cask 'powershell'
cask 'qlcolorcode'
cask 'qlmarkdown'
cask 'quicklook-json'
cask 'rcdefaultapp'
cask 'simple-comic'
cask 'shortcutdetective'
cask 'sizeup'
cask 'skype'
cask 'sloth'
cask 'spotify'
cask 'suspicious-package'
cask 'turbo-boost-switcher'
cask 'ukelele'
cask 'unity-hub'
cask 'visual-studio-code'
cask 'vlc'
cask 'yacreader'
cask 'yed'
cask 'yourkit-java-profiler'

# Maybes
# cask 'bettertouchtool'
# cask 'cd-to' # No longer supports iterm!?
# cask 'gitkraken'
# cask 'qlstephen' # Extension-less files. Handled by iPreview?
# cask 'seashore'
# cask 'tunnelblick'
# cask 'unshaky'

# Docker
# I always forget what docker component does what. This is probably not the best place for this, but meh.
# The docker cask installs Docker for Mac, aka Docker Desktop. This will install the command line tools on first run.
# /usr/local/bin/docker, docker-compose, docker-credential-desktop, docker-credential-osxkeychain
# Try `docker run -dp 80:80 docker/getting-started` and browsing to http://localhost
# Default docker vm is stored in ~/Library/Containers/com.docker.docker
# You can also use docker-machine with the docker-machine-parallels driver to host the docker vm in Parallels.
# This works, but requires extra setup to get docker talking to that host
cask 'docker'
# brew 'docker-machine'
# brew 'docker-machine-parallels'

# Dotnet SDK
tap 'isen-ng/homebrew-dotnet-sdk-versions'
cask 'dotnet-sdk3-1-400'

# Fonts
tap 'homebrew/cask-fonts'
cask 'font-cascadia-code'
cask 'font-consolas-for-powerline'
cask 'font-fira-code'
cask 'font-hasklig'
casl 'font-iosevka'
casl 'font-iosevka-aile'
casl 'font-iosevka-etoile'
casl 'font-iosevka-sparkle'
cask 'font-jetbrains-mono'
cask 'font-liberation-mono-for-powerline'
cask 'font-noto-sans-cjk-kr'
cask 'font-roboto'
cask 'font-source-code-pro'
cask 'font-victor-mono'

tap 'colindean/fonts-nonfree'
cask 'font-microsoft-office'

# App Store - `mas list`
mas 'DaisyDisk', id: 411643860
mas 'OneDrive', id: 823766827
mas 'Pocket', id: 568494494
mas 'Reeder', id: 1449412482
mas 'Shazam', id: 897118787
mas 'Slack', id: 803453959
mas 'Things 3', id: 904280696
mas 'Tweetbot', id: 1384080005
mas 'WiFi Explorer Lite', id: 1408727408
# Takes too long, with no visible progress
# mas 'Xcode', id: 497799835

# Safari extensions
mas 'AdGuard for Safari', id: 1440147259
# mas 'AdBlock', id: 1402042596
# mas 'AdBlock Plus', id: 1432731683
# mas 'Ghostery Lite', id: 1436953057
# mas 'Minimal Consent', id: 1514164630
mas 'Save to Pocket', id: 1477385213
mas 'Tab Space', id: 1473726602
mas 'Tampermonkey', id: 1482490089
