# HTB-CPTS
 
*HTB CPTS is a highly hands-on certification that assesses the candidates’ penetration testing skills. HTB Certified Penetration Testing Specialist certification holders will possess technical competency in the ethical hacking and penetration testing domains at an intermediate level. They will be able to spot security issues and identify avenues of exploitation that may not be immediately apparent from searching for CVEs or known exploit PoCs. They can also think outside the box, chain multiple vulnerabilities to showcase maximum impact, and actionably help organizations remediate vulnerabilities through commercial-grade pentesting reports.*

The Exam:    
*The candidate will have to perform blackbox web, external and internal penetration testing activities against a real-world Active Directory network hosted in HTB’s infrastructure and accessible via VPN (using Pwnbox or their own local VM). Upon starting the examination process, a letter of engagement will be provided that will clearly state all engagement details, requirements, objectives, and scope. All a candidate needs to perform the required penetration testing activities is a stable internet connection and VPN software. HTB Certified Penetration Testing Specialist is the most up-to-date and applicable certification for Penetration Testers that focuses on both penetration testing and professionally communicating findings.*

I copied the full version from the homepage of Hack The Box - CPTS . In short, it is like testing a system from the outside in, without a single machine, worm chain attacks, privilege escalation, Double Pivoting, Active Directory attack, Domain Trust attack,... Finally, write a detailed report step by step.
I chose CPTS because it was cheap in Roadmap.
Okay, let me tell you a little about my feelings about it. Let those who want to take the exam consider it!

## Okay 
- Hack The Box Academy is a good offensive teaching platform, especially the Active Directory part. So I want to take the exam to experience and learn more about AD. The PATH section also provides basic and necessary knowledge.
- The learning materials and labs are quite good. If all of you play HTB or THM, PG will know that you need a VPN connection to do the lab. HTB Academy uses Pwnbox, just log in to its web platform and you can do it.
- The study materials explain in detail, and at the end of each module there is a lab for practice.

## Limit
- The course provides knowledge that is not too in-depth
- HTB's Discord said that just studying in the roadmap is enough to pass. I find it quite difficult, rabit holes are not necessary and many things in the exam require gg.
- Writing a rather long article :((
- No supervision, 10 days

## Exam
In theory, studying and doing labs takes 43 days. But if you have a good base, the web part will learn very quickly, only the AD, pivot, PE windows part will take a bit of time. It took me 2.5 months to finish studying, but I didn't take the exam right away but went to YouTube to watch bmdyy and CryptoCat . I saw the offensive expert box bmdyytook 5 days, the remaining box took 2 times to pass. So I thought "I'm sure I'll pass the exam" so I studied for 3 more weeks and waited until the holiday April 30-May 1 to take the exam :))

The first time I failed, I thought it was like the last module. But no, stuck on the previous device, how can I switch to the next device? So I submitted a blank report to retake the exam a second time.
The second time, I thoroughly reviewed the above 3 modules + bloodhound, crackmapexec. I completed the lab exam over 7 days and wrote the report for 11-12 hours. Submit the report and receive a pass notification within 4 days.

Anyway, it was an interesting experience.
Thanks for reading this far!

## Reference link/resource

[🎙️ HTB Stories #10](https://www.youtube.com/watch?v=wwmCHeYd1I4&ab_channel=HackTheBox)    
[My Guide to HTB’s CPTS Course/Exam - bmdyy](https://www.youtube.com/watch?v=dRW1Gxmu__Q&ab_channel=bmdyy)      
[ HTB CPTS - Review + Tips - YouTube - CryptoCat ](https://www.youtube.com/watch?v=UN5fTQtlKCc&ab_channel=CryptoCat)     
#### Tools 
[Edges — BloodHound 4.3.1 documentation](https://bloodhound.readthedocs.io/en/latest/data-analysis/edges.html)    
[Introduction - CrackMapExec doc )](https://wiki.porchetta.industries/)    
[PowerView doc](https://powersploit.readthedocs.io/en/latest/)    
#### Pivoting
[Attacking Enterprise Networks: Double Pivot using Chisel](https://forum.hackthebox.com/t/attacking-enterprise-networks-double-pivot-using-chisel/267043)      
[runas - Running PowerShell as another user, and launching a script - Stack Overflow](https://stackoverflow.com/questions/28989750/running-powershell-as-another-user-and-launching-a-script) 
#### 3 module 
[Windows Privilege Escalation](https://academy.hackthebox.com/module/details/67)  
[Active Directory Enumeration & Attacks ](https://academy.hackthebox.com/module/details/143)  
[Pivoting, Tunneling, and Port Forwarding](https://academy.hackthebox.com/module/details/158)  
