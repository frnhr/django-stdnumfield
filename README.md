[![CircleCI](https://circleci.com/gh/frnhr/django-stdnumfield/tree/master.svg?style=shield)](https://circleci.com/gh/frnhr/django-stdnumfield/tree/master)
[![codecov](https://codecov.io/gh/frnhr/django-stdnumfield/branch/master/graph/badge.svg)](https://codecov.io/gh/frnhr/django-stdnumfield)

version: 0.1.5

## Usage:

    from stdnumfield.models import StdNumField

    field = StdNumField(
        'hr.oib',  # stdnum format
        exception_text=_("Not maching format {}"),  # you can override exception message
    )

## What's an stdnum?

See [python-stdnum](https://arthurdejong.org/python-stdnum/doc/1.5/index.html)
