# Shodan Dorks [![](https://dcbadge.vercel.app/api/shield/476415736466636810?compact=true)](https://discordapp.com/users/476415736466636810)

<p align="center">
  <img src="https://github.com/dootss/shodan-dorks/assets/126783585/94f89cca-c51c-425f-972b-4e06f537102d" /><br />
  <strong><a href="https://account.shodan.io/register">Most search filters require a Shodan account.</a></strong>
</p>

### *What makes this different from other dork/query lists?*

This has tons of titles, info and categorisation that a lot of other mass-lists don't have.

Also, every six hours, it re-checks every query on here and updates their count. It also removes dorks that have 0 results.

### **Contents**

- [Cameras](#cameras)
- [Industrial Control Systems](#industrial-control-systems)
- [Network Infastructure](#network-infastructure)
- [Printers](#printers)
- [Files and Directories](#files-and-directories)
- [Compromised devices and websites](#compromised-devices-and-websites)
- [Miscellaneous](#miscellaneous)

---

<a name='cameras'></a>

### Cameras

[General camera search](https://www.shodan.io/search?query=camera)  
`camera` - 3,493,195 results

[Hikvision IP Cameras](https://www.shodan.io/search?query=product%3A%22Hikvision%20IP%20Camera%22)  
`product:"Hikvision IP Camera"` - 2,532,468 results
<br>
Backdoor exploit at https://ipvm.com/reports/hik-exploit

[Webcams running on IPCam Client](https://www.shodan.io/search?query=title%3A%22IPCam%20Client%22)  
`title:"IPCam Client"` - 55,952 results

[Older webcams running on GeoVision](https://www.shodan.io/search?query=server%3A%20GeoHttpServer)  
`server: GeoHttpServer` - 34,876 results

[Vivotek IP cameras](https://www.shodan.io/search?query=server%3A%20VVTK-HTTP-Server)  
`server: VVTK-HTTP-Server` - 20,643 results

[Avigilion-brand camera/monitoring devices](https://www.shodan.io/search?query=title%3A%22Avigilon%22)  
`title:"Avigilon"` - 17,583 results

[DVR CCTV cameras accessible via HTTP](https://www.shodan.io/search?query=200%20ok%20dvr%20port%3A%2281%22)  
`200 ok dvr port:"81"` - 6,551 results

[Netwave-make IP cameras](https://www.shodan.io/search?query=Netwave%20IP%20Camera%20Content-Length%3A%202574)  
`Netwave IP Camera Content-Length: 2574` - 2,548 results

[A UK-based IP camera provider](https://www.shodan.io/search?query=WWW-Authenticate%3A%20%22Merit%20LILIN%20Ent.%20Co.%2C%20Ltd%22)  
`WWW-Authenticate: "Merit LILIN Ent. Co., Ltd"` - 1,440 results

[Various IP camera/video management system products](https://www.shodan.io/search?query=ACTi)  
`ACTi` - 1,414 results

[UI3 - the HTML5 web interface for Blue Iris](https://www.shodan.io/search?query=title%3A%22ui3%20-%22)  
`title:"ui3 -"` - 928 results

[Yet another WebCAM software](https://www.shodan.io/search?query=product%3A%22Yawcam%20webcam%20viewer%20httpd%22)  
`product:"Yawcam webcam viewer httpd"` - 426 results

[Unsecured Linksys webcams](https://www.shodan.io/search?query=title%3A%22%2Btm01%2B%22)  
`title:"+tm01+"` - 301 results
<br>
<img src="images/Unsecured Linksys webcams.png" alt="Unsecured Linksys webcams Screenshot" width="400">

[ContaCam Cameras](https://www.shodan.io/search?query=title%3A%22ContaCam%22)  
`title:"ContaCam"` - 184 results

[Webcams running on webcamXP](https://www.shodan.io/search?query=server%3A%20webcamxp)  
`server: webcamxp` - 142 results
<br>
<img src="images/Webcams running on webcamXP.png" alt="Webcams running on webcamXP Screenshot" width="400">

[Webcams with screenshots](https://www.shodan.io/search?query=webcam%20has_screenshot%3Atrue)  
`webcam has_screenshot:true` - 107 results

[Webcams running on webcam 7](https://www.shodan.io/search?query=server%3A%20%22webcam%207%22)  
`server: "webcam 7"` - 87 results
<br>
<img src="images/Webcams running on webcam 7.png" alt="Webcams running on webcam 7 Screenshot" width="400">

[IP Webcams with screenshots](https://www.shodan.io/search?query=has_screenshot%3Atrue%20IP%20Webcam)  
`has_screenshot:true IP Webcam` - 44 results
<br>
<img src="images/IP Webcams with screenshots.png" alt="IP Webcams with screenshots Screenshot" width="400">

[Canon-manufactured megapixel security cameras](https://www.shodan.io/search?query=title%3A%22Network%20Camera%20VB-M600%22)  
`title:"Network Camera VB-M600"` - 41 results

[i-Catcher IP-based CCTV systems](https://www.shodan.io/search?query=server%3A%20%22i-Catcher%20Console%22)  
`server: "i-Catcher Console"` - 26 results

[Linksys WVC80N cameras](https://www.shodan.io/search?query=WVC80N)  
`WVC80N` - 21 results

[Webcams running on Blue Iris](https://www.shodan.io/search?query=title%3A%22blue%20iris%20remote%20view%22)  
`title:"blue iris remote view"` - 16 results


---

<a name='industrial-control-systems'></a>

### Industrial Control Systems

[EtherNet/IP](https://www.shodan.io/search?query=port%3A44818)  
`port:44818` - 877,175 results

[S7](https://www.shodan.io/search?query=port%3A102)  
`port:102` - 862,543 results

[BACnet](https://www.shodan.io/search?query=port%3A47808)  
`port:47808` - 831,989 results

[Modbus](https://www.shodan.io/search?query=port%3A502)  
`port:502` - 808,507 results

[Niagara Fox](https://www.shodan.io/search?query=port%3A1911%2C4911%20product%3ANiagara)  
`port:1911,4911 product:Niagara` - 8,104 results

[VNC Servers](https://www.shodan.io/search?query=%22authentication%20disabled%22%20%22RFB%20003.008%22)  
`"authentication disabled" "RFB 003.008"` - 5,784 results
<br>
While not always 100% guaranteed to be a system, lots of embedded systems can show up here, along with personal systems.

[Gas Station Pump Controllers](https://www.shodan.io/search?query=%22in-tank%20inventory%22%20port%3A10001)  
`"in-tank inventory" port:10001` - 5,118 results
<br>
Find gas station pump controllers with accessible inventory data.
<br>
<img src="images/Gas Station Pump Controllers.png" alt="Gas Station Pump Controllers Screenshot" width="400">

[Siemens Industrial Automation](https://www.shodan.io/search?query=%22Siemens%2C%20SIMATIC%22%20port%3A161)  
`"Siemens, SIMATIC" port:161` - 2,807 results

[IEC 60870-5-104](https://www.shodan.io/search?query=port%3A2404%20asdu%20address)  
`port:2404 asdu address` - 2,695 results

[More VNC Servers](https://www.shodan.io/search?query=%22authentication%20disabled%22%20port%3A5900%2C5901)  
`"authentication disabled" port:5900,5901` - 2,251 results
<br>
Another search term for VNC servers - most are on port 5900 or 5901 as these are VNC display ports.

[DICOM Medical X-Ray Machines](https://www.shodan.io/search?query=%22DICOM%20Server%20Response%22%20port%3A104)  
`"DICOM Server Response" port:104` - 2,214 results

[Omron FINS](https://www.shodan.io/search?query=port%3A9600%20response%20code)  
`port:9600 response code` - 1,648 results

[DNP3](https://www.shodan.io/search?query=port%3A20000%20source%20address)  
`port:20000 source address` - 1,400 results

[ProConOS](https://www.shodan.io/search?query=port%3A20547%20PLC)  
`port:20547 PLC` - 751 results

[PCWorx](https://www.shodan.io/search?query=port%3A1962%20PLC)  
`port:1962 PLC` - 726 results

[XZERES Wind Turbine](https://www.shodan.io/search?query=title%3A%22xzeres%20wind%22)  
`title:"xzeres wind"` - 297 results

[MELSEC-Q](https://www.shodan.io/search?query=port%3A5006%2C5007%20product%3Amitsubishi)  
`port:5006,5007 product:mitsubishi` - 206 results

[Door / Lock Access Controllers](https://www.shodan.io/search?query=%22HID%20VertX%22%20port%3A4070)  
`"HID VertX" port:4070` - 140 results

[C4 Max Commercial Vehicle GPS Trackers](https://www.shodan.io/search?query=%5B1m%5B35mWelcome%20on%20console)  
`[1m[35mWelcome on console` - 34 results
<br>
<img src="images/C4 Max Commercial Vehicle GPS Trackers.png" alt="C4 Max Commercial Vehicle GPS Trackers Screenshot" width="400">

[GaugeTech Electricity Meters](https://www.shodan.io/search?query=%22Server%3A%20EIG%20Embedded%20Web%20Server%22%20%22200%20Document%20follows%22)  
`"Server: EIG Embedded Web Server" "200 Document follows"` - 29 results
<br>
<img src="images/GaugeTech Electricity Meters.png" alt="GaugeTech Electricity Meters Screenshot" width="400">

[Open ATM](https://www.shodan.io/search?query=NCR%20Port%3A%22161%22)  
`NCR Port:"161"` - 23 results

[Nordex Wind Turbine Farms](https://www.shodan.io/search?query=http.title%3A%22Nordex%20Control%22%20%22Windows%202000%205.0%20x86%22%20%22Jetty/3.1%20%28JSP%201.1%3B%20Servlet%202.2%3B%20java%201.6.0_14%29%22)  
`http.title:"Nordex Control" "Windows 2000 5.0 x86" "Jetty/3.1 (JSP 1.1; Servlet 2.2; java 1.6.0_14)"` - 21 results

[Voting Machines in the United States](https://www.shodan.io/search?query=%22voter%20system%20serial%22%20country%3AUS)  
`"voter system serial" country:US` - 17 results

[Electric Vehicle Chargers](https://www.shodan.io/search?query=%22Server%3A%20gSOAP/2.8%22%20%22Content-Length%3A%20583%22)  
`"Server: gSOAP/2.8" "Content-Length: 583"` - 17 results

[Traffic Light Controllers / Red Light Cameras](https://www.shodan.io/search?query=mikrotik%20streetlight)  
`mikrotik streetlight` - 15 results

[HART-IP](https://www.shodan.io/search?query=port%3A5094%20hart-ip)  
`port:5094 hart-ip` - 7 results

[Fuel Pumps connected to internet](https://www.shodan.io/search?query=%22privileged%20command%22%20GET)  
`"privileged command" GET` - 6 results

[Siemens HVAC Controllers](https://www.shodan.io/search?query=%22Server%3A%20Microsoft-WinCE%22%20%22Content-Length%3A%2012581%22)  
`"Server: Microsoft-WinCE" "Content-Length: 12581"` - 6 results

[CAREL PlantVisor Refrigeration Units](https://www.shodan.io/search?query=%22Server%3A%20CarelDataServer%22%20%22200%20Document%20follows%22)  
`"Server: CarelDataServer" "200 Document follows"` - 5 results
<br>
<img src="images/CAREL PlantVisor Refrigeration Units.png" alt="CAREL PlantVisor Refrigeration Units Screenshot" width="400">

[Samsung Electronic Billboards](https://www.shodan.io/search?query=Server%3A%20Prismview%20Player)  
`Server: Prismview Player` - 3 results
<br>
Search for electronic billboards managed by Prismview servers.
<br>
<img src="images/Samsung Electronic Billboards.png" alt="Samsung Electronic Billboards Screenshot" width="400">

[Railroad Management](https://www.shodan.io/search?query=%22log%20off%22%20%22select%20the%20appropriate%22)  
`"log off" "select the appropriate"` - 2 results

[Automatic License Plate Readers](https://www.shodan.io/search?query=P372%20%22ANPR%20enabled%22)  
`P372 "ANPR enabled"` - 1 result

[Submarine Mission Control Dashboards](https://www.shodan.io/search?query=title%3A%22Slocum%20Fleet%20Mission%20Control%22)  
`title:"Slocum Fleet Mission Control"` - 1 result


---

<a name='network-infastructure'></a>

### Network Infastructure

[General MySQL Database Search](https://www.shodan.io/search?query=product%3AMySQL)  
`product:MySQL` - 2,961,164 results

[Remote PostgreSQL Connections](https://www.shodan.io/search?query=port%3A5432%20PostgreSQL)  
`port:5432 PostgreSQL` - 609,030 results

[Default MongoDB Instances](https://www.shodan.io/search?query=mongodb%20port%3A27017)  
`mongodb port:27017` - 73,187 results

[MongoDB Server Information on Default Port](https://www.shodan.io/search?query=%22MongoDB%20Server%20Information%22%20port%3A27017)  
`"MongoDB Server Information" port:27017` - 69,866 results

[Open Elasticsearch Databases](https://www.shodan.io/search?query=port%3A%229200%22%20all%3Aelastic)  
`port:"9200" all:elastic` - 21,321 results

[Cisco Smart Install](https://www.shodan.io/search?query=smart%20install%20client%20active)  
`smart install client active` - 6,385 results

[Listed Apache CouchDB](https://www.shodan.io/search?query=product%3A%22CouchDB%22)  
`product:"CouchDB"` - 4,736 results

[Pi-hole Open DNS Servers](https://www.shodan.io/search?query=%22dnsmasq-pi-hole%22%20%22Recursion%3A%20enabled%22)  
`"dnsmasq-pi-hole" "Recursion: enabled"` - 2,887 results

[Android Root Bridges](https://www.shodan.io/search?query=%22Android%20Debug%20Bridge%22%20%22Device%22%20port%3A5555)  
`"Android Debug Bridge" "Device" port:5555` - 2,531 results

[Polycom Video Conferencing](https://www.shodan.io/search?query=http.title%3A%22-%20Polycom%22%20%22Server%3A%20lighttpd%22)  
`http.title:"- Polycom" "Server: lighttpd"` - 2,212 results

[Jenkins CI](https://www.shodan.io/search?query=%22X-Jenkins%22%20%22Set-Cookie%3A%20JSESSIONID%22%20http.title%3A%22Dashboard%22)  
`"X-Jenkins" "Set-Cookie: JSESSIONID" http.title:"Dashboard"` - 1,536 results

[Lantronix Serial-to-Ethernet Adapter Leaking Telnet Passwords](https://www.shodan.io/search?query=Lantronix%20password%20port%3A30718%20-secured)  
`Lantronix password port:30718 -secured` - 500 results

[Already Logged-In as root via Telnet](https://www.shodan.io/search?query=%22root%40%22%20port%3A23%20-login%20-password%20-name%20-Session)  
`"root@" port:23 -login -password -name -Session` - 389 results

[Accessible Kibana Dashboards](https://www.shodan.io/search?query=kibana%20content-length%3A217)  
`kibana content-length:217` - 277 results

[Exposed MongoDB Express Web Interfaces](https://www.shodan.io/search?query=%22Set-Cookie%3A%20mongo-express%3D%22%20%22200%20OK%22)  
`"Set-Cookie: mongo-express=" "200 OK"` - 266 results

[Docker Private Registries](https://www.shodan.io/search?query=%22Docker-Distribution-Api-Version%3A%20registry%22%20%22200%20OK%22%20-gitlab)  
`"Docker-Distribution-Api-Version: registry" "200 OK" -gitlab` - 214 results

[Citrix Virtual Apps](https://www.shodan.io/search?query=%22Citrix%20Applications%3A%22%20port%3A1604)  
`"Citrix Applications:" port:1604` - 155 results

[PBX IP Phone Gateways](https://www.shodan.io/search?query=PBX%20%22gateway%20console%22%20-password%20port%3A23)  
`PBX "gateway console" -password port:23` - 140 results

[Telnet Configuration](https://www.shodan.io/search?query=%22Polycom%20Command%20Shell%22%20-failed%20port%3A23)  
`"Polycom Command Shell" -failed port:23` - 24 results

[Weave Scope Dashboards](https://www.shodan.io/search?query=title%3A%22Weave%20Scope%22%20http.favicon.hash%3A567176827)  
`title:"Weave Scope" http.favicon.hash:567176827` - 10 results

[Vulnerable CouchDB Instances](https://www.shodan.io/search?query=port%3A%225984%22%2BServer%3A%20%22CouchDB/2.1.0%22)  
`port:"5984"+Server: "CouchDB/2.1.0"` - 1 result


---

<a name='printers'></a>

### Printers

[General Printer Search](https://www.shodan.io/search?query=printer)  
`printer` - 95,430 results

[HP Printers Remote Restart](https://www.shodan.io/search?query=port%3A161%20hp)  
`port:161 hp` - 8,954 results

[Canon Printer HTTP Servers](https://www.shodan.io/search?query=Server%3A%20CANON%20HTTP%20Server)  
`Server: CANON HTTP Server` - 6,707 results

[HTTP Accessible Epson Printers](https://www.shodan.io/search?query=http%20200%20server%20epson%20-upnp)  
`http 200 server epson -upnp` - 1,465 results
<br>
<img src="images/HTTP Accessible Epson Printers.png" alt="HTTP Accessible Epson Printers Screenshot" width="400">

[Samsung Printers with SyncThru Web Service](https://www.shodan.io/search?query=title%3A%22syncthru%20web%20service%22)  
`title:"syncthru web service"` - 1,165 results

[Unsecured Telnet Access to Printers](https://www.shodan.io/search?query=port%3A23%20%22Password%20is%20not%20set%22)  
`port:23 "Password is not set"` - 322 results

[Epson Printers via HTTP Server](https://www.shodan.io/search?query=%22Server%3A%20EPSON-HTTP%22%20%22200%20OK%22)  
`"Server: EPSON-HTTP" "200 OK"` - 260 results

[Remote Access to Xerox Printers](https://www.shodan.io/search?query=ssl%3A%22Xerox%20Generic%20Root%22)  
`ssl:"Xerox Generic Root"` - 213 results
<br>
<img src="images/Remote Access to Xerox Printers.png" alt="Remote Access to Xerox Printers Screenshot" width="400">

[Lexmark Printer Control Panels](https://www.shodan.io/search?query=Printer%20Type%3A%20Lexmark)  
`Printer Type: Lexmark` - 140 results

[HP LaserJet Printers via HTTP](https://www.shodan.io/search?query=%22HP-ChaiSOE%22%20port%3A%2280%22)  
`"HP-ChaiSOE" port:"80"` - 63 results

[Brother Printers Admin Interface](https://www.shodan.io/search?query=%22Location%3A%20/main/main.html%22%20debut)  
`"Location: /main/main.html" debut` - 50 results

[Printers with FTP Access](https://www.shodan.io/search?query=Laser%20Printer%20FTP%20Server)  
`Laser Printer FTP Server` - 21 results

[Exposed OctoPrint 3D Printer Controllers](https://www.shodan.io/search?query=title%3A%22OctoPrint%22%20-title%3A%22Login%22%20http.favicon.hash%3A1307375944)  
`title:"OctoPrint" -title:"Login" http.favicon.hash:1307375944` - 17 results


---

<a name='files-and-directories'></a>

### Files and Directories

[Open Lists of Files and Directories](https://www.shodan.io/search?query=http.title%3A%22Index%20of%20/%22)  
`http.title:"Index of /"` - 284,839 results

[Filezilla FTP](https://www.shodan.io/search?query=filezilla%20port%3A%2221%22)  
`filezilla port:"21"` - 171,693 results

[Samba Shares with Authentication Disabled](https://www.shodan.io/search?query=%22Authentication%3A%20disabled%22%20port%3A445%20product%3A%22Samba%22)  
`"Authentication: disabled" port:445 product:"Samba"` - 119,183 results

[Open Lists on Port 80](https://www.shodan.io/search?query=port%3A80%20title%3A%22Index%20of%20/%22)  
`port:80 title:"Index of /"` - 100,155 results

[FTP Access Without Credentials](https://www.shodan.io/search?query=%22220%22%20%22230%20Login%20successful.%22%20port%3A21)  
`"220" "230 Login successful." port:21` - 41,371 results

[Anonymous Access Allowed FTP](https://www.shodan.io/search?query=%22Anonymous%20access%20allowed%22%20port%3A%2221%22)  
`"Anonymous access allowed" port:"21"` - 22,300 results

[NDMP on FTP Port 10000](https://www.shodan.io/search?query=ftp%20port%3A%2210000%22)  
`ftp port:"10000"` - 7,615 results

[Vulnerable vsftpd Service](https://www.shodan.io/search?query=vsftpd%202.3.4)  
`vsftpd 2.3.4` - 1,741 results

[QuickBooks Files Shared Over Network](https://www.shodan.io/search?query=%22QuickBooks%20files%20OverNetwork%22%20-unix%20port%3A445)  
`"QuickBooks files OverNetwork" -unix port:445` - 24 results


---

<a name='compromised-devices-and-websites'></a>

### Compromised devices and websites

[Compromised Legacy Systems on Port 4444](https://www.shodan.io/search?query=port%3A4444%20system32)  
`port:4444 system32` - 1,119 results

[General Hacked Label Search](https://www.shodan.io/search?query=hacked)  
`hacked` - 1,051 results

[Hacked By in HTTP Title](https://www.shodan.io/search?query=http.title%3A%22Hacked%20by%22)  
`http.title:"Hacked by"` - 422 results

[Compromised Routers Labeled HACKED-ROUTER](https://www.shodan.io/search?query=HACKED-ROUTER)  
`HACKED-ROUTER` - 401 results

[Compromised Routers](https://www.shodan.io/search?query=hacked-router-help-sos)  
`hacked-router-help-sos` - 384 results

[Variation of Hacked By Label Search](https://www.shodan.io/search?query=hacked%20by)  
`hacked by` - 252 results

[Ransomware Infected RDP Services](https://www.shodan.io/search?query=%22attention%22%20%22encrypted%22%20port%3A3389)  
`"attention" "encrypted" port:3389` - 48 results

[Compromised Hosts Advertising Default Password](https://www.shodan.io/search?query=HACKED-ROUTER-HELP-SOS-HAD-DEFAULT-PASSWORD)  
`HACKED-ROUTER-HELP-SOS-HAD-DEFAULT-PASSWORD` - 47 results

[Compromised FTP Servers](https://www.shodan.io/search?query=HACKED%20FTP%20server)  
`HACKED FTP server` - 24 results

[Bitcoin Ransomware with Screenshot](https://www.shodan.io/search?query=bitcoin%20has_screenshot%3Atrue)  
`bitcoin has_screenshot:true` - 7 results
<br>
<img src="images/Bitcoin Ransomware with Screenshot.png" alt="Bitcoin Ransomware with Screenshot Screenshot" width="400">

[Owned By Label in HTTP Title](https://www.shodan.io/search?query=http.title%3A%220wn3d%20by%22)  
`http.title:"0wn3d by"` - 6 results


---

<a name='miscellaneous'></a>

### Miscellaneous

[General Dashboard Interfaces](https://www.shodan.io/search?query=http.title%3A%22dashboard%22)  
`http.title:"dashboard"` - 375,282 results

[Control Panel Access Points](https://www.shodan.io/search?query=http.title%3A%22control%20panel%22)  
`http.title:"control panel"` - 65,226 results

[Minecraft Servers](https://www.shodan.io/search?query=%22Minecraft%20Server%22%20%22protocol%20340%22%20port%3A25565)  
`"Minecraft Server" "protocol 340" port:25565` - 4,735 results

[Bitcoin Antminer Miners](https://www.shodan.io/search?query=antminer)  
`antminer` - 1,720 results
<br>
These devices are often left with default credentials.

[Bomgar Help Desk Portals](https://www.shodan.io/search?query=%22Server%3A%20Bomgar%22%20%22200%20OK%22)  
`"Server: Bomgar" "200 OK"` - 358 results

[Tesla-related Interfaces](https://www.shodan.io/search?query=http.title%3A%22Tesla%22)  
`http.title:"Tesla"` - 354 results

[Everything in North Korea](https://www.shodan.io/search?query=net%3A175.45.176.0/22%2C210.52.109.0/24%2C77.94.35.0/24)  
`net:175.45.176.0/22,210.52.109.0/24,77.94.35.0/24` - 50 results

[EIG Electricity Meters](https://www.shodan.io/search?query=%22Server%3A%20EIG%20Embedded%20Web%20Server%22%20%22200%20Document%20follows%22)  
`"Server: EIG Embedded Web Server" "200 Document follows"` - 29 results

[Misconfigured WordPress Installations](https://www.shodan.io/search?query=http.html%3A%22%2A%20The%20wp-config.php%20creation%20script%20uses%20this%20file%22)  
`http.html:"* The wp-config.php creation script uses this file"` - 9 results

[Ethereum Miners](https://www.shodan.io/search?query=ETH%20-%20Total%20speed)  
`ETH - Total speed` - 3 results



---

*i'm not responsible for any misuse of this list :) explore responsibly!*

*last updated at: 2025-04-24 20:36:53*

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=dootss/shodan-dorks&type=Date&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=dootss/shodan-dorks&type=Date" />
  <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=dootss/shodan-dorks&type=Date" />
</picture>