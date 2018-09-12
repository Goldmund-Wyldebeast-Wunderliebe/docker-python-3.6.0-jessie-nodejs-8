docker-python-3.6.0-jessie-nodejs-8
-----------------------------------
Debian Jessie with:python 3.6.0, NodeJS, NVM, git, python-pip, Firefox 47 preinstalled

Used for Plone/Django test runners in Gitlab CI.

Usage
=====

To pull:

.. code-block:: sh

	docker pull gw20e/jessie-py3.6.0-nodejs-8:latest

To push:

.. code-block:: sh

    docker build -t gw20e/jessie-py3.6.0-nodejs-8:latest .
	docker push gw20e/jessie-py3.6.0-nodejs-8:latest

To run:

.. code-block:: sh

	docker run gw20e/jessie-py3.6.0-nodejs-8

Gitlab CI
=========

In your `gitlab-ci.yml` file add the image statement to use this image:

.. code-block:: text

    image: gw20e/jessie-py3.6.0-nodejs:latest
