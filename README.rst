Nagios OpsGenie
===============
-----------------------------------------------------------
A non-Java based basic integration into OpsGenie for Nagios
-----------------------------------------------------------

:Author:    agrimberg@linuxfoundation.org
:Date:      2013-12-04
:Copyright: Andrew Grimberg and contributors
:License:   GPLv2
:Version:   0.1.0

DESCRIPTION
-----------
The reason for writing this is that we try to minimize the number of
components installed on our monitoring system. We're also not
particularly happy about using Java to communicate out for paging
services ;)

This should be a fairly close (though stripped down) rendering of the
ogCreateAlert.groovy script that ships with the OpsGenies nagios
integration kit.

REQUIREMENTS
------------
1. JSON_ used for data transport encodint to/from OpsGenie

.. _JSON: http://search.cpan.org/~makamaka/JSON-2.90/lib/JSON.pm

AUTHORS
-------
  * Andrew Grimberg <agrimberg@linuxfoundation.org>

SUPPORT
-------
Please open an issue on GitHub: https://github.com/tykeal/nagios_opsgenie/issues
