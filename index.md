<h1 class="no_toc">Table of contents</h1>

* TOC
{:toc}

# Bitlocker Veiledning
> Bitlocker er bare på windows. Visst du bruker mac eller et annet operativsystem, trenger du ikke lese videre.
> Om du har bitlocker aktivert, og du ikke har gjenoprettnings nøkkel, vil du miste alt innhold på pc dersom bitlocker går på.
> Bitlocker kan gå på av flere grunner som finnes på [Microsoft](https://learn.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-recovery-guide-plan#what-causes-bitlocker-recovery) sin guide. Bitlocker vil også alltid gå på om hovedkortet blir byttet ved reparasjon.

# Hva er fordelene med å ha bitlocker

# Hvordan finne bitlocker nøkkel
>Det er flere metoder å finne og ta vare på din bitlocker nøkkel. 

>Den første metoden er å gå inn på [Microsoft](https://account.microsoft.com/devices/recoverykey), hvor du kan logge deg på og se bitlocker nøkkel. Om du ikke finner den, betyr det at din pc ikke har blitt satt opp med en microsoft konto, eller at bitlocker har blitt skrudd på i senere tid.

>Den andre metoden er å trykke på windows knappen og skrive "Administrer Bitlocker". Der finner du en knapp som heter "Sikkerhetskopier gjenopprettingsnøkkelen". Deretter vil du få fire valg om hvor du vil lagre din nøkkel.

>Den tredje metoden er å åpne cmd/ledetekst som administrator, deretter skriver du kommandoen ```manage-bde -protectors C: -get``` da vil du få opp bitlocker nøkkel som du ser på vedlagt bilde.
![](https://www.top-password.com/blog/wp-content/uploads/2018/10/find-bitlocker-recovery-key-from-cmd.png)

# Hvordan skru av bitlocker
