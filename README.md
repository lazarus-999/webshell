===== LAZARUS WEB SHELL SCANNER =====

.

🇮🇩 Bahasa Indonesia
Lazarus Webshell Scanner adalah alat keamanan portabel untuk menemukan file shell tersembunyi (webshell) pada server web. Dilengkapi dengan wordlist dari SecLists, fitur recursive fuzhing, dan dukungan proxy. Tersedia mode FREE (1 domain, 100 URL, ekstensi HTML saja) dan PREMIUM (tanpa batasan, semua fitur aktif). Cocok untuk bug bounty hunter dan security tester.

.

🇬🇧 English
Lazarus Webshell Scanner is a portable security tool designed to detect hidden webshell files on web servers. It includes wordlists from SecLists, recursive fuzzing, and proxy support. Available in FREE mode (1 domain, 100 URLs, HTML only) and PREMIUM mode (unlimited access, all features enabled). Ideal for bug bounty hunters and security testers.

.


1. Run the file: shell_scanner.exe

2. Free Features:

   a. Only scan 1 domain with 100 URLs/paths per scan.
   b. Default wordlist (SecLists) or load custom wordlist.
   c. Only single domain input allowed.
   d. Proxy options: None (default), Manual (enter proxy data), List (use multiple proxies from file).
   e. File extensions to scan: HTML only.
   f. Enable recursive fuzzing for deeper scanning into subdirectories – set max depth up to 5 levels (example: wp-content/images/uploads/...).

3. Premium Features: All available functions in Lazarus Webshell Scanner.


=========
NOTES:

- To add more wordlists for better results, follow these steps:

1. Method without Git:

   > Download the ZIP file using PowerShell (no Git required):
   Invoke-WebRequest -Uri "https://github.com/danielmiessler/SecLists/archive/refs/heads/master.zip" -OutFile "SecLists.zip"

   > Extract the ZIP file:
   Expand-Archive -Path "SecLists.zip" -DestinationPath "."

   > Delete the ZIP file (optional):
   Remove-Item "SecLists.zip"

=========

2. Using Git (recommended):

   > Open PowerShell or CMD as Administrator.

   > Run the git clone command (downloads only the latest content, faster):
   git clone --depth 1 https://github.com/danielmiessler/SecLists.git


=========
For information and license activation:
- https://github.com/lazarus-999
- https://t.me/lazarussignals
