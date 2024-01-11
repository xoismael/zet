# Utilizing sqlmap with burpsuite

I believe a great way to maximize the efficiency of sqlmap is to just use it with burpsuite with the `--proxy` flag. Especially for time based sqli payloads, the ability to see the response time is very much great.

Also try to create our own payloads and give it to sqlmap. (Effective way)
Command to use to proxy the traffic of sqlmap:
  `sqlmap --proxy=http://127.0.0.1:8080`
  
  
:sqli:
