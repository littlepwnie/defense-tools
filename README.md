# Defense Tools
A small collection of tools used for defensive actions, such as scanning for malware and IOC's.
## Yara_scanner
A simple malware scanner based on a given yara rules file. Works on python and has been tested
on linux machines.
Usage:
###
python yara_scanner.py -y <yara_rule_dst> [-s <scan_files_dir> (if not provided, current dir is scanned)]
###
