# Playbook

> Ansible playbook with essential dependencies & development environments on the Debian / CentOS / Darwin Operating Systems.

### Welcome to Contribute, Share, Learning on same time!

## Usage

```shell
ansible-playbook -i inventory/localhost playbook.yml
```

You can change

* `-i inventory/*` argument - hosts
* `playbook.yml` argument - roles
* `-v` argument - output info or `-vvv` for much more
* `roles/example` role files - test or show your magicial config for examples

## Todo

* [ ] dependencies
  * [x] git
  * [x] curl
  * [x] python3
  * [x] nvim
  * [ ] tmux
  * [ ] fish
  * [ ] go
  * [ ] mysql
  * [ ] nginx
  * [ ] docker
  * [ ] i3-wm
* [ ] other things
  * [ ] Travis
  * [ ] CircleCI
  * [ ] Readme

## LICENSE

MIT
