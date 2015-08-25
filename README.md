# Brightbox Ruby Ansible Role

Used to install ruby 1.8 with [Ansible](http://www.ansible.com/) using the [brightbox PPA](https://launchpad.net/~brightbox/+archive/ubuntu/ruby-ng). 

## Using

Include as a role in your Ansible playbook. Custom gems can be installed by editing defaults/main.yml. You can either install the latest version for the platform by adding the gem to `brightbox_ruby_default_gems`, or you can install specific versions of gems by adding an entry to `brightbox_ruby_versioned_gems`.

## License

* MIT
