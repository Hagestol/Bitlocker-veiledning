<h1 class="no_toc">Innhold</h1>

* TOC
{:toc}

# Bitlocker Veiledning
> Bitlocker er bare på windows. Om du bruker mac eller et annet operativsystem, trenger du ikke lese videre.
> Om du har bitlocker aktivert, og du ikke har gjenoprettnings nøkkel, vil du miste alt innhold på pc dersom bitlocker går på.
> Bitlocker kan gå på av flere grunner som finnes på [Microsoft](https://learn.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-recovery-guide-plan#what-causes-bitlocker-recovery) sin guide. Bitlocker vil også alltid gå på om hovedkortet blir byttet ved reparasjon.

# Hva er fordelen med å ha bitlocker
>Bitlocker krypterer disken din som gjør det er umulig for andre å få tak i dine filer. Til og med Microsoft kan ikke få tak i innholdet på disken uten din bitlocker nøkkel. Med andre ord så er all din data sikker så lenge bitlocker er aktivert. (Bitlocker beskytter deg ikke fra virus den sikrer deg bare fra fysisk angrep på pc).

# Hvordan finne bitlocker nøkkel
>Det er flere metoder for å finne og ta vare på din bitlocker nøkkel. 

>Den første metoden er å gå inn på [Microsoft](https://account.microsoft.com/devices/recoverykey), hvor du kan logge deg på og se bitlocker nøkkelen. Om du ikke finner den, betyr det at din pc ikke har blitt satt opp med en microsoft konto, eller at bitlocker har blitt skrudd på i senere tid.

>Den andre metoden er å trykke på windows knappen og skrive "Administrer Bitlocker". Der finner du en knapp som heter "Sikkerhetskopier gjenopprettingsnøkkelen". Deretter vil du få fire valg om hvor du vil lagre din nøkkel.

![](https://cdn.discordapp.com/attachments/760864383931777074/1024608856959090749/unknown.png)

![](https://cdn.discordapp.com/attachments/760864383931777074/1024626550429192293/unknown.png)

>Her kan du velge "Lagre til Microsoft-kontoen" og da kan du finne den igjen [her](https://account.microsoft.com/devices/recoverykey), om dette ikke funker må du lagre nøkkelen på et annet sted. Om du velger å lagre nøkkelen på en annen måte er det viktig at du ikke mister denne, enten det er et ark eller en usb. Så lenge nøkkelen ikke ligger på microsoft kontoen, har du ingen mulighet for å hente denne nøkkelen andre steder en fra din pc, om bitlocker allerede har skrudd seg på, vil dette vere for seint.

>Den tredje metoden er å åpne cmd/ledetekst som administrator, deretter skriver du kommandoen ```manage-bde -protectors C: -get``` da vil du få opp bitlocker nøkkel som du ser på vedlagt bilde.

![](https://cdn.discordapp.com/attachments/760864383931777074/1024607462898282496/fghghhdtgethedtherth.png)

# Hvordan skru av bitlocker
