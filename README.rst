=======================================
pre-commit_ unittest super call checker
=======================================

Checks for the existance of super calls in ``setUp``, ``tearDown``, ``setUpClass``, ``tearDownClass`` and ``setUpTestData``.


Usage
=====

Add this to your ``.pre-commit-config.yaml`` file for pre-commit_:

.. code-block:: yaml

   repos:
    -   repo: https://github.com/emilkholod/pre-commit-check-unittest-super/
        rev: master
        hooks:
        -   id: check-unittest-super


.. _pre-commit: https://pre-commit.com/
