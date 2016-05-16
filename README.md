
Vim for C++ Projects

Watching C++ vim gurus like Chandler Carruth and Manuel Klimek you can get the impression that all there is to it is installing YouCompleteMe and CtrlP and you have a full fledged C++ IDE... sadly it is not that simple :)

## The Tools

* YouCompleteMe
* CtrlP
* Silver searcher

### What you need to do


### Caveats, Warnings etc

* YouCompleteMe does *not* index your project. It indexes the files you open. This means for instance that while there is a "Go to Definition" command, it rarely works, since while code using a symbol needs access to the *declaration* in the proper include file, the *definition* should hopefully lie in a separate cpp file that is *not* know by the current cpp file.
* 

