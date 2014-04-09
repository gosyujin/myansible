myansible
=========

自分の環境を作る用のansible-playbook

```bash
$ ansible-playbook -i servershost site.yml -u vagrant --private-key=~/.vagrant.d/insecure_private_key
```

pipとansibleのインストール

```bash
$ curl -kL https://raw.github.com/pypa/pip/master/contrib/get-pip.py | sudo -E python; sudo -E pip install ansible
```
