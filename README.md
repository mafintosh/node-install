# node-install

Extremely simple node install script build using [bashkit](https://github.com/mafintosh/bashkit).

One-line install

	 curl -fs https://raw.github.com/mafintosh/node-install/master/install | bash && . $(bashkit rc)

It is easy to use

	node-install 0.10.10 # installs node 0.10.10
	node-install 0.8.24  # installs node 0.8.24
	node-install latest  # installs latests stable node

It also features autocompletion!

	node-install <tab><tab> # prints all available versions

It is licensed under MIT