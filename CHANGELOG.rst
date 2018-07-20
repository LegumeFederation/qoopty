Changelog
---------

.. snip

- Name of package abstracted away as much as possible to enable
  code reuse.

- Changed ``var/`` and ``etc/`` directory structures to play nicely
  with root at /.

- ``LORAX_ROOT`` is now always the location of the ``lorax_env``
  script and is defined at install time.

- ``run_in_lorax_env`` renamed to simply ``lorax_env``


0.0.1
~~~~

- Carved out of ``lorax`` for re-use elsewhere.
