# open-mantis-issue
Open Mantis issue from CLI

```
./open-mantis-issue --help
usage: open-mantis-issue [-h] --summary SUMMARY --description DESCRIPTION --project-id PROJECT_ID [--configuration-file CONFIGURATION_FILE]

Opens Mantis issues

optional arguments:
  -h, --help            show this help message and exit
  --summary SUMMARY     Issue summary
  --description DESCRIPTION
                        Issue description
  --project-id PROJECT_ID
                        Project ID
  --configuration-file CONFIGURATION_FILE
                        INI file containing Mantis parameters
```

Mantis INI configuration file must look like:

```
[Mantis]
wsdl = http://MANTIS_URL/api/soap/mantisconnect.php?wsdl
username = my_user
password = my_password
```
# Installation

```
apt-get install python-soappy
```
