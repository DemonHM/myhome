Base backages you should probably have on most dev ubuntu desktops:
```sh
sudo puppet apply --modulepath=/etc/puppet/modules -e "package { ['build-essential',\
                         'apt-transport-https',\
                         'gftp-text',\
                         'python-software-properties',\
                         'tagcoll',\
                         'super',\
                         'upstart',\
                         'debtags',\
                         's3cmd',\
                         'libaugeas-ruby1.8',\
                         'libaugeas-ruby1.9.1',\
                         'capistrano',\
                         'libopenssl-ruby',\
                         'ruby1.8-dev',\
                         'syslog-summary',\
                         'whois',\
                         'ngrep',\
                         'bash-completion',\
                         'netcat',\
                         'moreutils',\
                         'logcheck',\
                         'augeas-tools',\
                         'apticron',\
                         'git-core',\
                         'nfs-common',\
                         'locate',\
                         'sysvinit-utils',\
                         'logtail',\
                         'tmux',\
                         'vim',\
                         'ruby1.9.1',\
                         'rubygems1.8',\
                         'socat',\
                         'libruby1.8',\
                         'timelimit',\
                         'vnstat',\
                         'logwatch',\
                         'htop',\
                         'python-psutil']: ensure => present }"
                      
```
