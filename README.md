# MH-PR
# Master Hacker Chapter 5 - Passive Reconnaissance
## Google Hacking - 

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


## Netcraft
Netcraft is a website that tracks data about web servers.
The site today is a bigger site then when this book was written, so I had to find what i needed to search the web. 
I did find the 'Whats the Site Running' to help us understand what technologies are running the site. 
here we are looking at Facebook, - 

![image](https://github.com/user-attachments/assets/388e886a-3bee-4a5e-a95d-812501d086e8)

![image](https://github.com/user-attachments/assets/66009b24-32a6-428e-9799-68cf22f32d2c)

![image](https://github.com/user-attachments/assets/60532cc6-08e2-4ece-94e1-3e96b07b77fe)

![image](https://github.com/user-attachments/assets/0a768c2a-2638-4913-9120-c2717ff646ed)

![image](https://github.com/user-attachments/assets/798c398c-2486-4a11-961b-46336c15819c)

![image](https://github.com/user-attachments/assets/0424eda6-daa5-4245-bea5-6351ea5445e4)

#Whois
When someone regesters a web site they are requriered to provide some neccessery information about them selves and their company. 
This infomation is maintained by the registrar and a central registry by InterNIC.
We can Query port 43

![image](https://github.com/user-attachments/assets/c1570c54-de72-4658-852a-bfd7c90a1f0c)
![image](https://github.com/user-attachments/assets/5187e987-235e-4b4b-b2ef-3bffe91c2f92)
![image](https://github.com/user-attachments/assets/274911d1-7f48-4b16-8eb6-dd7a69d7e193)

When using windows systems tou can refer to the following, - 
  - http://whois.domaintools.com
  - http://ripe.net
  - http://whois.se

## shodan - 
Shodan is a search engine that pulls banners from websites. 
Enabling us to see many many IOT devices on the net many of them are unsecre meaning we can get access, sometimes they have default passwords and other times they just dont have any security on them at all. 
You have to sign up for an account to use it to start with . 
![image](https://github.com/user-attachments/assets/cf671e6b-0fa5-49c5-9a5a-a1509b86ecb7)
To carry on i need a paid membership which i will come back too. 
But in a nut shell it allows users to find devices such as servers, webcams, routers, and other devices that are connected to the internet. Shodan can be used to find devices that are vulnerable to attack, or to identify devices that are misconfigured.

## DOS















