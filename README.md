# modsecurity

mod_security ruleset based on the Comodo Web Application Firewall and OWASP ModSecurity Core Rule Set (CRS) with modifications to prevent false positives.

This ruleset has also been stripped down in order to provide support for CentOS 5,6,7.

## Installation

### CentOS and CloudLinux 5,6,7
```
curl -sL https://raw.githubusercontent.com/sliqua-hosting/modsecurity/master/install/install.sh | bash
service httpd restart
```

## Credits

Copyright 2015 Sliqua Enterprise Hosting, Inc. (https://www.sliqua.com)

Copyright 2015 Comodo Security Solutions (http://waf.comodo.com)

Originally based on the OWASP Foundation's Core Rule Set (CRS)

Distributed under the Apache License, see LICENSE for more information.
