.. Connexion documentation master file, created by
   sphinx-quickstart on Wed Jun 17 12:09:55 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. warning::

    This is the WIP documentation for Connexion 3.0 which is currently in alpha. You might want to
    read the documentation for the latest `stable version`_ instead.

    If you want to try out Connexion 3.0, refer to the :ref: `v3`_ section.

Welcome to Connexion's documentation!
=====================================

Connexion is a Python web framework that makes spec-first and api-first development easy. You
describe your API in an `OpenAPI`_ (or swagger) specification with as much detail as you want and
Connexion will guarantee that it works as you specified.

Connexion Features
------------------

Based on your specification, Connexion provides the following functionality:

* Automatic routing to your Python functions
* Authentication
* Request validation
* Parameter parsing and injection
* Response serialization
* Response validation
* A Swagger UI console with live documentation and 'try it out' feature

Connexion also helps you write your OpenAPI specification and develop against it by providing a
command line interface which lets you test and mock your specification.

.. code-block:: bash

    connexion run openapi.yaml


Why Connexion?
--------------

Being spec-first is what makes Connexion unique in the Python ecosystem. With Connexion, you write
your API specification first, and automatically get a lot of functionality. With all other popular
Python web frameworks, you write your functionality first, and automatically get your specification.

We choose the spec-first approach because it:

* Stimulates thinking about the design of your API and enables quick feedback loops
* Creates a common understanding of how the API should work
* Allows server and client development in parallel
* Enables contract testing
* Allows for orchestrating multiple layers of your API stack from one contract (eg. API Gateway)

For a more detailed explanation about the benefits of working spec-first, or an overview of helpful
tooling, have a look at our `recommended resources`_.

Documentation
-------------

.. toctree::
   :maxdepth: 2

   quickstart
   middleware
   cli
   routing
   request
   response
   security
   cookbook
   exceptions
   v3

Recommended resources
---------------------

About the advantages of working spec-first:

* `Blog Atlassian`_
* `API guidelines Zalando`_
* `Blog ML6`_
* `Blog Zalando`_

Tools to help you work spec-first:

* `Online swagger editor`_
* `VS Code plugin`_
* `Pycharm plugin`_

.. _stable version: https://connexion.readthedocs.io/en/stable/
.. _v3: https://connexion.readthedocs.io/en/latest/v3.html
.. _OpenAPI: https://openapis.org/
.. _Blog atlassian: https://www.atlassian.com/blog/technology/spec-first-api-development
.. _Blog ML6: https://blog.ml6.eu/why-we-decided-to-help-maintain-connexion-c9f449877083
.. _Blog Zalando: https://engineering.zalando.com/posts/2016/12/crafting-effective-microservices-in-python.html
.. _API guidelines Zalando: https://opensource.zalando.com/restful-api-guidelines/#api-first
.. _Online swagger editor: https://editor.swagger.io/
.. _VS Code plugin: https://marketplace.visualstudio.com/items?itemName=42Crunch.vscode-openapi
.. _Pycharm plugin: https://plugins.jetbrains.com/plugin/14837-openapi-swagger-editor
