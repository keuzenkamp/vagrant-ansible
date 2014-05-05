1. run the postinstall script with curl -L https://gist.github.com/danvaida/7fab83e0962e8405799a/raw/postinstall.sh | bash
2. shut down the machine
3. vagrant package --base wheezy-vagrant --out wheezy-vagrant.box
4. vagrant box add wheezy-vagrant wheezy-vagrant.box
5. run 'vagrant init' in a directory of choice
6. edit the Vagrant file and change config.vm.box = "ubuntu-11.10" and other settings...

useful pyYAML validator: https://yaml-online-parser.appspot.com/
