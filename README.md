# HCheck
HCheck is a host bug checking tool for tunneling via HTTP Websocket.

This tool is built using Javascript, runs using Nodejs and utilizes "curl" to send Websocket requests.

## Required Programs

* [__Termux__](https://f-droid.org/packages/com.termux/). Android does not have a terminal like Linux in general, so the Termux application is needed to run programs.
* [__Git__](https://git-scm.com/downloads). Required to clone this repository
* [__Nodejs__](https://nodejs.org). HCheck is a Javascript script and requires Nodejs to run for terminal.
* Standard command
  * curl

## Install and Execution
Run the commands below:<br>
`apt update && apt upgrade -y`<br>

`apt install curl git nodejs -y`<br>

`git clone https://github.com/ZeltNamizake/HCheck && cd HCheck`<br>

`chmod +x hcheck`<br>

`./hcheck -h`
