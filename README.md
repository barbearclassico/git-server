Project to spin up a Git server
===============================



Pre-flight
==========

Ansible and Virtualbox
----------------------


This requires ansible, setup a virtual environment.


Get submodules
--------------

```
git submodules update --init
```


Spin up a testing server
------------------------

Add `gitserver.dah` to `/etc/hosts`:

```
127.0.0.1       gitserver.dah
```

call vagrant:

```
vagrant up
```

Go to [http://gitserver.dah:8800](http://gitserver.dah:8800)

