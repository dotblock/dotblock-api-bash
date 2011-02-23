# DotBlock API Bash Client

This is a bash client for <http://api.dotblock.com/>.


## Usage

    Usage:

      dotblock-api [command]

    Commands:

      server-list                : List virtual server ids for this account
      server-info <serverid>     : Show info for <serverid>
      server-boot <serverid>     : Boot <serverid>
      server-reboot <serverid>   : Reboot <serverid>
      server-suspend <serverid>  : Suspend <serverid>
      server-resume <serverid>   : Resume <serverid>
      server-shutdown <serverid> : Shutdown <serverid>


## Install

    wget https://github.com/dotblock/dotblock-api-bash/raw/master/bin/dotblock-api
    chmod +x dotblock-api
    sudo mv dotblock-api /usr/local/bin


## License

MIT License, see LICENSE in this repo.
