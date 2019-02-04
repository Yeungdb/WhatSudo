# WhatSudo

WhatSudo is a proof-of-concept priviledge escalation shell code that attempts to address the trust and over-reliance that Linux users have towards sudo. The shell code essentially assumes the position of sudo and can abstract user and superuser passwords without being suspicious to a user. Upon staging the WhatSudo as /usr/bin/sudo, WhatSudo will be run in place of the original sudo. 


