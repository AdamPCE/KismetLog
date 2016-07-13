usage: klv.py [-h] [-o {html,csv}]
              [-s {essid,security,bssid,manufacturer,clients,packets}]
              [-g {yes,no}] [-t {beacon,request,response}]
              LogFilePath

Kismet Log Viewer v2.01 creates a readable summary of Kismet .netxml log
files.

positional arguments:
  LogFilePath           A directory containing one or more Kismet .netxml log
                        files. KLV will process all .netxml files in the
                        directory but will ignore all other files.

optional arguments:
  -h, --help            show this help message and exit
  -o {html,csv}         Output format (default: html)
  -s {essid,security,bssid,manufacturer,clients,packets}
                        Sort output (default: essid) (***unfinished***)
  -g {yes,no}           Group by essid (default: no) (***unfinished***)
  -t {beacon,request,response}
                        Show network types (default: beacon only)
                        (***unfinished***)
