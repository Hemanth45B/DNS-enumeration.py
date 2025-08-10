# DNS-enumeration.py
A simple Python tool that uses dnspython to query and display various DNS records (A, AAAA, CNAME, MX, TXT, SOA) for a given domain.

##  Description
This tool allows you to query a domain's DNS records, which can be useful for network troubleshooting, security analysis, or information gathering. It's written in Python and uses the `dnspython` library to handle DNS queries.

##  Features

-   Fetches common DNS record types: `A`, `AAAA`, `CNAME`, `MX`, `TXT`, and `SOA`.
-   Easy to modify and extend with more record types.
-   Simple and clean output.

## Requirements

Before running the script, you need to have Python installed on your system. You will also need to install the `dnspython` library.

You can install the required library using pip:
```bash
pip install dnspython

 ##Customization
To change the target domain, simply edit the target_domain variable within the dns_enumuration_python_p1.1.py file

target_domain = 'your-desired-domain.com'
