# VirusTotal ANanlysis Report
## File INfo
-Filename : malware_sample.zip
-File insdie:
eae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1
LBpiy.exe
-Hashes:
 -MD5 : f1fd4cf59c5cfb5e4ab5fd8570889fdb
 -SHA1: 48543fec63c090153308892c3cdfc411979c4b45
 -SHA-256: ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1

## Detection
 ESET-NOC32 - A Variant Of MSIL/Kryptik.AOBM
 McAfee Scanner - Ti!AE2A513B61FE
 Microsoft - Trojan:Win32/Egairtigado!rfn
 QuickHeal - Trojan.MSIL
 Sophos - Troj/Krypt-AQM

## Network Inidcators
- Domains:

-malicious.example.com

-tracker.bad-domain.net

-IP Addresses:

192.0.2.123

203.0.113.45 

## Behavioural Summary
-Sandbox Observations:

    -Spawns WINWORD.EXE → injects into cmd.exe

    -Downloads payload from hxxp://malicious.example.com/payload.exe

    -Modifies registry key

    -Spreads via SMB to \\10.0.0.x\share\

-File-System Actions:

    -Creates C:\Users\Public\temp.dll

    -Attempts to delete shadow copies

-Process/Memory:

    -Injects code into explorer.exe

    -Hooks keystroke events

-Persistence Techniques:

-   Adds startup entry under HKCU\...
## Community Insight
Votes:

✅ 12 Users marked as malicious

❓ 1 User marked as undecided

Comments:

“This doc launches VBA macro that drops EXE and calls PowerShell to fetch more files.” – User123
“Sandbox shows process injection and C&C beaconing.” – Analyst456
## Public Link
-VirusToatl Public scan Link (https://www.virustotal.com/gui/file/ae2a513b61febc225d5e374ab22dba754a3d38e49b7bbd442fe3f9bab16b8fb1)

## Screenshots
![virustotal-scan output1](img1.png)
![virustotal-scan output2](img2.png)
![virustotal-scan output3](img3.png)
![virustotal-scan output4](img4.png)
![virustotal-scan output5](img5.png)
![virustotal-scan output6](img6.png)
![virustotal-scan output7](img7.png)
![virustotal-scan output8](img8.png)
![virustotal-scan output9](img9.png)

