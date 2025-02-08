sample-novirt-8bitdev
=====================

This is an example of an 8-bit development project using [t8dev] without
a local virtualenv, i.e., t8dev is installed in the pre-existing
environment (whether that be the system environment or a virtualenv started
before anything here is run).

More typically, developers would want to do one of the following:
- Have a virtualenv specifically for the project, which would include t8dev
  and any other packages they need. (An example of this is not yet
  available.)
- Use t8dev source as a submodule, allowing development on t8dev along with
  the project. [0cjs/8bitdev] is an example of this.



<!-------------------------------------------------------------------->
[0cjs/8bitdev]: https://github.com/0cjs/8bitdev
[t8dev]: https://github.com/mc68-net/t8dev
