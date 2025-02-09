# MH-PR
Master Hacker Chapter 5
# Google Hacking - 

  So in section we get introdused into Google Hacking which is not really hacking but a more indeath way of serching google for what is already public facing. Its Also called Google Dorking and you can find a number of them already done at www.exploit-db.com.
  filetype:sql intext:password | pass |passwd intext:username intext 
    We can use keywords to narrow down the search like the following - 
      intitle:hackers-arise
![image](https://github.com/user-attachments/assets/056973a3-bb10-4873-acdc-c1a9795d4f40)
Screen shot of first page that and hackers-arrise in the title. 

This will also work for images and videos 

you can also look for a file type by entering something like 
  passwords filetype:xls

We can dive more into selective and combine google keys. - 
    filetype : xls site : gov inurl : content
      This pulls an xls file from a gov web site that contanes a contacts list
If we where looking for email addresses then we might use this link - 
  
Other Key wards include - 

        allinurl
          allintitle: "network camera network camera"
        filetype
          
        inanchor
        intext
        intitle
        inurl
        link
        site

filetype:sql intext:password | pass | passwd intext :username intext insert into 'users' values


# Netcraft
Netcraft is a website that tracks data about web servers.
The site today is a bigger site then when this book was written, so I had to find what i needed to search the web. 
I did find the 'Whats the Site Running' to help us understand what technologies are running the site. 
here we are looking at Facebook, - 

![image](https://github.com/user-attachments/assets/388e886a-3bee-4a5e-a95d-812501d086e8)

Background
Site title	Log in to Facebook
Site rank	1478
Description	Log in to Facebook to start sharing and connecting with your friends, family and people you know.
Date first seen	May 1997
Primary language	English
Network
Site	http://facebook.com
Netblock Owner	Facebook, Inc.
Hosting company	Facebook
Hosting country	 US
IPv4 address	157.240.202.35 (VirusTotal)
IPv4 autonomous systems	AS32934
IPv6 address	2a03:2880:f17b:187:face:b00c:0:25de
IPv6 autonomous systems	AS32934
Reverse DNS	edge-star-mini-shv-02-cdg4.facebook.com
Domain	facebook.com
Nameserver	a.ns.facebook.com
Domain registrar	registrarsafe.com
Nameserver organisation	whois.registrarsafe.com
Organisation	Meta Platforms, Inc., 1601 Willow Rd, Menlo Park, 94025, United States
DNS admin	dns@facebook.com
Top Level Domain	Commercial entities (.com)
DNS Security Extensions	Enabled
IP delegation
IPv4 address (157.240.202.35)
IP range	Country	Name	Description
::ffff:0.0.0.0/96	 United States	IANA-IPV4-MAPPED-ADDRESS	Internet Assigned Numbers Authority
 ↳ 157.0.0.0-157.255.255.255	 United States	NET157	Various Registries (Maintained by ARIN)
  ↳ 157.240.0.0-157.240.255.255	 United States	THEFA-3	Facebook, Inc.
   ↳ 157.240.202.35	 United States	THEFA-3	Facebook, Inc.
IPv6 address (2a03:2880:f17b:187:face:b00c:0:25de)
IP range	Country	Name	Description
::/0	N/A	ROOT	Root inet6num object
 ↳ 2a00::/11	 European Union	EU-ZZ-2A00	RIPE NCC
  ↳ 2a00::/12	 Netherlands	EU-ZZ-2A00	RIPE Network Coordination Centre
   ↳ 2a03:2880::/29	 Ireland	IE-FACEBOOK-201100822	Meta Platforms Ireland Limited
    ↳ 2a03:2880:f17b:187:face:b00c:0:25de	 Ireland	IE-FACEBOOK-201100822	Meta Platforms Ireland Limited
IP Geolocation
We use multilateration to independently determine the location of a server. Read more.

+
−
Legend:

Advertised country

Multilaterated locationLeaflet | © OpenStreetMap contributors
SSL/TLS
This is not a HTTPS site. If you're looking for SSL/TLS information try the HTTPS site report.

Sender Policy Framework
A host's Sender Policy Framework (SPF) describes who can send mail on its behalf. This is done by publishing an SPF record containing a series of rules. Each rule consists of a qualifier followed by a specification of which domains to apply this qualifier to. For more information please see open-spf.org.

Qualifier	Mechanism	Argument
Modifiers extend the functionality of SPF records. The most common one is the redirect which indicates another host contains the SPF record being searched for.

Modifier	Argument
redirect	_spf.facebook.com
DMARC
DMARC (Domain-based Message Authentication, Reporting and Conformance) is a mechanism for domain owners to indicate how mail purporting to originate from their domain should be authenticated. It builds on SPF and DKIM, providing a method to set policy and to give reporting of failures. For more information please see dmarc.org.

Raw DMARC record:

v=DMARC1; p=reject; rua=mailto:a@dmarc.facebookmail.com; ruf=mailto:fb-dmarc@datafeeds.phishlabs.com; pct=100
Tag	Field	Value
p=reject	Requested handling policy	Reject: emails that fail the DMARC mechanism check should be rejected. Rejection SHOULD occur during the SMTP transaction.
rua=mailto:a@dmarc.facebookmail.com	Reporting URI(s) for aggregate data	a@dmarc.facebookmail.com
ruf=mailto:fb-dmarc@datafeeds.phishlabs.com	Reporting URI(s) for failure data	fb-dmarc@datafeeds.phishlabs.com
pct=100	Sampling rate	100% of messages from the Domain Owner's mail stream should have DMARC applied.
Web Trackers
Web Trackers are third-party resources loaded onto a webpage. Trackable resources include social sharing widgets, javascript files, and images. These trackers can be used to monitor individual user behaviour across the web. Data derived from these trackers are primarily used for advertising or analytics purposes.

1 known tracker was identified.
Companies
Categories
Company	Primary Category	Tracker	Popular Sites with this Tracker
Facebook 	CDN	Facebook CDN	www.ithome.com.tw, www.babelio.com, www.breitbart.com
Site Technology (fetched 28 days ago)
Server-Side
Includes all the main technologies that Netcraft detects as running on the server such as PHP.

Technology	Description	Popular sites using this technology
SSL 	A cryptographic protocol providing communication security over the Internet	saas-aftral.octime.net
PHP 	PHP is supported and/or running	www.pixiv.net, www.skillacloud.com, www.forexfactory.com
Client-Side
Includes all the main technologies that run on the browser (such as JavaScript and Adobe Flash).

Technology	Description	Popular sites using this technology
JavaScript 	Widely-supported programming language commonly used to power client-side dynamic content on websites	www.netflix.com, www.instagram.com, www.amazon.com
Client Pull	No description	www.perplexity.ai, www.upwork.com, x.com
Content Delivery Network
A content delivery network or content distribution network (CDN) is a large distributed system of servers deployed in multiple data centers in the Internet. The goal of a CDN is to serve content to end-users with high availability and high performance.

Technology	Description	Popular sites using this technology
Facebook CDN	Facebook content delivery network	www.babelio.com, www.ithome.com.tw, www.breitbart.com
Character Encoding
A character encoding system consists of a code that pairs each character from a given repertoire with something else such as a bit pattern, sequence of natural numbers, octets, or electrical pulses in order to facilitate the transmission of data (generally numbers or text) through telecommunication networks or for data storage.

Technology	Description	Popular sites using this technology
UTF8 	UCS Transformation Format 8 bit	
HTTP Compression
HTTP compression is a capability that can be built into web servers and web clients to make better use of available bandwidth, and provide greater transmission speeds between both.

Technology	Description	Popular sites using this technology
Gzip Content Encoding 	Gzip HTTP Compression protocol	www.amazon.es, www.amazon.com.br, www.amazon.ca
Web Browser Targeting
Web browser targeting enables software applications to make use of specific functions of the browser as well as optimizing the application for specific browser versions.

Technology	Description	Popular sites using this technology
X-Content-Type-Options 	Browser MIME type sniffing is disabled	www.twitch.tv, www.deepl.com, www.canva.com
X-XSS-Protection Disabled 	Cross-site scripting protection is disabled	www.virustotal.com, www.notion.so, base-contacts.aftral.com
Strict-Transport-Security (preload)	No description	www.amazon.fr, www.amazon.in, www.amazon.de
Content Security Policy 	Detect and mitigate attacks in the browser	app.powerbi.com, accounts.google.com, mail.proton.me
X-Frame-Options Deny 	Prevents the web page being embedded in a frame	www.bbc.co.uk, yandex.com, discord.com
Strict Transport Security 	Web security policy mechanism whereby a web server declares that complying user agents are to interact with it using only secure HTTP connections	chatgpt.com
Doctype
A Document Type Declaration, or DOCTYPE, is an instruction that associates a particular SGML or XML document (for example, a webpage) with a Document Type Definition (DTD).

Technology	Description	Popular sites using this technology
HTML5 	Latest revision of the HTML standard, the main markup language on the web	webmail.vinccihoteles.com, campus-1001.ammon.cloud
CSS Usage
Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation semantics (the look and formatting) of a document written in a markup language (such as XHTML).

Technology	Description	Popular sites using this technology
External 	Styles defined within an external CSS file	




