# OCLint - http://oclint.org

[![Travis CI Status](https://api.travis-ci.org/oclint/oclint.svg?branch=master)](https://travis-ci.org/oclint/oclint) [![Coverage Status](https://coveralls.io/repos/github/oclint/oclint/badge.svg?branch=master)](https://coveralls.io/github/oclint/oclint?branch=master)

OCLint is a static code analysis tool for improving quality and reducing defects
by inspecting C, C++ and Objective-C code.

It looks for potential problems that aren't visible to compilers, for example:

* Possible bugs - empty if/else/try/catch/finally statements
* Unused code - unused local variables and parameters
* Complicated code - high cyclomatic complexity, NPath complexity and high NCSS
* Redundant code - redundant if statement and useless parentheses
* Code smells - long method and long parameter list
* Bad practices - inverted logic and parameter reassignment
* ...

For more information, visit [http://oclint.org](http://oclint.org)

如果你本地没有`CMake`和`Ninja`两个编译环境, 并且安装失败或者是`CMake`编译阶段频繁失败, 可以使用我提供的编译好的`0.15.0`版本

在`feature/0.15.0`的分支下我已经提供了本地编译好的资源文件

默认`build`被设置了忽略, 为了更明显的辨认, 我将文件夹名称改为`oclint-0.15.0-build`, 名称可以任意修改, 关键是环境路径一定要设置正确.
