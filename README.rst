vsi
---

**v**ery **s**imple **i**nterpreter written in pure python without any
third party dependencies.


Installation
------------

you will need `python <https://www.python.org/downloads/>`_ interpreter and
`pip <https://pip.pypa.io/en/stable/installing/>`_ package manager
after that run this command

    $ pip install vsi

**note**: for linux and mac users you may want to prefix command with sudo


Quick Start
-----------

    # this is a comment

    # variables
    x := 1;
    y := x + 2;

    # printing
    print x;
    print y;

    # if statements
    if y > x then
        z := y;
    # optional else
    else
        z := x;
    done

    # while statemnt
    while x < 5 do
        x := x + 1;
        print x;
    done


save this to hello.vsi file and then

    $ vsi hello.vsi

output

    1
    3
    2
    3
    4
    5

see more examples at examples/ folder

LICENSE
-------
**MIT**

see LICENSE file for more information.