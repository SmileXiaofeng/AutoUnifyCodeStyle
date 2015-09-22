# AutoUnitCodeStyle

A tool to auto unit your team code style before commit. You can install AutoUnitCodeStyle by one command and all your code that commit to repo will be formatted by clang-format.You can edit your code style in .clang-format file which is in your project root directory.[For all code options you can use please read Clang 3.8 documentation](http://clang.llvm.org/docs/ClangFormatStyleOptions.html/).

If you have a project and need teamwork,it’s great way to unify team code style.You don’t have to write a code style guide and give all your teammate and spend much time to learn it.Just use same code style options and all the project code would look like one person wrote. Enjoy that.

### Installation

First,You should change the current working directory to the target project,then you can install it by pasting following command at a Terminal prompt.

``` 
####first cd to the target project 
wget -O - https://raw.github.com/SmileXiaofeng/AutoUnitCodeStyle/master/install | bash
```

All teammates should run the command In project directory to install AutoUnitCodeStyle.

### License

AutoUnitCodeStyle is released under the MIT license. See LICENSE for details.