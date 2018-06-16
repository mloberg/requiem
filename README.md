# Requiem

**abandoned** - This project has been abandoned. It was an interesting experiment in how to manage a local Mac environment using Anisble. I didn't use it much, and every time I did, it seemed like something needed to be tweaked in order to work.

My Mac setup using Ansible.

## Installing

1. Install Apple's command line tools (`xcode-select --install`)
2. Install Ansible (`sudo easy_install pip && sudo pip install ansible`)
3. `script/requiem`

It will install a `requiem` executable in your path that you can run at any
time.

## Computer Specific Settings

1. `cp config/local.example.yml config/local.yml`
2. Edit to fit the machines requirements
