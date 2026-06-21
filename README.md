DAY 1:

1.Find location (coordinates), restaurant name and exact location in street view map.

![](data:image/jpeg;base64...)

Steps:
 1. Use Yandex image search (Rus and Euro based results) and find exact or similar images.
 2. Take hints from visible shop names and search for it in the maps.

3.Use street view in maps and navigate to the exact location where the picture was taken.

1. Find info about a baseball game video from a zip file

Steps:

1. Play the video and take screenshot of a correct moment which could’ve made it on the internet.
2. Search the image using reverse image search either Yandex or google.
3. Gather info about the picture results.

3. Find exact location from a picture presented with captions and hint.

 Steps:

1. Gather hints from the picture like billboard and find an approximate location

2. Look up the event info and search for starting point of the event.

3. Look for the exact location using Google street view in the map.

DAY 2:

Pic2map – used to find location if a picture

Exiftool – linux

Jimpl.com – website for exif

Flightradar24 to find details about flights

Marinetraffic to gather details about ships

Social engineering:

1. Phishing

2. Vhishing

3. Spear phishing

4. qshing (QR)

GoPhish tool in kali to simulate phishing:

1. Create a sending phishing profile

2. landing point

3. email template

4. users & group

5. Start campaign to start attacking using phishing

Trae llm – just like claude. Can be very useful for creating tools and projects

Rubber ducky (no need that much coding) – Use own scripts on it (can be potentially final yr project

(ESP 32 circuit) – can build Bluetooth jammer, bruteforce attack and wifi cracker. this needs programming knowledge like c and c++

Hak5 – website to buy hacking devices (devices are banned in IN tho)

DAY 3:

Blue Room on Tryhackme; (includes nmap and metasploitable)

Nmap (Network Map)

Command to scan open ports:

1. Nmap -p 500-1000 target machine’s ip

2. Nmap -sn ip address ( for host discovery)

3. Nmap -iL targets.txt

4. nmap -PS -sn target ip (can mention port number after 22 to send the packets. If not mentioned, it sends to port number 80) – (-PU and -PA is used for UDP protocols)

5. nmap -sT target\_ip\_address

6. nmap -sU TARGET (send packets to all udp ports)

7. nmap -sL TARGET (scans for hosts which are about to be scanned by nmap without scanning them)

8. nmap -sn target (for scans only live targets without port scanning

9. nmap -sN target (sends null packets to the target)

10. nmap -sA (acknowledgement packet)

11. nmap -sF target (finish packet) (port is open if we don’t get any response)

12. nmap -sX Target (sends FIN, PSH, URG) (if no response the port is open)

13. nmap -PR Target (does ARP scan. Add -sn if port scanning isn’t needed)

14. nmap -S SPOOFED\_IP MACHINE\_IP (sends spoofed ip address)

15. nmap -PE Target (to send icmp echoe request to all hosts in the target network. It’ll be blocked by firewalls mostly cuz of built-in firewall in MS Windows)

ARP-SCAN, Fscan, Ping utility

Zenmap for window (similar to Nmap)

DAY 4:

Searchlight imint on tryhackme

Sakura room on TryHackme

Some to lookout for jobs:

Nmap command to search all the 6k+ ports quickly (enumeration) :

nmap -p- -sV -sC -0 -T5 ip\_address -oN result.txt

alternate for this long ahh command nmap -p- -A -T5 ip -oN result.txt

Day 5:

Enumeration using nmap commands

Kenobi room in tryhackme

SSH and bruteforcing in metasploitable vm

Day 6:

DNS records

Using dnsdumpster.com

Google dorking:

Use nasa.gov as example

1. site:nasa.gov gives only results with nasa.gov

2. site:nasa.gov intitle:home gives result with ‘home’ in title of the search result.

3. site:nasa.gov intext:username vies search result where desc(under the title) has the word “username”.

4. site:nasa filetype:pdf show results with pdf files.

5. site:nasa filetype:pdf inurl:mars.nasa,gov excludes the specific url metioned (mars.nasa.gov).

Use google dorking cheatsheet for all the dorking commands :

Github link: <https://gist.github.com/sundowndev/283efaddbcf896ab405488330d1bbc06>

6. Find exploits in EXPloit-db website

go to Google hacking database

Search for webam and select “intitle:"webcamXP" inurl:8080”

Search intitle:"webcamXP" inurl:8080” in google search and open the first link to see live webcam feed

7. Gathering most if the info (Dorking) : <https://3eye.vercel.app/>

8. Search web by domain : <https://searchdns.netcraft.com/>

9. HTTrack website can clone any website (both frontend and backend) : [https://httrack.com](https://httrack.com/). Can be installed in any system and takes too long to process

do <https://tryhackme.com/room/vulnversity> room
