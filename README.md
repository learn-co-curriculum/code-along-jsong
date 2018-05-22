# Code Along With Jimmy Song

This course provides in-depth coverage of Elliptic Curve Digital Signature Algorithm (ECDSA), how ECDSA functions and how it is used to provide signing and verification of Bitcoin transactions.  After covering the basics, Jimmy dives into and explains Bitcoin transaction data structure, including Bitcoin scripting opcodes - how these transactions are formed and interpreted by Bitcoin nodes.

<iframe width="560" height="315" src="https://www.youtube.com/embed/e6voIwB-An4" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

To complete tasks in this course, you will need to setup the appropriate python environment as follows:
Install `python3`, `virtualenv`, `git`

```
$ git clone http://github.com/bitcoinedge/devplus...
$ cd devplusplus
$ virtualenv -p python3 .venv
$ .  .venv/bin/activate
$ pip install -r requirements.txt
$ jupyter notebook
```

Your browser should open up a jupyter notebook.
