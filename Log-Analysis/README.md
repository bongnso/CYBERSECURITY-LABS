The following images document key investigation stages:

1. *access 2 0.jpeg* – Initial access log entries  
2. *ACCESS 2 404.jpeg* – 404 errors indicating file probing  
3. *access 2 CONNECT.jpeg* – CONNECT method (potential proxy tunneling)  
4. *ACCESS 2 XMLRPC.jpeg* – XMLRPC exploit attempts  
5. *Dradis Report 1.jpeg* – Documenting findings  
6. *Dradis Report 2.jpeg* – Final structured incident report evidence  

 Summary of Findings
Analysis of the access logs revealed:

- Multiple *repeated requests from the same IP*, indicating brute-force or enumeration attempts  
- *404 errors* caused by probing for non-existent files  
- *XMLRPC exploitation attempts*, commonly used in WordPress attacks  
- Suspicious *CONNECT* method requests, often linked to tunneling or exploitation tools  
- Evidence compiled into a *formal Dradis incident report*  

Tools Used
- Linux command-line (grep, cat, less)  
- Log review using Apache access logs  
- Dradis Framework for documenting findings  
- Wireshark (for related network investigations)
