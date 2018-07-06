# node-install

Extremely simple node install script written in bash.

One-line install

  curl -fs https://raw.githubusercontent.com/mafintosh/node-install/master/install | sh

It is easy to use

  node-install 0.10.10 # installs node 0.10.10
  node-install 0.8.24  # installs node 0.8.24
  node-install 10 # installs latest node 10

You can also make it print the command it runs to install instead of installing using the `--dry-run` flag

  node-install 10 --dry-run

It is licensed under MIT
