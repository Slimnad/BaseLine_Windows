
# BASELINE WINDOWS



**Comparatifs PolicyAnalyzer avant et apres le durcissement.**

![Alt text]()

**Résultat de la commande "Get-BitLockerVolume"**

![Alt text]()

**Résultat de la commande "Get-MpPreference"**

![Alt text]()

**Résultat de la commande "auditpol.exe /get /category:*"**

![Alt text]()

**Captures des logs (ou resultat powershell) avec échec d'authentification et escalade de privilèges**

#AuditPol /set /category:"Connexion de compte" /failue:enable

#AuditPol /set /subcategory:"Ouvrir la session" /failue:enable

![Alt text]()

