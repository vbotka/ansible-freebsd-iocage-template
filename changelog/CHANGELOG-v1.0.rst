================================================
vbotka.freebsd_iocage_template 1.0 Release Notes
================================================

.. contents:: Topics


1.3.7
=====

Release Summary
---------------

Major Changes
-------------

Minor Changes
-------------
* Add debug0.yml tasks to display fit_templates.
* Update setup.yml tasks; Meta end_host changed to end_role
* Add vars samples.


1.3.6
=====

Release Summary
---------------
Mount filesystems, configure, and update pkg repos.

Major Changes
-------------

Minor Changes
-------------
* Optionally mount filesystems.
* Optionally configure and update pkg repos.


1.3.5
=====

Release Summary
---------------

Major Changes
-------------

Minor Changes
-------------
* Add pkgng options ignore_osver and pkgsite.
* Add ansible_facts.* debug.yml
* Move .ansible-lint.local to .ansible-lint
* Update README.md


1.3.4
=====

Release Summary
---------------
Get rid of Ansible Galaxy ansible-lint warnings.

Major Changes
-------------

Minor Changes
-------------
* syntax-check[unknown-module]; community.general.pkgng is included by default.
* schema[meta]; versions ['6.1', '7.1', '7.2', 'all'] is both obsolete and misleading.


1.3.3
=====

Release Summary
---------------
Move meta/requirements.yml to the role root directory.


1.3.2
=====

Release Summary
---------------
Put required collections in meta/requirements.yml


1.3.1
=====

Release Summary
---------------
Add files templating.

Major Changes
-------------

Minor Changes
-------------
* Add tasks/templates; Create files from templates.
* Fix tasks/pkg.yml; Install packages.
* Get activated pool by iocage get -p


1.3.0
=====

Release Summary
---------------
Ansible 2.21 upgrade.

Major Changes
-------------
* Supported FreeBSD 14.4, 15.0, and 15.1

Minor Changes
-------------


1.2.0
=====

Release Summary
---------------
Use command module instead of iocage module.

Major Changes
-------------

Minor Changes
-------------
* Use command module instead of iocage module.


1.1.0
=====

Release Summary
---------------
Add tasks to copy files.

Major Changes
-------------

Minor Changes
-------------
* Add tasks to copy files.
* Update tasks names.
* Update README.


1.0.0
=====

Release Summary
---------------
Production release.

Major Changes
-------------

Minor Changes
-------------
