---
layout: default
title: External Command Reference
---

<!--
************************************************
* AUTO GENERATED PAGE - USE ./update SCRIPT
************************************************
-->

<span class="glyphicon glyphicon-arrow-up"></span><a href="index.html"> External Commands Reference</a> - START_OBSESSING_OVER_SVC<br>


#### Command Format:

`START_OBSESSING_OVER_SVC;service`

#### Description:

Enables processing of service checks via the OCSP command for the specified service.

#### Shell Script Usage Example:

```sh
#!/bin/sh
# This is a sample shell script showing how you can submit the START_OBSESSING_OVER_SVC command
# to Naemon. Adjust variables to fit your environment as necessary.

printf "[%lu] START_OBSESSING_OVER_SVC;service1\n" `date +%s` > /var/lib/naemon/naemon.cmd
```



