..  _tutorial-set-up:

Create a new Django project
===========================

In this section we will create and deploy a new project in the Control Panel using `Django
<https://www.djangoproject.com/>`_, the most popular Python web application framework. The principles covered by the
tutorial will apply to any other development stack.

..  note::

    This tutorial is intended to introduce the basics of working with Divio, using Django as an example. **It is not a
    tutorial for Django**. However, you don't need to know Django or Python, or have them installed on your system.


..  include:: includes/02-create-project-1.rst


* *Python*: ``Python 3.x``
* *Project type*: ``Django``

..  admonition:: Django 2.2

    At the time of writing, version 2.2 is `Django's Long-Term Support release
    <https://www.djangoproject.com/download/#supported-versions>`_, and is
    guaranteed support until at least April 2022. This is the version currently
    selected by default in Divio projects.


..  include:: includes/02-create-project-2.rst


Since this is your own project, you can use our :ref:`single-sign-on <aldryn-sso>` to log in by selecting **Log in with
Divio**. You'll see the familiar Django admin for a new project.

.. image:: /images/intro-django-admin.png
   :alt: 'Django admin'
   :class: 'main-visual'


..  include:: includes/02-create-project-3.rst
