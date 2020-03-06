# ansible-firefox-deb
Ansible Playbook - Install latest stable Firefox and latest beta Thunderbird on Debian

This ansible playbook is a part of my ansible "base" role on my private repository.

If you don't want Firefox ESR on Debian:

# How to
```
git clone https://github.com/pboesch/ansible-firefox-deb
cd ansible-firefox-deb
ansible-playbook playbooks/mozilla-latest.yml -K
```

After that, when a new release is out, Firefox and Thunderbid will be updated automatically.

Warning: playbook will download FR release (?lang=fr) by default, you can override it with extra-var `mozilla_lang`
