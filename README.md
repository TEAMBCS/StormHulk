                                                                              
                                                                              
                                                                                                    
                                                                              

𝑺𝒕𝒐𝒓𝒎𝒉𝒖𝒍𝒌

       [ ADVANCED VERSION BY PARVEZ ]
        HIGH-POWER HTTP LOAD TOOL

======================================================
> Name       : stormHULK - Advanced Version
> Author     : Bangladesh cyber squad {Parvez hasan}
> Language   : Golang
> Platform   : Linux / Termux / Android / Kali / Windows (WSL)
> Category   : Stress Testing / Load Generation
======================================================

>> DESCRIPTION:

StormHULK (HTTP Unbearable Load King) - Advanced Version is a powerful and optimized HTTP flood tool designed for stress testing websites and servers. It uses multiple techniques like random user-agents, referers, proxy support, and cookie injection to bypass caching and amplify load.

This version includes:
- Multi-threading (custom worker counts)
- Proxy support
- Randomized headers (agents, referers)
- Enhanced control via CLI flags
- Bypass cache & cookie injection
- Verbose logging



Command 1 (Standard):
---------------------
./hulk -targets targets.txt -workers 1000 -duration 150 \
-rate 50000 -random-agents -random-referers -bypass-cache \
-cookies -verbose

Command 2 (Advanced with proxy & GET method):
---------------------------------------------
./hulk -targets targets.txt -workers 2000 -duration 300 \
-rate 100000 -random-agents -random-referers -bypass-cache \
-cookies -method GET -proxy proxy.txt -verbose

>> OPTIONS EXPLAINED:

-targets        : Path to file with list of target URLs
-workers        : Number of concurrent worker threads
-duration       : Attack duration in seconds
-rate           : Requests per second per worker
-random-agents  : Use random User-Agent headers
-random-referers: Use random Referer headers
-bypass-cache   : Add cache-bypassing parameters
-cookies        : Inject random cookies
-method         : HTTP method (default: GET)
-proxy          : Use proxies from file
-verbose        : Enable verbose output

>> EXAMPLES:

Example targets.txt:
---------------------
https://example.com
http://victim.site/page

Example proxy.txt:
---------------------
http://123.45.67.89:8080
socks5://98.76.54.32:1080

>> DISCLAIMER:

This tool is intended **ONLY FOR EDUCATIONAL & STRESS TESTING PURPOSES ON YOUR OWN SERVERS**.
Using it against any system without permission is **illegal**.

> Developer: Parvez
> team; (Bangladesh Cyber Squad)

======================================================
      THANK YOU FOR USING StormHULK ADVANCED TOOL!
======================================================
