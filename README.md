# Browser-Forensics-Investigation-Cryptominer-Incident
In this project, I conducted a browser-based forensic investigation following a SOC alert indicating suspicious crypto-mining traffic originating from a newly joined workstation on the network. The incident response team identified that the malicious traffic was being generated through browser applications, prompting a detailed forensic analysis.
------------------------
Using FTK Imager, I examined the provided .ad1 forensic image file containing collected browser artifacts. The objective was to identify indicators of compromise (IOCs), determine the source of the crypto-mining activity, and reconstruct user browser activity.
Tools & Techniques Used
•	FTK Imager – To mount and analyze the AD1 evidence file and extract relevant browser artifacts.
•	BrowserHistoryView – To parse and analyze browser history databases.
•	Manual forensic analysis of:
o	Browser history (URLs, visit frequency, timestamps)
o	Cache files
o	Cookies
o	Download history
o	Stored sessions and extensions
Key Investigation Steps
1.	Loaded and verified the integrity of the AD1 evidence file.
2.	Extracted browser artifacts from user profile directories.
3.	Analyzed browsing history to identify connections to known cryptomining domains and suspicious JavaScript-based mining platforms.
4.	Correlated timestamps with SOC alert logs.
5.	Identified potential malicious websites or browser extensions responsible for initiating mining activity.
6.	Documented indicators of compromise and provided remediation recommendations.
Outcome
The investigation confirmed that the crypto-mining traffic originated from a malicious or compromised website accessed via the browser. The analysis provided clear evidence of browser-based cryptojacking activity, including domain artifacts and timestamps aligned with network alerts.
Skills Demonstrated
•	Digital Forensics & Incident Response (DFIR)
•	Browser Artifact Analysis
•	Timeline Reconstruction
•	Evidence Handling & Preservation
•	IOC Identification
•	Report Writing & Documentation

