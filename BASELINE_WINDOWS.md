
# BASELINE WINDOWS


**Comparatifs PolicyAnalyzer avant et apres le durcissement.**
- Avant
![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/5ae72679-326d-4185-8e87-7a99e940bfe9)

- Après
![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/4b89dc76-5fb0-44fb-b0b5-a4e2cf676913)

**Résultat de la commande "Get-BitLockerVolume"**

![Alt text](https://github.com/Slimnad/BaseLine_Windows/blob/main/Bitlock.png?raw=true)

**Résultat de la commande "Get-MpPreference"**
- Avant renforcement
![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/1c964c57-9282-4e90-a2e8-fcee18304661)

- Après renforcement
![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/13ef1c25-5dbc-4a08-893a-ec6e92e0758a)


**Résultat de la commande "auditpol.exe /get /category:*"**

![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/05b0d608-4100-4ee2-99bb-f7e16d883f50)

**Captures des logs (ou resultat powershell) avec échec d'authentification et escalade de privilèges**

#AuditPol /set /category:"Connexion de compte" /failure:enable

#AuditPol /set /subcategory:"Ouvrir la session" /failure:enable

![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/cd6cb897-d730-4bf8-9575-8ce3157c78ff)

![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/ee5bbcaf-13ec-49a7-9e86-45bfd60ee3e9)

![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/552d9e5c-6098-4649-85a1-85ecdc21e498)


