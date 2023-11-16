# Discord-Redirect-CloudFlare-or-Website

Example using website: [Click Here](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/index.html)

Explanation in orthers langs:


| Lang | Link |
| --- | --- |
| EN | [Click Here](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/README.md) |
| ES | [Click Here](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/README_ES.md) |
| DE | [Click Here](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/README_DE.md) |
| JP | [Click Here](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/README_JP.md) |

---

It works for me thanks full tutorial in case someone understood it.

**This is for CloudFlare**

Created Add Record "A"

this type "A" must contain in Name: "Name you want for the sub domain", and in IPv4 address they must place "8.8.8.8", Proxy status activated.


<img src="https://raw.githubusercontent.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/master/5YtzR.png" alt="discord"/>


Then they go to "Rules"

Here they add a Create a new rule, and place the following data in URL: "yoursubdomanin.yourdomain.com", luen in Then the settings are: Select "Forwarding URL", then in Select status code: Select "301 - Permanent Redirect"

in Enter destination URL (required) you put the url of the Discord invitation: "https://discord.gg/yourInviteCode".

<img src="https://raw.githubusercontent.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/master/oBufr.png" alt="discord"/>

That's how it works, in case it doesn't load you because you have already tried many methods with "discord.yourdomain.com", try another subdomain while the other one is reactivated or try from another device, example of another dub domain "discord1.yourdomain.com".

**That's bye :D**
