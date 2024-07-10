
# BASELINE WINDOWS



**Comparatifs PolicyAnalyzer avant et apres le durcissement.**

![Alt text]()

**Résultat de la commande "Get-BitLockerVolume"**

![Alt text](https://github.com/Slimnad/BaseLine_Windows/blob/main/Bitlock.png?raw=true)

**Résultat de la commande "Get-MpPreference"**



**Résultat de la commande "auditpol.exe /get /category:*"**

![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/05b0d608-4100-4ee2-99bb-f7e16d883f50)

**Captures des logs (ou resultat powershell) avec échec d'authentification et escalade de privilèges**

#AuditPol /set /category:"Connexion de compte" /failue:enable

#AuditPol /set /subcategory:"Ouvrir la session" /failue:enable

![image](https://github.com/Slimnad/BaseLine_Windows/assets/163383857/cd6cb897-d730-4bf8-9575-8ce3157c78ff)


