# ScanXplorer
`ScanXplorer` is a powerful automation tool designed to detect vulnerabilities such as XSS (Cross-Site Scripting), SQLi (SQL Injection), SSRF (Server-Side Request Forgery), Open-Redirect, and more in web applications.`ScanXplorer` combines these tools to automate the process of subdomain discovery, port scanning, and spidering to identify vulnerable URLs and parameters. Fuzzing templates are then applied to test these URLs and parameters, aiming to detect potential vulnerabilities.

By using `ScanXplorer`, security researchers or penetration testers can efficiently execute a series of essential steps in automatically identifying vulnerabilities in web applications. This speeds up the security testing process and minimizes manual efforts required.

## Usage

```sh
./scanXplorer -h
```

This will display help for the tool. Here are the options it supports.


```console
scanXplorer is a Powerful Automation tool for detecting XSS, SQLi, SSRF, Open-Redirect, etc. vulnerabilities in Web Applications
Usage: ./NucleiFuzzer.sh [options]

Options:
  -h, --help              Display help information
  -d, --domain <domain>   Domain to scan for xss,sqli,ssrf,open-redirect..etc vulnerabilities
```  

Made by
`Suredsi Ulpada` | `cyberdesu` \
A `Security Researcher` and `Bug Hunter` \
