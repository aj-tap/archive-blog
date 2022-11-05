---
published: true
layout: post
title: _init_
---
## THM-Writeups Confidential

We got our hands on a confidential case file from some self-declared "black hat hackers"... it looks like they have a secret invite code available within a QR code, but it's covered by some image in this PDF! If we want to thwart whatever it is they are planning, we need your help to uncover what that QR code says.

##### Let's start our Ubuntu Vm Box and navigate to the home/ubuntu/confidential directory, where we can find the Repdf.pdf file.
![writeups_confidential-1]({{site.baseurl}}/images/Writeups/writeups_confidential-1.png){:height="250px" width="250px"}


##### It looks like our ubuntu Vm box has Libre Office Suite, Let's open the file using Libre draw office. 
![writeups_confidential-2]({{site.baseurl}}/images/Writeups/writeups_confidential-2.png){:height="250px" width="250px"}



##### It looks like the attacker didn't flatten the pdf. We can simply drag or delete the vector image.
![writeups_confidential-4]({{site.baseurl}}/images/Writeups/writeups_confidential-4.png){:height="250px" width="250px"}




##### Take a screenshot of the QR code, then decode it to retrieve the flag. 
![writeups_confidential-3]({{site.baseurl}}/images/Writeups/writeups_confidential-3.png){:height="250px" width="250px"}
