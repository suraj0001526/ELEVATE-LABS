Commands used:
nmap -sV 192.168.28.136 -oN detailed_scan.txt
nmap -sV 192.168.28.136 
sudo nmap -sS 192.168.28.136/24
ip a
sudo apt update && sudo apt install nmap -y


Security Analysis of the open ports:

🔸 Port 80 – HTTP

    Service: Apache Web Server

    Risk:

        HTTP is unencrypted.

        Could expose admin interfaces or outdated web apps.

        Check for default pages, directory listings, or misconfigurations.

    Recommendation:

        Use HTTPS (port 443) instead.

        Update Apache to latest secure version.

        Disable directory browsing if not needed.

🔸 Port 9200 – Elasticsearch API (over SSL)

    Service: Elasticsearch REST API (with Shield security plugin)

    Risk:

        If not authentication-protected, it can expose/search database content.

        Elasticsearch has had serious vulnerabilities (e.g., CVE-2015-1427, CVE-2019-7610).

    Recommendation:

        Restrict access to trusted IPs.

        Ensure Shield (or X-Pack) is enforcing authentication.

        Update to latest version.

        Disable unauthenticated external access.