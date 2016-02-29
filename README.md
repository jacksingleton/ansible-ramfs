Role Name
=========

Mount an in-memory `ramfs` filesystem.

`ramfs` is a very simple in-memory filesystem that will never be written to swap.

Note that `ramfs` does not have a size limit. Anyone with write access will be able to exhaust the memory on the machine.

Role Variables
--------------

* `ramfs_path`: Where the in-ram filesystem should be mounted
* `ramfs_mode`: Mount point permissions, defaults to a restrictive `0600`

Example Playbook
----------------

See test.yml

License
-------

BSD
