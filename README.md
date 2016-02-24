# Cloudflare-Add-Uptimerobot

A simple script that fetches all of [uptimerobot](https://uptimerobot.com)'s ip addresses from [here](https://uptimerobot.com/inc/files/ips/IPv4andIPv6.txt)  and adds them to your [CloudFlare](https://cloudflare.com) firewall.  

This script requires python 2.7 or python 3.3+, and requests. Requests can be installed using pip:

    pip install requests

You will be promted to enter your email and API secret when running the script:

    python main.py
    > Email: email  
    > API-Secret: secret
