1. To check the HTTP request and response in a browser, you need to use the built-in Developer Tools (DevTools) available in most modern browsers. Here’s how you can do it:
 
 Steps in Chrome (similar process for Firefox, Edge, Opera)
 
 Open DevTools

Press F12 or Ctrl + Shift + I (Windows/Linux) or Cmd + Option + I (Mac) to open DevTools.

Go to the Network Tab

Click the “Network” tab in DevTools.

Reload the page (press F5) to start capturing network activity.

View Requests

As the page loads, you will see a list of requests made by the browser.

Each row represents a resource requested (HTML, JS, images, API calls, etc.).

Inspect Individual Requests

Click on any resource to see more details.

Headers tab: View request and response headers (method, cookies, content type, status, etc.).

Response tab: See the content actually returned by the server (HTML, JSON, etc.).

Preview tab: For easily readable rendering of JSON, images, or HTML.

Timing tab: Shows how long each step of the request took.

Initiator tab: What caused the request.


2. Here’s how to check your DNS server and IP address:

On Windows
Check IP Address

Open Command Prompt (Win + R, type cmd, then Enter).

Type: ipconfig

Look for “IPv4 Address” under your active network adapter.

Check DNS Server

In Command Prompt, type: ipconfig /all

Find the “DNS Servers” line under your network adapter. This shows your DNS server IPs.

Quick DNS Lookup

Type: nslookup google.com

In the result, “Server” and “Address” will show your active DNS server.

On Mac
Check IP Address

Open Terminal (Cmd + Space, type “terminal” and Enter).

Type: ifconfig

Find “inet” under your active adapter for your IP.

Check DNS Server

In Terminal, type: nslookup google.com

The “Server” and “Address” lines show your DNS server.


3. To change your machine’s DNS (Domain Name System) settings, follow these steps depending on your operating system:

Windows 10/11
Open Control Panel:

Search “Control Panel” from the Start Menu and open it.

Network and Sharing Center:

Go to “Network and Internet” > “Network and Sharing Center”.

Change Adapter Settings:

Click on “Change adapter settings” on the left side.

Select Your Connection:

Right-click your active connection (Wi-Fi or Ethernet) and select “Properties”.

Edit IPv4/IPv6:

Select “Internet Protocol Version 4 (TCP/IPv4)” and click “Properties”.

Set DNS Server:

Click “Use the following DNS server addresses”.

Enter your preferred DNS (e.g., Google DNS: 8.8.8.8, 8.8.4.4; Cloudflare DNS: 1.1.1.1, 1.0.0.1).

Click “OK” and close all windows.

Restart Your Computer:

A restart ensures the settings take effect.

macOS
Open System Preferences:

Click the Apple menu > “System Preferences” > “Network”.

Choose Connection:

Select your active connection on the left, then click “Advanced”.

Go to DNS Tab:

Click the “DNS” tab.

Add DNS Servers:

Click the “+” sign and add new DNS IP addresses.

Save Settings:

Click “OK” and “Apply”.



 4.Here are 5 free DNS service providers you can use:

Google Public DNS

IPs: 8.8.8.8 and 8.8.4.4

Fast, reliable, widely used, and simple to set up.

Cloudflare DNS

IPs: 1.1.1.1 and 1.0.0.1

Known for speed, privacy, DDoS protection, and free SSL support.

OpenDNS (Cisco)

IPs: 208.67.222.222 and 208.67.220.220

Offers configurable content filtering and anti-phishing protection, popular for families and businesses.

Quad9 DNS

IPs: 9.9.9.9 and 149.112.112.112

Focuses on security by blocking malicious domains, fast and free.

FreeDNS (Afraid.org)

Provides free DNS management with unlimited domains and subdomains, good for personal or hobby projects.

These providers balance speed, security, and privacy, making them great options for everyday or advanced DNS needs.




By following these steps, you can view and analyze all HTTP requests and responses made by your browser as you interact with a website.

