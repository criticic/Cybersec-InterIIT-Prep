# InterIIT Cybersecurity Prepathon 2024

## Part A: Development of POCs for given CVEs

Videos for the POCs can be found here: [video](https://iitbhuacin-my.sharepoint.com/:f:/g/personal/sagnik_mandal_mst23_iitbhu_ac_in/Ei3ukgBD7pFOnksAKsq8cPYBTp0D7CjItgQPnVN9ytPFpw?e=8SxWNM)

### 1. CVE-2024-32113 (100 points)

Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') vulnerability in Apache OFBiz.This issue affects Apache OFBiz: before 18.12.13. Users are recommended to upgrade to version 18.12.13, which fixes the issue.

POC: [exploit.md](CVE-2024-32113/POC/exploit.md)

### 2. CVE-2020-7245 (100 points)

Incorrect username validation in the registration process of CTFd v2.0.0 - v2.2.2 allows an attacker to take over an arbitrary account if the username is known and emails are enabled on the CTFd instance. To exploit the vulnerability, one must register with a username identical to the victim's username, but with white space inserted before and/or after the username. This will register the account with the same username as the victim. After initiating a password reset for the new account, CTFd will reset the victim's account password due to the username collision.

POC: [exploit.md](CVE-2020-7245/POC/exploit.md)

### 3. CVE-2019-0217 (100 points)

In Apache HTTP Server 2.4 release 2.4.38 and prior, a race condition in mod_auth_digest when running in a threaded server could allow a user with valid credentials to authenticate using another username, bypassing configured access control restrictions.

POC: [exploit.md](CVE-2019-0217/POC/exploit.md)

### 4. CVE-2016-3841 (100 points)

The IPv6 stack in the Linux kernel before 4.3.3 mishandles options data, which allows local users to gain privileges or cause a denial of service (use-after-free and system crash) via a crafted sendmsg system call.

POC: TODO

### 5. CVE-2020-9484 (100 points)

When using Apache Tomcat versions 10.0.0-M1 to 10.0.0-M4, 9.0.0.M1 to 9.0.34, 8.5.0 to 8.5.54 and 7.0.0 to 7.0.103 if (a) an attacker is able to control the contents and name of a file on the server; and (b) the server is configured to use the PersistenceManager with a FileStore; and (c) the PersistenceManager is configured with sessionAttributeValueClassNameFilter="null" (the default unless a SecurityManager is used) or a sufficiently lax filter to allow the attacker provided object to be deserialized; and (d) the attacker knows the relative file path from the storage location used by FileStore to the file the attacker has control over; then, using a specifically crafted request, the attacker will be able to trigger remote code execution via deserialization of the file under their control. Note that all of conditions (a) to (d) must be true for the attack to succeed.

POC: [exploit.md](CVE-2020-9484/POC/exploit.md)

## Part B: Automating Cyber Security Auditing (200 points)

Design and architect a system to automate the task of cybersecurity auditing. Explicitly state the technical requirements for your model. Prepare a report and presentation for the same.

Report: TODO
Presentation: TODO
