# Project-BlackSheep
Project blacksheep is a project i started to study, share and mitigate the amount of current cyber attacks & tracking on the web, this repo is here as a resource to share knowledge about known bad ip addresses, active malware samples, and phishing/tracking domains. 
This includes:
- Bad ipv4 Addresses captured via ssh & telnet honeypot
- Bad ipv4 Addresses Captured via http honeypot(ip addresses of web attackers)
- Blocklists for active phishing sites and advertisement trackers, browser miners etc. overall just a list of crap to filter out the internet.
- Malware Samples captured via honeypot for further analysis (I am not held responsible for what ever happens to you or your servers/computers/network)
- Malformed Get and post requests and raw logs from an apache honeypot
- Common credits used for attacking servers
- User agent string Dictionary for Bots and Crawlers (check UAS)

#
I deployed the blocklists using pfblockerNG on pfsense 2.4.5-devel, You can use a alternative such as pi-hole however I do not support installs on pi-hole.
If you would like to report a false positive or a issue/feature please make a issue request and I will get back to you as soon as possible! 

"Arguing that you don't care about the right to privacy because you have nothing to hide is no different than saying you don't care about free speech because you have nothing to say." "When you say, 'I have nothing to hide,' you're saying, 'I don't care about this right." - Edward Snowden
