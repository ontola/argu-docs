# Argu op eigen domein hosten

Jouw Argu website is standaard beschikbaar op argu.co/websitenaam, maar kan ook vanaf een andere domeinnaam of subdomein beschikbaar worden gemaakt. Je moet daarvoor je DNS Records aanpassen in de beheeromgeving van je domeinnaam, en deze aan ons doorgeven. Welke DNS Records je moet aanpassen, hangt af van of je een subdomein wil of niet:

## Op een subdomein (subdomein.example.com)

1. Voeg op het gekozen subdomein een DNS CNAME record toe met de waarde argu.co.
1. Geef de URL en de naam van de Website op Argu aan ons door via info@argu.co.

## Op een hoofddomein (example.com)

1. Voeg op het gekozen domein een A Record met waarde 188.166.203.193.
1. Voeg een AAAA Record toe met waarde 2a03:b0c0:2:f0::229:d001
1. Geef de URL en de naam van de Website op Argu aan ons door via info@argu.co.
