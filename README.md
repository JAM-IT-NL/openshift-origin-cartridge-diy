# OpenShift DIY Cartridge
This cartridge is documented in the [Cartridge Guide](http://openshift.github.io/documentation/oo_cartridge_guide.html#diy).

# Changes
* Create dir ~/.passenger
* Create dir ~/.npm
* Touch ~/.npmrc
* echo "gem: --no-document --no-ri --no-rdoc" > ~/.gemrc

# Usage
rhc create-app myapp http://cartreflect-claytondev.rhcloud.com/github/xenonl/openshift-origin-cartridge-diy
