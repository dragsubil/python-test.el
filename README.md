# python-test - Python testing integration

*Author:* Mario Rodas <marsam@users.noreply.github.com><br>
*Version:* 0.1<br>

`python-test.el` allows the execution of python tests from Emacs.

## Setup

### Python objects

| objects      | function                 |
| -------------|--------------------------|
| class        | `python-test-class`      |
| method       | `python-test-method`     |
| function     | `python-test-function`   |
| file         | `python-test-file`       |
| project      | `python-test-project`    |

### Test frameworks

+ [nose][]
+ [pytest][]
+ [unittest][]: Needs the command-line interface available since python >=2.7

### TODO

+ Fontify "Captured stdout call" from py.test
+ Add support for --pdb flag

[nose]: https://nose.readthedocs.org/
[pytest]: https://pytest.org/
[unittest]: https://docs.python.org/library/unittest.html "Unit testing framework"


---
Converted from `python-test.el` by [*el2markdown*](https://github.com/Lindydancer/el2markdown).
