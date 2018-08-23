.. image:: https://img.shields.io/badge/license-LGPL--3-blue.png
   :target: https://www.gnu.org/licenses/lgpl
   :alt: License: LGPL-3

=============================
 Email Addresses per Website
=============================

Mail-related stuff for multi-website support

* Makes ``res.users``'s ``email`` field website-dependent
* Makes ``mail.template``'s ``body_html`` field website-dependent
* Overrides ``mail.template``'s ``render_template`` method to add ``website``
  variable. It may cause incompatibility with other modules that redefine that
  method too.

Credits
=======

Contributors
------------
* `Ivan Yelizariev <https://it-projects.info/team/yelizariev>`__

Sponsors
--------
* `e-thos SSII <http://www.e-thos.fr/>`__

Maintainers
-----------
* `IT-Projects LLC <https://it-projects.info>`__

      To get a guaranteed support
      you are kindly requested to purchase the module
      at `odoo apps store <https://apps.odoo.com/apps/modules/11.0/mail_multi_website/>`__.

      Thank you for understanding!

      `IT-Projects Team <https://www.it-projects.info/team>`__

Further information
===================

Demo: http://runbot.it-projects.info/demo/mail-addons/11.0

HTML Description: https://apps.odoo.com/apps/modules/11.0/mail_multi_website/

Usage instructions: `<doc/index.rst>`_

Changelog: `<doc/changelog.rst>`_

Notifications on updates: `via Atom <https://github.com/it-projects-llc/mail-addons/commits/11.0/mail_multi_website.atom>`_, `by Email <https://blogtrottr.com/?subscribe=https://github.com/it-projects-llc/mail-addons/commits/11.0/mail_multi_website.atom>`_

Tested on Odoo 11.0 4d0a1330e05bd688265bea14df4ad12838f9f2d7
