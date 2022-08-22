# Beveiliging en privacy gebruiksgegevens

Binnen Argu kunnen persoonsgegevens worden verwerkt. Wanneer gebruikers zich registreren, geven ze hun e-mailadres. Verder kunnen beheerders zelf bepaalde velden instellen waar persoonsgegevens in staan.

In onze [Privacy policy](https://argu.co/argu/privacy) staat beschreven hoe wij om gaan met persoonsgegevens.

## Voeldoet Argu aan de AVG / GDPR?

Ja, we nemen privacy uiterst serieus en houden ons aan de Algemene Vordering Gegevensbescherming.

## Is Argu verwerkingsverantwoordelijke?

Meestal wel, maar je kunt er als klant voor kiezen om zelf een privacy overeenkomst met de gebruikers van jouw Argu website aan te gaan. In dat geval zijn wij als Argu _verwerker_ in plaats van _verwerkingsverantwoordelijke_. We zullen in dat geval een _verwerkingsovereenkomst_ met jou opstellen.

## Security & privacy maatregelen

- We gebruiken in externe verbindingen altijd [SSL versleutelde](https://www.ssllabs.com/ssltest/analyze.html?d=argu.co&latest) HTTPS verbindingen en we gebruiken DNSSEC om onze DNS records te versleutelen. We scoren door dergelijke maatregelen [100% op internet.nl](https://internet.nl/site/argu.co/803966/).
- Alleen specifieke werknemers hebben database toegang. Toegang werkt via een versleutelde SSH verbinding, en is met een firewall van Cloud66 (de [CX tool](https://github.com/cloud66-oss/cx)) afgeschermd.
- Alle accounts voor kritieke infrastructuur maken gebruik van two-factor authentication (2FA).
- We draaien bij iedere deploy geautomatiseerde dependency vulnerability checks en static code analyse (rubocop, brakeman)
- Waar we [bezoekersstatistieken](https://argu.co/argu/t/10532) verzamelen, doen we dat met de zelf-gehoste software Matomo, en daar verwijderen we altijd de laatst drie of zes nummers van IP adressen.
- We gebruiken strenge CSP en CORS instellingen, zodat cross-site scripting attacks niet goed mogelijk zijn.
- Werknemers mogen alleen gevoelige gegevens (zoals productie data van Argu) op hun laptop hebben in uitzonderlijke situaties, en mogen dit alleen versleuteld opslaan.
- We hanteren een whitelist voor extensies voor bijlagen, zodat het lastiger is om malware te verspreiden.
