---
title: Some Quick Notes on Phone Security
date: 2022-03-30T23:38:31+01:00
lastmod: 2022-06-25T01:30:45+01:00
author: Darthagnon
avatar: /img/authors/Darthagnon.jpg
authorlink: https://robot-one.github.io
cover: /img/hackerman.jpg
images:
   - /img/hackerman.jpg
categories:
  - Tech
tags:
  - Romanian
  - Telephone
  - Hacks
  - Security Research
# nolastmod: true
draft: false
---

A friend recently contacted me with some techie questions about smartphone privacy. Security research is one of my obsessions, so I though it expedient to give a thorough answer. 

<!--more-->

Perhaps too thorough? It's rather long, so I thought it worth sharing here, too. And then I forgot to publish the article for a couple months 😅. I have polished it and added references to various instructional articles. 

## Further Reading
Security professionals have done a much better job than me, comparing the security of all the popular chat applications here:
### [SecureMessagingApps.com](https://www.securemessagingapps.com/)

## ![English Language](/img/logos/United-Kingdom.gif) English:

> Hi
> 
> Please tell me: can someone can check your WhatsApp, read your conversations or listen to your phone.
> 
> Or how do I know who's controlling my phone?
> 
> I've heard that you can install ghost apps on your phone that know everything you're talking about. Is that true?
> 
> How do I know if I have something like that on my phone?
> 
> ~ Anonymous [28 Mar 2022, 5:48 PM] 

### Whatsapp
**Whatsapp** is "encrypted" - no one else can read your messages, hear your calls, etc. EXCEPT if you backup Whatsapp to Google Drive. Then Google can read your messages (**not saying they do**, but they can)<sup>[1]</sup>. Check your Whatsapp settings to enable "encrypted backups"<sup>[2]</sup> to make it more secure and make sure that Google can't read your messages from the backup. Also enable a Whatsapp 2-Step-Verification PIN<sup>[3]</sup>, so that if there's a hack, someone can't just log in and read your messages<sup>[4]</sup>.

### Facebook Messenger
**[Facebook Messenger]** is normally "unencrypted" - this means Facebook, Mark Zuckerberg, FBI, CIA, etc. can read everything in Messenger. The same for Instagram. Proof: remember those times I tried to send you links to movies, and Facebook deleted them?

### Telegram
**[Telegram]** has some encryption; not as good as Whatsapp, but it's more convenient and also not an American company (and American companies do a lot of spying, and you still have to trust Whatsapp's promise that your messages are encrypted). It's made by Russian rebel Pavel Durov, and used by lots of "illegal" groups, so it's gotta be good haha (I set up a Telegram account for you ages ago on the eBook and laptop, which I used to send some books over)

### Other encrypted communications: 

**[Signal]** (lots of people recommend it), **[Matrix]** (still a work-in-progress), **[Threema]** (Swiss, $$$), **[Jami]** (I use this one to call you sometimes, works better for video calls), **[Tox]** (I like this one, but it's difficult to set up), **[Session]** (no-one uses it), **[Deltachat]** (uses email, no video/voice calls, but very good). A lot of these are "Open Source", which means everyone can see the computer code that makes them. This means you can see for yourself if they're telling the truth about encryption, and don't have to take a company's word for it.

### Other unencrypted communications: 

**TikTok** is literally spyware that tracks your interests and data and sends it to China<sup>[5], [6]</sup> (search for "TikTok Spyware" and read some articles). **Skype** is unencrypted and not very good, but it's old, so still common to use. 

Also, your phone's keyboard app might be sending what you type somewhere; I recommend installing an Open Source keyboard that is guaranteed not to spy on you, like **[Florisboard]** from the F-Droid store. 

Oh, and **uninstall all coronavirus tracking/contact tracing apps**; use paper or PDF only. There have been several cases of those being used to track people by police <sup>[7], [8], [9], [10], [11], [12]</sup>. And keep your phone in airplane mode as much as possible, this makes sure you're not trackable via mobile towers and GPS (that's how the Russians are finding all the stupid English/American people who go to Ukraine to fight and take pictures for Instagram)<sup>[13], [14], [15]</sup>.

Those are the main areas. I don't know about "ghost apps", but security holes appear from time to time; keep software up-to-date, and be careful installing hacked apps (get them from reliable sources). Uninstall any apps you don't recognise; use 2-factor-authentication for all accounts, and (if possible) different passwords for every account (I recommend a password manager like **[Keepass]**). There are antivirus apps, but **(my opinion)** they're usually as bad as the viruses; Android is pretty secure. There are also more advanced methods (e.g. install alternative operating systems like **[LineageOS]/[CalyxOS]/[GrapheneOS]**, but those only work on "hackable" phones, and you have a Huawei which is not hackable). Notably, Huawei has been partially banned from the UK and USA over fears they have hardware hacks built in by the Chinese government<sup>[16], [17]</sup>.

---------------------------------
## ![Romanian Language](/img/logos/Romania.gif) Romanian:

> Bună
> 
> Te rog sa imi zici daca cineva poate sa iti controleze WhatsApp, sa iti citeasca conversațiile sau sa asculte telefonul
> 
> Sau cum pot sti cine imi controlează telefonul?
> 
> Am  auzit ca se pot instala pe telefon aplicatie fantoma care stie tot ce vorbesti. Este adevarat?
> 
> Cum pot sti daca am asa ceva pe telefon?
> 
> ~ Anonim [28 Mar 2022, 5:48 PM] 

### Whatsapp
**Whatsapp** este "criptat" - nimeni altcineva nu vă poate citi mesajele, nu vă poate auzi apelurile etc. CU EXCEPȚIA dacă faceți o copie de rezervă a Whatsapp pe Google Drive. Atunci Google vă poate citi mesajele (**nu spun că o face**, dar poate)<sup>[1]</sup>. Verificați setările Whatsapp pentru a activa "copii de rezervă criptate"<sup>[2]</sup> pentru a-l face mai sigur și pentru a vă asigura că Google nu vă poate citi mesajele din copia de rezervă. De asemenea, activați un PIN Whatsapp de autentificare cu 2 factori<sup>[3]</sup>, astfel încât, în cazul unui hacker, cineva să nu se poată loga și să vă citească mesajele<sup>[4]</sup>.

### Facebook Messenger
**[Facebook Messenger]** este "necriptat" - acest lucru înseamnă că Facebook, Mark Zuckerberg, FBI, CIA etc. pot citi totul în Messenger. Același lucru pentru Instagram. Dovada: îți amintești de acele momente în care am încercat să-ți trimit linkuri către filme, iar Facebook le-a șters?

### Telegram
**[Telegram]** are o anumită criptare; nu la fel de bună ca Whatsapp, dar este mai convenabilă și, de asemenea, nu este o companie americană (iar companiile americane fac multă spionaj, și tot trebuie să ai încredere în promisiunea lui Whatsapp că mesajele tale sunt criptate). Este făcut de rebelul rus Pavel Durov și este folosit de o mulțime de grupuri "ilegale", așa că trebuie să fie bun haha (ți-am făcut un cont Telegram cu mult timp în urmă pe eBook și pe laptop, pe care l-am folosit pentru a trimite niște cărți)

### Alte comunicații criptate: 

**[Signal]** (multă lume îl recomandă), **[Matrix]** (încă în lucru), **[Threema]** (elvețian, $$$), **[Jami]** (Îl folosesc pe acesta pentru a te suna uneori, funcționează mai bine pentru apeluri video), **[Tox]** (îmi place acesta, dar este dificil de configurat), **[Session]** (nu îl folosește nimeni), **[Deltachat]** (folosește e-mail, nu folosește apeluri video/vocale, dar este foarte bun). Multe dintre acestea sunt "Open Source", ceea ce înseamnă că oricine poate vedea codul informatic care le creează. Acest lucru înseamnă că puteți vedea cu ochii voștri dacă spun adevărul despre criptare și nu trebuie să credeți pe cuvânt o companie.

### Alte comunicații necriptate: 
**TikTok** este literalmente un spyware care vă urmărește interesele și datele și le trimite în China<sup>[5], [6]</sup> (căutați "TikTok Spyware" și citiți câteva articole). **Skype** este necriptat și nu este foarte bun, dar este vechi, așa că încă se mai folosește frecvent. 

De asemenea, este posibil ca aplicația de tastatură a telefonului tău să trimită undeva ceea ce tastezi; îți recomand să instalezi o tastatură Open Source care este garantată că nu te spionează, cum ar fi **[Florisboard]** din magazinul F-Droid. 

Oh, și **dezinstalați toate aplicațiile de urmărire a coronavirusurilor/identificare a contactelor**; folosiți doar hârtie sau PDF. Au existat mai multe cazuri în care acestea au fost folosite pentru a urmări oamenii de către poliție<sup>[7], [8], [9], [10], [11], [12]</sup>. Și țineți-vă telefonul în modul avion cât mai mult posibil, asta vă asigură că nu sunteți localizabil prin turnurile de telefonie mobilă și GPS (așa îi găsesc rușii pe toți proștii de englezi/americani care merg în Ucraina să se bată și să facă poze pentru Instagram)<sup>[13], [14], [15]</sup>.

Acestea sunt principalele domenii. Nu știu despre "aplicații fantomă", dar din când în când apar găuri de securitate; mențineți software-ul actualizat și aveți grijă să instalați aplicații piratate (procurați-le din surse de încredere). Dezinstalați orice aplicații pe care nu le recunoașteți; utilizați autentificarea cu 2 factori pentru toate conturile și (dacă este posibil) parole diferite pentru fiecare cont ( recomandați un manager de parole precum **[Keepass]**). Există aplicații antivirus, dar acestea sunt de obicei la fel de rele ca și virușii **(părerea mea)**; Android este destul de sigur. Există, de asemenea, metode mai avansate (de exemplu, instalați sisteme de operare alternative precum **[LineageOS]/[CalyxOS]/[GrapheneOS]**, dar acestea funcționează doar pe telefoane "hackabile", iar dumneavoastră aveți un Huawei care nu este hackabil). În special, Huawei a fost interzis parțial în Marea Britanie și SUA din cauza temerilor că au hardware-uri cu hack-uri încorporate de guvernul chinez<sup>[16], [17]</sup>.

*Translated with [www.DeepL.com/Translator](https://www.deepl.com/translator) (free version)*

[1]: https://www.helpnetsecurity.com/2018/08/29/whatsapp-backups-google-drive/
[2]: https://faq.whatsapp.com/general/chats/how-to-turn-on-and-turn-off-end-to-end-encrypted-backup/
[3]: https://faq.whatsapp.com/general/verification/how-to-manage-two-step-verification-settings/
[4]: https://wabetainfo.com/stolen-whatsapp-accounts-the-real-story/
[5]: https://mashable.com/article/tiktok-china-access-data-in-us
[6]: https://www.buzzfeednews.com/article/emilybakerwhite/tiktok-tapes-us-user-data-china-bytedance-access
[7]: https://7news.com.au/news/western-australia-police/wa-police-accessed-contact-tracing-data-c-3118713
[8]: https://www.washingtonpost.com/world/2022/01/13/german-covid-contact-tracing-app-luca/
[9]: https://www.dw.com/en/german-police-under-fire-for-misuse-of-covid-contact-tracing-app/a-60393597
[10]: https://www.technologyreview.com/2021/01/05/1015734/singapore-contact-tracing-police-data-covid/
[11]: https://caldronpool.com/police-use-data-from-contact-tracing-app-to-find-criminals/
[12]: https://www.met.police.uk/foi-ai/metropolitan-police/disclosure-2020/december-2020/nhs-test--trace-or-nhs-covid-19-application-data-for-investigation-purpose/
[13]: https://www.nzherald.co.nz/world/russia-ukraine-war-foreign-legion-volunteers-flee-ukraine-after-russian-missile-strike-on-training-base/QVQOMEWFUBQZPBL6YYCJXQ3RYE/
[14]: https://nationalfile.com/reddit-inspired-foreign-fighters-reportedly-killed-russian-airstrikes-ukraine/
[15]: https://knowyourmeme.com/memes/redditors-in-ukraines-international-legion
[16]: https://www.channele2e.com/business/enterprise/huawei-banned-in-which-countries/
[17]: https://en.wikipedia.org/wiki/Criticism_of_Huawei#Espionage_and_security_concerns
[Facebook Messenger]: https://www.messenger.com/
[Telegram]: https://telegram.org/
[Signal]: https://signal.org/
[Matrix]: https://matrix.org/clients
[Threema]: https://threema.ch/en
[Jami]: https://jami.net/
[Tox]: https://tox.chat/clients.html
[Session]: https://getsession.org/
[Deltachat]: https://delta.chat/
[Florisboard]: https://f-droid.org/en/packages/dev.patrickgold.florisboard/
[KeePass]: https://keepass.info/download.html
[LineageOS]: https://lineageos.org/
[CalyxOS]: https://calyxos.org/
[GrapheneOS]: https://grapheneos.org/