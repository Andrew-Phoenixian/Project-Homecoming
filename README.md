# Project-Homecoming

![](https://cdn.discordapp.com/attachments/821492326626099253/1030073972202668042/project-1.gif)

Hva er Project Homecoming?
=============

Dette er et RPG-spillprosjekt/-opplevelse med bruk av discord-roboter og våre egne genererte eiendeler som kart, karakterer, npc-er, gjenstander, oppdrag og en mengde andre ting.

Prosjektet har et stort team av spill-staff, oversettere, alpha testere, historie skrivere (de som lager historien bak enkelte karakterer, områder eller oppdrag.).

Prosjektet er et hovedsakelig backend prosjekt, da Discord behandler all frontend for meg.

Prosjektet er basert på JavaScript med json som lagrer UED informasjon (un-editable data), hvorav alt av lagring som blir endret er i vår maria db.

Prosjekt Oppsett
-------------

I vår server så har vi flere "botter" som gjør at våre drømmer kommer til virkelighet.
Vår hoved bot heter Idix Daemon, som har ansvar for alt i prosjektet for spill-logikk eller annet. Sammen med Idix, så har vi flere SoundPod's som har ansvar for å spille musikk, lydeffekter og stemme til karakterer som spilleren snakker med.

Her starter Idix som etterhvert starter disse "Soundpods"ene, disse vil automatisk bli med i voice kanaler på serveren.

https://gyazo.com/cf1c7955e1a75677258e84a1470f246c

![image](https://user-images.githubusercontent.com/42244235/195585550-a5ee1d80-d1cf-4f46-ab71-b4069e56293b.png)

https://user-images.githubusercontent.com/42244235/195585938-55cb69b2-3ea2-400f-a072-b2620297a1c4.mp4

Database
-------------

Som sagt, bruker vi mariadb til å lagre spill data.

![image](https://user-images.githubusercontent.com/42244235/195586468-d070164c-ac16-4fcd-bf2a-c1baac7ad625.png)
![image](https://user-images.githubusercontent.com/42244235/195586528-e9715c57-4618-4291-a104-8182c5deb175.png)
Siden spillere kan ha flere enn en karakter, så har de en "boundaccount" property som kobler den karakteren til dem sin bruker.
Her har du også mye annet data som hvilke quest de holder på med eller er ferdig med, karakter info som liv, mana og stamina osv.

Vi har laget et "sequence" system som er hvordan alle quest eller interaksjoner med NPC'er er satt opp.

![image](https://user-images.githubusercontent.com/42244235/195586879-e0c42603-3012-496e-8bea-fe33bcae3943.png)

Vårt Team
-------------


Prosjekt Ledere


##### Anders Hagås
###### Prosjekt Leder og Eier

##### Tim Laszlo
###### Eier og Rådgiver

Assisterende Utvikler
=============

Dette er personell som jobber med småting som å sette opp oppdrag, NPC'er og annet.

##### Sebastian
###### Assisterende Utvikler

##### Sakusa
###### Assisterende Utvikler
