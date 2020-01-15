

0rion 2.0
-----------------------------------------------------------------
0rion has been tested on and is intended for Kali linux
NO LONGER will the 0rion Framework 1.0 be maintained.
a settings menu for the interface can be found by simply clicking the settings file in the file manager once you start 0rion
modules reside in the orion directory
make sure all modules are marked executable

debpg
edith
quickpg
winpg
avet/a.sh
avet/b.sh
avet/c.sh
avet/d.sh
avet/e.sh
avet/f.sh
avet/g.sh
avet/h.sh
avet/i.sh
avet/j.sh
avet/k.sh
<blockquote class="imgur-embed-pub" lang="en" data-id="a/OAmjaJs"><a href="//imgur.com/a/OAmjaJs"></a></blockquote><script async src="//s.imgur.com/min/embed.js" charset="utf-8"></script>
0rion Framework 2.0 updates include:
                                    no longer runs on a lamp/stack,
                                    now uses a EDex-UI interface https://github.com/GitSquared/edex-ui 
                                    all payload generators have been updated
                                     


                                    windows payload generator now uses avet with custom build scripts,
                                    addition of metasploit "mass_exploiter" script https://github.com/r00t-3xp10it/resource_files 
                                    all recon modules have been combined into the "e.d.i.t.h" module. 
                                    the edith module is the soul 0rion module currently and is intended for blackbox testing.
                                    between a few Y/N statements here is a current list of what edith will prefom on a target.


                          Ask to start anonymous mode
                          1: nmap scan including shodan and vulscan nse scripts
                          2: nikto scan
                          3: web scan = siege
                                        whatweb
                                        sslyze
                                        lbd
                                        waf00f
                                        amap
                          4: uniscan
                          5: gather additional domain info = nmap scan wih nbstat script
                                                             xprobe2
                                                             dmitry
                                                             /cmd/bing-ip2hosts
                                                             /cmd/tekCollect.py
                          6: geolocation of target
                          7: theHarvester
                          8: preform reverse IP
                          9: metasploit auxiliary scan round 1: metasploit will open and run the following modules = 
                                                                clear the database of all hosts
                                                                import all xml files from the recon so far
                                                                tcp portscan
                                                                smb version
                                                                http version
                                                                ssl version
                                                                ftp version
                                                                mysql version
                                                                imap version
                                                                smtp version
                                                                telnet version
                                                                ssh version
                                                                finger users
                                                                db2 discovery
                                                                db2 version
                                                                energizer duo detect
                                                                chargen probe
                                                                couchdb enum
                                                                counchdb login
                                                                db2 auth
                                                                dcerpc endpoint mapper
                                                                dcerpc hidden
                                                                dcerpc management
                                                                tcp dcerpc auditor
                                                                windows deployment services
                                                                call scanner
                                                                station scanner
                                                                arp sweep
                                                                empty udp
                                                                udp probe
                                                                udp sweep
                                                                disw leak capture
                                                                indices enum
                                                                alphastor devicemanager
                                                                alphastor librarymanager
                                                                open key scanner
                                                                etcd version
                                                                ftp anonymous check
                                                                ftp bison traversal check
                                                                ftp colorado traversal check
                                                                ftp easy file share check
                                                                ftp konica traversal check
                                                                ftp pcman traversal check
                                                                ftp titan xcrc traversal check
                                                                gopher_gophermap
                                                                gtp echo
                                                                h323 version
                                                                accellion fta statecode file read
                                                                adobe xml inject
                                                                allegro rompager misfortune cookie
                                                                apache activemq source disclosure
                                                                activemq traversal check
                                                                apache optionsbleed
                                                                apache userdir enum
                                                                atlassian crowd fileaccess
                                                                barracuda directory traversal check
                                                                bitweaver overlay type traversal
                                                                blind sql query
                                                                bmc trackit passwd reset
                                                                http brute dirs
                                                                buildmaster login
                                                                caido bruteforce login
                                                                canon wireless
                                                                http cert 
                                                                cgit traversal
                                                                chef webui login
                                                                chromecast webserver
                                                                chromecast wifi
                                                                clansphere traversal check
                                                                cnpilot r web login root
                                                                coldfusion locale traversal
                                                                coldfusion version
                                                                concrete5 member list
                                                                http crawler
                                                                dell idrac
                                                                dicoogle traversal check
                                                                dir listing
                                                                dir scanner
                                                                dir webdav unicode bypass
                                                                dnalims file retrieve
                                                                docker version
                                                                dolibarr login
                                                                drupal views user enum
                                                                ektron cms400net
                                                                elasticsearch traversal check
                                                                epmp1000 dump config
                                                                epmp1000 dump hashes
                                                                epmp1000 reset pass
                                                                epmp1000 web login
                                                                error sql injection
                                                                es file explorer open port
                                                                list hosts, services, loot, creds, vulns

                           10: (keep going?) metasploit auxiliary scan round 2: metasploit will open and run the following modules =
                                                                                f5 bigIP virtual server,
                                                                                f5 mgmt scanner
                                                                                file same name dir
                                                                                http files dir
                                                                                frontpage credential dump
                                                                                git scanner
                                                                                gitlab login
                                                                                gitlab user enum
                                                                                glassfish traversal check
                                                                                goahead traversal check
                                                                                groupwise agents http traversal check
                                                                                host header injection
                                                                                hp imc downloadservlet traversal check
                                                                                hp imc faultdownservlet traversal check
                                                                                hp imc ictdownloadservlet traversal
                                                                                hp imc reportimgservlit traversal check
                                                                                hp imc som file download
                                                                                hp sitescope getfileinternal fileaccess
                                                                                hp sitescope getsitescopeconfiguration
                                                                                hp sitescope loadfilecontent fileaccess
                                                                                http header
                                                                                http hsts
                                                                                http login
                                                                                http put
                                                                                http sickrage password leak
                                                                                http traversal check
                                                                                httpdasm directory traversal
                                                                                iis internal ip
                                                                                iis shortname scanner
                                                                                influxdb enum
                                                                                intel amt digest bypass
                                                                                jboss status
                                                                                jboss vulnscan
                                                                                jenkins enum
                                                                                joomla bruteforce login
                                                                                joomla ecommercewd sqli scanner
                                                                                joomla gallerywd sqli scanner
                                                                                joomla pages
                                                                                joomla plugins
                                                                                joomla version
                                                                                kodi traversal
                                                                                linknat vos traversal check
                                                                                litespeed source disclosure
                                                                                majordomo2 directory traversal
                                                                                manageengine deviceexpert traversal check
                                                                                manageengine deviceexpert user creds
                                                                                manageengine securitymanager traversal check
                                                                                meteocontrol weblog extractadmin
                                                                                mod negotiation brute
                                                                                mod negotiation scanner
                                                                                ms09_020 webdav unicode bypass
                                                                                netdecision traversal
                                                                                nginx source disclosure
                                                                                novell file reporter fsfui fileaccess
                                                                                novell file reporter srs fileaccess
                                                                                novell mdm creds
                                                                                ntlm info enumeration
                                                                                open proxy scanner
                                                                                openmind messageos login
                                                                                http options
                                                                                oracle demantra database credentials leak
                                                                                oracle demantra file retrieval
                                                                                owa iis internal ip
                                                                                radware appdirector enum
                                                                                rails json yaml scanner
                                                                                rails mass assignment
                                                                                rails xml yaml scanner
                                                                                rewrite proxy bypass
                                                                                rips traversal check
                                                                                riverbed steelhead vcx file read 
                                                                                s40 traversal check
                                                                                sap businessobjects version enum
                                                                                sentry cdu enum
                                                                                servicedesk plus traversal
                                                                                sevone enum
                                                                                simple web server
                                                                                smt ipmi 49152 exposure
                                                                                smt ipmi cgi scanner
                                                                                smt ipmi static cert scanner
                                                                                smt ipmi url redirect traversal check
                                                                                soap xml
                                                                                sockso traversal
                                                                                splunk web login
                                                                                springcloud traversal check
                                                                                squid pivot scanning
                                                                                squid matrix user enum
                                                                                ssl
                                                                                support center plus directory traversal
                                                                                surgenews user creds
                                                                                svn scanner
                                                                                svn wcdb scanner
                                                                                sybase easerver traversal
                                                                                symantec brightmail ldapcreds
                                                                                thinvnc traversal
                                                                                titan ftp admin pwd
                                                                                http title
                                                                                tomcat enum
                                                                                tomcat mgr login
                                                                                totalis traversal check
                                                                                tplink traversal noauth
                                                                                http trace
                                                                                http trace axd
                                                                                vcms login
                                                                                verb auth bypass
                                                                                vhost scanner
                                                                                web vulndb
                                                                                webdav internal ip
                                                                                webdav scanner
                                                                                webdav website content
                                                                                webpagetest traversal
                                                                                wildfly traversal check
                                                                                hosts
                                                                                vulns
                                                                                creds
                                                                                loot
                                        
                           11:  (dig deeper?) metasploit auxiliary scan round 3: metasploit will open and run the following modules =                                                    
                                                                                 wordpress cp calendar sqli
                                                                                 wordpress ghost scanner
                                                                                 wordpress scanner
                                                                                 wp arbitrary file deletion
                                                                                 wp contus video gallery sqli
                                                                                 wp dukapress file read
                                                                                 wp gimedia library file read
                                                                                 wp mobile pack info disclosure
                                                                                 wp mobileedition file read
                                                                                 wp simple backup file read
                                                                                 wp subscribe comments file read
                                                                                 http xpath
                                                                                 yaws traversal
                                                                                 zenworks assetmanagment fileaccess
                                                                                 zenworks assetmanagement getconfig
                                                                                 ipidseq
                                                                                 ipmi cipher zero
                                                                                 ipmi version
                                                                                 kademila server info
                                                                                 lotus domino version
                                                                                 memcached amp
                                                                                 memcached udp version
                                                                                 clamav control
                                                                                 easycafe server fileaccess
                                                                                 ib service mgr info
                                                                                 ibm mq channel brute
                                                                                 ibm mq enum
                                                                                 java rmi server
                                                                                 oki scanner
                                                                                 poisonivy control scanner
                                                                                 sercom backdoor scanner
                                                                                 sunrpc portmapper
                                                                                 zenworks preboot fileaccess
                                                                                 msmail host id
                                                                                 mssql ping
                                                                                 mysql authbypass hashdump
                                                                                 natpmp portscan
                                                                                 nbname
                                                                                 nntp login
                                                                                 ntp monlist
                                                                                 ntp readvar
                                                                                 oracle emc sid
                                                                                 oracle spy sid
                                                                                 tnslsnr version
                                                                                 tnspoison checker
                                                                                 xdb sid brute
                                                                                 pcanywhere tcp
                                                                                 pcanywhere udp
                                                                                 pop3 login
                                                                                 pop3 version
                                                                                 postgres dbname flaf injection
                                                                                 postgres login
                                                                                 postgres schemadump
                                                                                 postgres version
                                                                                 canon irady pwd extract
                                                                                 printer download
                                                                                 printer list dir
                                                                                 printer ready message
                                                                                 printer version info
                                                                                 quake server info
                                                                                 sap ctc verb tampering user mgmt
                                                                                 sap hostctrl getcomputersystem
                                                                                 sap icf public info
                                                                                 sap icm uriscan
                                                                                 sap mgmt con abaplog
                                                                                 sap mgmt con extractusers
                                                                                 sap mgmt con getaccesspoints
                                                                                 sap mgmt con getenv
                                                                                 sap mgmt con getprocesslist
                                                                                 sap mgmt con getprocessparameter
                                                                                 sap mgmt con instanceproperties
                                                                                 sap mgmt con startprofile
                                                                                 sap mgmt con version
                                                                                 sap router portscanner
                                                                                 sap mgmt con version
                                                                                 sap router portscanner
                                                                                 sap service discovery
                                                                                 sip enumerator
                                                                                 sip enumerator tcp
                                                                                 sip options
                                                                                 sip options tcp
                                                                                 sipdroid ext enum
                                                                                 smb pip auditor
                                                                                 pipe dcerpc auditor
                                                                                 smb smb1
                                                                                 smb smb2
                                                                                 smb enumusers
                                                                                 smb enumusers domain
                                                                                 smb ms17_010
                                                                                 smb unitit cred
                                                                                 smtp enum
                                                                                 snmp arris_dg950
                                                                                 cnpilot r snmp loot
                                                                                 epmp1000 snmp loot
                                                                                 netopia enum
                                                                                 snmp sbg6580 enum
                                                                                 snmp enum
                                                                                 snmp enum hp laserjet
                                                                                 snmp ubee ddw3611
                                                                                 xerox workcentre enumusers
                                                                                 apache karaf command execution
                                                                                 ssh detect kippo
                                                                                 ssh fortinet backdoor
                                                                                 ssh juniper backdoor
                                                                                 ssh libssh auth bypass
                                                                                 openssl ccs
                                                                                 openssl heartbleed
                                                                                 steam server info
                                                                                 lantronix telnet password
                                                                                 lantronix telnet version
                                                                                 telnet encrypt overflow
                                                                                 telnet ruggedcom
                                                                                 ipswitch whatsupgold tftp
                                                                                 netdecision tftp
                                                                                 ubiquiti discover
                                                                                 udp amplification
                                                                                 ssdp amp
                                                                                 ssdp msearch
                                                                                 varnish cli file read
                                                                                 varnish cli login
                                                                                 esx fingerprint
                                                                                 vmauthd version
                                                                                 vmware enum permissions
                                                                                 vmware enum sessions
                                                                                 vmware enum users
                                                                                 vmware enum vms
                                                                                 vmware host details
                                                                                 vmware screenshot stealer
                                                                                 vmware update manager traversal
                                                                                 hosts
                                                                                 creds
                                                                                 vulns
                                                                                 loot

                           12: (continue 2 dig?) metasploit auxiliary scan round 4: metasploit will open and run the following modules = 
                                                 vnc login
                                                 vnc none auth
                                                 vxworks urgent11 check
                                                 vxworks wdbrpc bootline
                                                 vxworks wdbrpc version
                                                 winrm auth methods
                                                 open x11
                                                 ilo create admin account
                                                 hp imc som create account
                                                 cnpilot r cmd exec
                                                 cnpilot r fpt
                                                 contentkeeper fileaccess
                                                 foreman openstack satellite priv esc
                                                 iis auth bypass
                                                 iomega storcenterpro sessionid
                                                 joomla registration privesc
                                                 kaseva master admin
                                                 manage engine dc create admin
                                                 manage engine dir listing
                                                 netflow file download 
                                                 nexpose xxe file read
                                                 scadabr credential dump
                                                 scrutinizer add user
                                                 sophos wpa traversal
                                                 supra smart cloud tv rfi
                                                 sysaid file download
                                                 tomcat administration
                                                 tomcat utf8 traversal
                                                 trendmicro dlp traversal check
                                                 ulterius file download
                                                 vbulletin upgrade admin
                                                 webnms cred disclosure
                                                 webnms file download 
                                                 zyxel admin password extractor
                                                 sercomm dump config
                                                 natpmp map
                                                 tmlisten traversal
                                                 oracle login
                                                 oracle sid brute
                                                 solaris kcms readfile
                                                 edit html fileaccess
                                                 webmin file disclosure
                                                 nuuo nvmini reset
                                                 avtech744 dvr accounts
                                                 c2s dvr password disclosure
                                                 ipcamera password disclosure
                                                 bavision cam login
                                                 cctv dvr login
                                                 dahua dvr authbypass
                                                 dvr config disclosure
                                                 raysharp dvr passwords
                                                 roswill rxs3211 passwords
                                                 cerbus helpdesk hash disclosure
                                                 checkpoint hostname
                                                 citrix published applications
                                                 citrix published bruteforce
                                                 coldfusion pwd props
                                                 darkcomet filedownloader
                                                 dolibar creds sqli
                                                 emc cta xxe
                                                 hp snac domain creds
                                                 joomla com realestatemanager sqli
                                                 joomla contenthistory sqli
                                                 joomla weblinks sqli
                                                 kerberos enumusers
                                                 konica minoita pwd extract
                                                 lansweeper collector
                                                 mantisbt admin sqli
                                                 natpmp external address
                                                 oats downloadservlet traversal check
                                                 office365userenum
                                                 pimcore creds sqli
                                                 pulse secure file disclosure
                                                 gnap backtrace admin hash
                                                 rails doubletap file read
                                                 search email collector
                                                 shodan search
                                                 censys search
                                                 shodan honeyscore
                                                 sql domain creds
                                                 vbulletin vote sqli
                                                 xerox pwd extract
                                                 xymon info
                                                 zabbix toggleids sqli
                                                 openemr sqli dump
                                                 astrisk login
                                                 cerbus helpdesk hash disclosure
                                                 gnap backtrack admin hash
                                                 wp w3 cache hash extract
                                                 ipmi dumphashes
                                                 mssql hashdump
                                                 oracle hashdump
                                                 postgres hashdump
                                                 brocade enumhash
                                                 hosts
                                                 services
                                                 vulns
                                                 creds
                                                 loot


                           13: (exploit the target?) metasploit will attempt to autopwn the target and pop a shell

                           stop anonymous mode ?

debpg is the debian payload generator
winpg is the windows payload generator (uses avet)
quickpg is the quick payload generator, this builds windows,
                                                    linux,
                                                    android,
                                                    osx,
                                                    asp,
                                                    java,
                                                    php payloads                                                          

requirements
===============
vulscan -

git clone https://github.com/scipag/vulscan.git
 mv vulscan /usr/share/nmap/scripts
==============================
anonsurf -

install instructions

git clone https://github.com/Und3rf10w/kali-anonsurf.git

 chmod 755 -R kali-anonsurf/
 cd kali-anonsurf
 ./installer.sh
====================================
Make sure the nmap shodan nse script has your API key filled in
===========================================

after this is installed start the next step

install instructions
=======================
first put the AppImage where you want it and execute it. this will create the directories
where you will place the directories and files in this folder.

you can exit 0rion by typing exit

now move 

 logs/
 avet/
 cmd/
 exploits/
 wordlists/
 api-keys.yaml  
 
 to .config/0rion/Orion/

move 

cd-camstr1ke-user.txt
cd-camstr1ke-pass.txt

to /usr/share/wordlists/

move

mass_exploiter.rc

to /usr/share/metasploit-framework/scripts/resource/

now move into the avet directory which will be (/root/.config/0rion/Orion/avet/) and run the setup.sh script

next fill out the api-keys.yaml file in .config/0rion/Orion/
next make sure the nmap shodan nse script has your api key inserted into it.

now 0rion is setup

to run a module simple type ./modulename

