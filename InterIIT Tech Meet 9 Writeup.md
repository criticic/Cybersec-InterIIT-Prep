# InterIIT Tech Meet 9 Writeup

## Development of POCs for given CVEs

Videos for the solved POCs can be found here: [video](https://iitbhuacin-my.sharepoint.com/:f:/g/personal/sagnik_mandal_mst23_iitbhu_ac_in/Ei3ukgBD7pFOnksAKsq8cPYBTp0D7CjItgQPnVN9ytPFpw?e=8SxWNM)

### 1. CVE-2014-0226 (100 points)

Race condition in the mod_status module in the Apache HTTP Server before 2.4.10 allows remote attackers to cause a denial of service (heap-based buffer overflow), or possibly obtain sensitive credential information or execute arbitrary code, via a crafted request that triggers improper scoreboard handling within the status_handler function in modules/generators/mod_status.c and the lua_ap_scoreboard_worker function in modules/lua/lua_request.c.

POC & Setup Guide: TODO

### 2. CVE-2017-12615 (100 points)

When running Apache Tomcat 7.0.0 to 7.0.79 on Windows with HTTP PUTs enabled (e.g. via setting the readonly initialisation parameter of the Default to false) it was possible to upload a JSP file to the server via a specially crafted request. This JSP could then be requested and any code it contained would be executed by the server.

POC & Setup Guide: TODO

### 3. CVE-2020-0609 and CVE-2020-0610 (200 points)

A remote code execution vulnerability exists in Windows Remote Desktop Gateway (RD Gateway) when an unauthenticated attacker connects to the target system using RDP and sends specially crafted requests, aka 'Windows Remote Desktop Gateway (RD Gateway) Remote Code Execution Vulnerability'.

POC & Setup Guide: TODO

### 4. CVE-2018-1335 (100 points)

From Apache Tika versions 1.7 to 1.17, clients could send carefully crafted headers to tika-server that could be used to inject commands into the command line of the server running tika-server.

POC & Setup Guide: TODO

### 5. CVE-2019-0232 (100 points)

When running on Windows with enableCmdLineArguments enabled, the CGI Servlet in Apache Tomcat 9.0.0.M1 to 9.0.17, 8.5.0 to 8.5.39 and 7.0.0 to 7.0.93 is vulnerable to Remote Code Execution due to a bug in the way the JRE passes command line arguments to Windows. The CGI Servlet is disabled by default. The CGI option enableCmdLineArguments is disable by default in Tomcat 9.0.x (and will be disabled by default in all versions in response to this vulnerability).

POC & Setup Guide: TODO
