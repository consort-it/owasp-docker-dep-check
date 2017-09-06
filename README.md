# OWASP Dependency-Check

OWASP dependency-check is a software composition analysis utility that detects publicly disclosed vulnerabilities in application dependencies.

# Usage

In the following example it is assumed that the source to be checked is in the current working directory. Persistent data and report directories are used, allowing you to destroy the container after running.

```
PROJECT_NAME=foo owasp-check.sh
```
