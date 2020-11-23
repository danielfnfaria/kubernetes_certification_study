# kubernetes_certification_study

This project was created for help me in the way of kubernetes certification

Requirements on host:
- vagrant
- virtualbox
- ansible

You can use your kubectl on host, for this you need copy /etc/kubernetes/admin.conf from master instance and put content in your ~/.kube/config

For use directly in master instance:

`vagrant ssh master`

## Training all things
*use training*

Install last version of kubernetes with 1 master and 2 workers

```bash
cd training
vagrant up
```

## To study simple install
*use training-install*

Setup 1 master and 2 workers without kubernetes installation

```bash
cd training-install
vagrant up
```

## To study upgrades
*use training upgrade*

Install kubernetes 1.18.0-00 for you can upgrade it, with 1 master and 2 workers

```bash
cd training-upgrade
vagrant up
```
