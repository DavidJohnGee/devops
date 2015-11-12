### DevOps

Brah. You do networking. You want to look at DevOps? Then install it like this:

####Install from PyPi

```
$ pip install the_devops
```

####Install from source

```
$ git clone https://github.com/davidjohngee/devops
$ cd devops
$ sudo python setup.py install
```

Maybe it will be know as 'thedevops'. Update soon

Because DevOps.

#### Work In Progress

This will always be modified. Get used to it.

On that note, create a PR and add your own devops flakes of magic.

####Usage

To check that the devops has been installed:

```python
$ python
>>> from devops.devops import devops
>>> thedevops = DevOps()
>>> print thedevops
Dude, you totally devopsificated
```

####Testing

Unit tests are included for tox. If you're going to DevOps, do it properly.

```python
$ tox
```

This also includes the flake8 static analysis tests.

####Code quality
The code is covered by the CRAPL license. See the LICENSE file.

####Serious purpose?

This is an educational package riding on the back of 'the devops', sweeping it's way through the industry.

If you want to add your own devops magic, add the feature, add the test and create a pull request.
