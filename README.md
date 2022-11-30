# broken-link-hijacking

Target: https://saqco.com/

Bug : Broken link hijacking

Severity: (Medium) Improper Access Control - Generic


Summary:

A link(https://www.instagram.com/saqco.saudi/) in https://saqco.com/  was broken and anyone could create that account which leads to account impersonate.

Steps To Reproduce:

1.Go to https://saqco.com/
2.Scroll down to bottom there you can see that instagram icon.
3.Click on that icon, you will redirected to instagram account which I have been hijacked
4.Anyone could claim this username and broken link could be hijacked.

POC:


![image](https://user-images.githubusercontent.com/84071887/204716285-658ba168-601c-4ee9-abf4-759d90a8916e.png)

Impact:

Since the link can be hijacked so any attacker can claim the link and make fake instagram profile of MRM and can do scam with them.

Solution:

Add this link to the insta icon : https://www.instagram.com/saqco.saudi/

Supporting Material/References:

https://hackerone.com/reports/1117079
