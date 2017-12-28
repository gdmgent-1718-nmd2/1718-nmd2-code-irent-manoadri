New Media Design II 2017-2018
=============================

Opdracht iRent
--------------

### Installatie kloon

```
PS> c
<<<<<<< HEAD
PS> git clone »naam-van-de-repo« »naam-van-de-map«
PS> c »naam-van-de-map«
=======
PS> git clone «repositorynaam» «mapnaam»
PS> c «mapnaam»
>>>>>>> 35ee00574967047c1491e9402279aacbab95729c
PS> git submodule update --init
PS> git submodule foreach 'git checkout v4-dev'
```


```
<<<<<<< HEAD
PS> c »naam-van-de-map«
=======
PS> c «mapnaam»
>>>>>>> 35ee00574967047c1491e9402279aacbab95729c
PS> bundle update
PS> bundle exec jekyll serve
```

### Origineel

Als je aan een eigen project Bootstrap als een **Git Submodule** wil toevoegen.

```
PS> c
<<<<<<< HEAD
PS> mkdir »naam-van-de-map«
PS> c »naam-van-de-map«
=======
PS> mkdir «mapnaam»
PS> c «mapnaam»
PS> git init
>>>>>>> 35ee00574967047c1491e9402279aacbab95729c
PS> git submodule add --branch v4-dev --depth 1 https://github.com/twbs/bootstrap/ _vendor/bootstrap
```

### Voorbeeldsite

<http://www.gdm.gent/1718-nmd2-code-irent/>