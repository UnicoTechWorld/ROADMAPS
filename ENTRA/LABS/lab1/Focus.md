Identiteitsstructuur opzetten

Je maakt een duidelijke structuur van afdelingen:

Operations

Support

Finance

Marketing

Management

Voor elke afdeling wil de IT-manager:

Logische gebruikersaccounts (naming convention)

Security groups voor rechten op apps en data

Microsoft 365 Groups / Teams waar nodig

Basis van gebruikersbeheer verbeteren

Nieuwe gebruikers moeten volgens een vast patroon worden aangemaakt:

Juiste user principal name

Juiste display name

Juiste afdeling, functie, locatie

Gastgebruikers (freelancers, tijdelijke medewerkers) moeten duidelijk herkenbaar zijn.

Je moet een manier voorzien om snel per afdeling/locatie te zien wie waar hoort.

Licenties centraliseren met groepen

Contoso Mobility gebruikt ongeveer:

Microsoft 365 Business Premium

Microsoft 365 Apps for Business (voor sommige externen)

Nu zijn licenties één per één aangeklikt per gebruiker.

Jij moet een basis leggen voor group-based licensing:

1 of meerdere licentiegroepen per type medewerker

Koppeling tussen afdeling/functie en de juiste licentiegroep

Basisbeveiliging inschakelen voor aanmeldingen

Er is momenteel geen MFA of security defaults.

IT-manager wil in Phase 1 minstens dat:

MFA standaard verplicht wordt voor interne gebruikers

Self-service password reset actief is zodat de helpdesk minder tickets krijgt

Je moet kiezen:

Ofwel Security Defaults

Ofwel een eerste, eenvoudige eigen configuratie (MFA + SSPR) die nog niet te complex is

Rollen en verantwoordelijkheid duidelijk maken

Op dit moment logt de IT-manager als Global Administrator in voor alles.

Jij krijgt de opdracht om:

Jouw eigen account de juiste rol(len) te geven voor dagelijks beheer

Een scheiding te maken tussen “Global Admin” en “Helpdesk / User Admin” taken

Doel: zo min mogelijk dagelijkse taken via Global Admin, meer via beperkte rollen.

CONCREET WAT JE GAAT DOEN IN HET LAB (hoog niveau, nog niet de stappen):

Een “labzone” maken in je tenant:

Testgebruikers en testgroepen, duidelijk gelabeld als LAB_…

Gebruikersscenario’s uitwerken:

1 nieuwe medewerker in Support (voltijds, interne medewerker, krijgt Business Premium)

1 nieuwe medewerker in Marketing (deel van een extern bureau, moet alleen Teams en Office apps hebben)

1 manager in Operations die overal toegang toe moet hebben (incl. MFA, compliance zaken)

Groepen ontwerpen:

Per afdeling minstens één security group

Eén of meerdere licentiegroepen (bijvoorbeeld “LIC_M365_BusinessPremium_AllStaff”)

Licenties via groepen toewijzen aan je testgebruikers

MFA en SSPR activeren, en testen met minstens één testgebruiker

Rollen toekennen:

Eén account als Global Administrator (best bestaand)

Jouw lab-account als bijvoorbeeld User Administrator / Authentication Administrator (of iets gelijkaardig) om dagelijkse taken te doen

Doel van deze Phase 1-lab:

Jij begrijpt hoe je een tenant logisch structureert rond users, groups, licenties en basisbeveiliging.

Je kan later makkelijk uitbreiden naar:

Device identities

Conditional Access

Identity protection

Entra ID Governance, enz.
