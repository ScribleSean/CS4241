# CS4241
Coursework for CS4241 in A23

Resetting Submodules
~~~ git
git clean -xfd
git submodule foreach --recursive git clean -xfd
git reset --hard
git submodule foreach --recursive git reset --hard
git submodule update --init --recursive
~~~

Adding Submodules
~~~ git
git submodule add  https://github.com/ScribleSean/a4-sean-arackal a4
~~~