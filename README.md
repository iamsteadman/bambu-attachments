# Bambu Attachments

A setup for handling generic model attachments

## About Bambu Attachments

This package contains a simple set of models and admin helper classes that allow you to add media
attachments to any model.

## About Bambu Tools 2.0

This is part of a toolset called Bambu Tools. It's being moved from a namespace of `bambu` to its own
'root-level' package, along with all the other tools in the set. If you're upgrading from a version prior
to 2.0, please make sure to update your code to use `bambu_attachments` rather than `bambu.attachments`.

## Installation

Install the package via Pip:

```
pip install bambu-api
```

Add it to your `INSTALLED_APPS` list:

```python
INSTALLED_APPS = (
    ...
    'bambu_attachments'
)
```

Run `manage.py syncdb` or `manage.py migrate` to setup the database tables.

## Documentation

Full documentation can be found at [ReadTheDocs](http://bambu-attachments.readthedocs.org/).

## Questions or suggestions?

Find me on Twitter (@[iamsteadman](https://twitter.com/iamsteadman))
or [visit my blog](http://steadman.io/).
