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

※ Mac OS X, Xcode 5.1 の場合、ansibleが入らない

- http://blog.quality-season.jp/1579410.html
- https://github.com/romanbsd/fast-stemmer/issues/9

```bash
$ sudo ARCHFLAGS=-Wno-error=unused-command-line-argument-hard-error-in-future pip install ansible
```
