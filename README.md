> "When it started out, it was an awful lot of fun." (c) Alan Perlis

`suxx-tracker` suxx, because

 * its name is ugly in both lower and Capitalized Case
 * it is too verbose and too concise at the same time
 * it is a plain text file that can not be parsed
 * you need to pass GitHub registration and know the interface

## Contents

- [GCC](#gcc)

- [Mailman](#mailman)

- [Python](#python)
    - [python.org](#pythonorg-as-a-community-site)
    - [python 3](#python-3)
    - [virtualenv](#virtualenv)

- [Ubuntu PPA](#ubuntu)


## GCC

`gcc 4.x` suxx, because:

    $ gcc main.c
    $ ls main*
    main.c

## Mailman

`mailman` 2.x mailing list software suxx, because

 * it doesn't have search button for its archives
 * you can't reply to the thread if you're not already subscribed
 * you can't subscribe only to threads you're interested in
 * if you are not subscribed, there is no guaranteed mail delivery
   because it is not clear if you address will be added to CC

## Python

### python.org as a community site

 * proprietary owned by PSF (there is no sign that it is open source)
 * code is not reusable because of verbose license with no owner
 * doesn't credit people who contributed to it (everything links to PSF)

### Python 3

 * it suxx, because it managed to ship `venv` module with all suxx facts from `virtualenv` chapter below
 * it suxx, because for some reason binary data is now math (integers)
```python
line = b'12345'
if line[0] == b'1':
  print('python 2')
else:
  print('python 3')
```

### virtualenv

`virtualenv` (python-virtualenv) suxx, because

 * you can't just login and logout from the env, you need to `activate` it
 * you can't just refence sctipt in virtualenv - you need platform-aware conditional to choose `bin/` on Linux and `Scripts\` on Windows

## Ubuntu PPA

`Ubuntu PPA` suxx, because

 * you can't just `install inkscape from https://launchpad.net/~inkscape.dev/+archive/ubuntu/stable`.
 * `PPA launchpad pages` like https://launchpad.net/~inkscape.dev/+archive/ubuntu/stable just don't have a straightforward single *visible* command needed to the istall the stuff right away ([launchpad#1458513](https://bugs.launchpad.net/launchpad/+bug/1458513))

## Competitors

 * https://wiki.theory.org/YourLanguageSucks

