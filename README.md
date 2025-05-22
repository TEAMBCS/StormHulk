╔════════════════════════════════════════════════════╗
║                 𝑺𝒕𝒐𝒓𝒎𝒉𝒖𝒍𝒌 - ADVANCED VERSION         ║
║                 [ BY PARVEZ | BCS TEAM ]          ║
║            HIGH-POWER HTTP LOAD TOOL (GoLang)     ║
╚════════════════════════════════════════════════════╝

──────────────────────────────────────────────────────
> Name       : StormHULK - Advanced Version  
> Author     : Bangladesh Cyber Squad {Parvez Hasan}  
> Language   : Golang  
> Platform   : Linux / Termux / Android / Kali / Windows (WSL)  
> Category   : Stress Testing / Load Generation  
──────────────────────────────────────────────────────

▶️ DESCRIPTION:

StormHULK (HTTP Unbearable Load King) - Advanced Version is a powerful and optimized HTTP flood & stress testing tool. It simulates real-world traffic using advanced techniques:

✔ Multi-threaded attack engine  
✔ Proxy and SOCKS5 support  
✔ Randomized User-Agents and Referers  
✔ Cache bypass and cookie injection  
✔ Detailed verbose output  
✔ CLI-flag based full control  

Use it for **stress testing your own servers**, simulating traffic to identify bottlenecks.

──────────────────────────────────────────────────────
▶️ USAGE EXAMPLES:

Command 1 (Standard Attack)
----------------------------
./hulk -targets targets.txt -workers 1000 -duration 150 \
-rate 50000 -random-agents -random-referers \
-bypass-cache -cookies -verbose

Command 2 (Advanced Proxy-Based GET Attack)
--------------------------------------------
./hulk -targets targets.txt -workers 2000 -duration 300 \
-rate 100000 -random-agents -random-referers \
-bypass-cache -cookies -method GET -proxy proxy.txt -verbose

──────────────────────────────────────────────────────
▶️ OPTIONS EXPLAINED:

  -targets         → Path to file containing target URLs  
  -workers         → Number of concurrent worker threads  
  -duration        → Attack duration in seconds  
  -rate            → Requests per second per worker  
  -random-agents   → Enables random User-Agent headers  
  -random-referers → Enables random Referer headers  
  -bypass-cache    → Appends cache-bypass parameters  
  -cookies         → Random cookie header injection  
  -method          → HTTP Method (GET/POST etc.)  
  -proxy           → Load proxy list from file  
  -verbose         → Enables detailed logging  

──────────────────────────────────────────────────────
▶️ EXAMPLES:

targets.txt
-----------
https://example.com  
http://testsite.org/page  

proxy.txt
----------
http://123.45.67.89:8080  
socks5://98.76.54.32:1080  

──────────────────────────────────────────────────────
⚠️ DISCLAIMER:

This tool is made **ONLY FOR EDUCATIONAL & AUTHORIZED TESTING PURPOSES**.

**Using this on unauthorized servers is ILLEGAL.**  
The developer is **not responsible** for any misuse or damage.

──────────────────────────────────────────────────────
> Developer: Parvez Hasan  
> Team     : Bangladesh Cyber Squad (BCS)   
──────────────────────────────────────────────────────

      THANK YOU FOR USING STORMHULK ADVANCED TOOL!
