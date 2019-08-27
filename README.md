# check_certexp

```bash
$ sh get_check_certexp
```

## Installation

Replace the path for utils.pm with the path to the nagios plugins.

```bash
$ sed -i.bak 's#/usr/local/nagios/libexec#/usr/lib/nagios/plugins#' check_certexp.pl
```

Install required Perl packages.
```bash
$ apt-get install libdate-manip-perl libnet-ssleay-perl libnagios-plugin-perl
```
