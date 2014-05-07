# node-install

Extremely simple node install script written in bash.

One-line install

	curl -fs https://raw.githubusercontent.com/mafintosh/node-install/master/install | sh

It is easy to use

	node-install 0.10.10 # installs node 0.10.10
	node-install 0.8.24  # installs node 0.8.24
	node-install latest  # installs latests stable node

It also features autocompletion!

	node-install --completion --save # and follow the instructions
	node-install <tab><tab> # prints all available versions

It is licensed under MIT
