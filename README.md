Solid Mailbox
====================

By [@nsauter](https://github.com/nsauter) and [contributors](https://github.com/nsauter/solid-mailbox/graphs/contributors).

Solid Mailbox helps individuals take back control of their email by installing a solid mail server with only the very needed tools. But you can install a few cool additions if you wish to.

* * *

The goal of Solid Mailbox is to:

* Make deploying a good and simple mail server easy.
* Promote [decentralization](http://redecentralize.org/), innovation, and privacy on the web.
* Make a lightweight & secure but **not** completely unhackable server.

The Box
-------

Solid Mailbox turns a fresh Ubuntu or Debian machine into a working mail server by installing and configuring various components.

It is a one-click email appliance. There are only a few user-configurable setup options to make it very easy and lightweight. It "just works".

The components installed are:

* SMTP ([postfix](http://www.postfix.org/))
* IMAP ([dovecot](http://dovecot.org/))
* Spam filtering ([spamassassin](https://spamassassin.apache.org/))
* Greylisting ([postgrey](http://postgrey.schweikert.ch/))
* Firewall ([ufw](https://launchpad.net/ufw))
* Intrusion protection ([fail2ban](http://www.fail2ban.org/wiki/index.php/Main_Page))

And optional functions:

* ([apache](https://httpd.apache.org/)) Webserver with a Webmail ([Roundcube](http://roundcube.net/)) installation
* System monitoring ([monit](https://mmonit.com/monit/))

Secured by:

* ([LetsEncrypt](https://letsencrypt.org/de/about/))

For more information on how Solid Mailbox handles your privacy, see the [security details page](security.md).

Installation
------------

Clone this repository:

	$ git clone https://github.com/nsauter/solid-mailbox
	$ cd solid-mailbox

Begin the installation.

	$ sudo setup/install.sh


Contributing and Development
----------------------------

Solid Mailbox is an open source project. Your contributions and pull requests are welcome. 

