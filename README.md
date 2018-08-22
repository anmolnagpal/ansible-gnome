<p align="center"><img src="https://user-images.githubusercontent.com/4303310/44457306-f3d1c300-a613-11e8-8e86-17f4e8f7b24b.png" /></p>


> Ansible role to deploy/setup Gone on **AWS ec2 ubuntu** 
<p align="center">
    <a href="LICENSE.md">
      <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square" alt="Software License">
    </a>
    <a href="https://www.paypal.me/anmolnagpal">
      <img src="https://img.shields.io/badge/paypal-donate-179BD7.svg?style=flat-squares" alt="Donate">
    </a>
  </p>
</p>
## Role Variables

```yamlex
user: anmolnagpal
password: 6jCXkfGbjq2VsBgTCFZWyufq3GFrqBSNwY8sTXzUjCVN6d8
```

## Example Playbook

```yaml
- hosts: ubuntu
  remote_user: ubuntu
  become: true
  roles:
    - role: ansible-gnome

```
## 👬 Contribution
- Open pull request with improvements
- Discuss ideas in issues

- Reach out with any feedback [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/anmol_nagpal.svg?style=social&label=Follow%20%40anmol_nagpal)](https://twitter.com/anmol_nagpal)
