# Discord-Redirect-CloudFlare-or-Website

Beispiel der Nutzung: [Hier klicken](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/index.html)

Erklärung in anderen Sprachen:


| Sprache | Link | Author |
| --- | --- | --- |
| EN | [Hier klicken](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/README.md) | @HappyRogelio7 |
| ES | [Hier klicken](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/README_ES.md) | @HappyRogelio7 |
| DE | [Hier klicken](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/README_DE.md) | @InfoBlock |
| JP | [Hier klicken](https://github.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/blob/master/README_JP.md) | @HappyRogelio7 |

---

Es funktioniert bei mir! Ein kleines Tutorial für die, die es verstanden haben.

**Dies ist für Cloudflare**

Erstelle einen DNS-Eintrag des Typ "A" 

Typ A erfordert das du im Namen deine gewünschte Subdomain und als IPv4 Adresse 8.8.8.8 angibst mit aktivierten Proxy.


<img src="https://raw.githubusercontent.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/master/5YtzR.png" alt="discord"/>


Gehe anschließend auf "Regeln"

Erstelle hier eine Seitenregel (Page Rule) und setze in die URL "deinesubdomain.deinedomain.de" ein, wähle als Einstellung "Weiterleitungs-URL" und setze den Statuscode auf "301: Dauerhafte Umleitung"

Als Ziel-URL gibst du nun den Permanenten Einladungslink für deinen Discord ein (https://discord.gg/EinladungsCode oder https://discord.com/invite/EinladungsCode)

<img src="https://raw.githubusercontent.com/HappyRogelio7/Discord-Redirect-CloudFlare-or-Website/master/oBufr.png" alt="discord"/>

That's how it works, in case it doesn't load you because you have already tried many methods with "discord.yourdomain.com", try another subdomain while the other one is reactivated or try from another device, example of another dub domain "discord1.yourdomain.com".
So funktioniert es. Sollte es nicht laden dann hast du "discord.deinedomain.de" schon zu oft versucht, versuche stattdessen eine andere Subdomain wie "discord1.deinedomain.de" oder versuche es auf einem anderen Gerät.

**Das ist alles, bye :D**
