# Returside for Enable Banking

Publiser `callback.html`, `index.html` og denne filen i roten av `Axel3121/Axel3121.github.io`. GitHub Pages kan publisere fra roten av standardgrenen. Returadressen som registreres hos Enable Banking er `https://axel3121.github.io/callback.html`.

Sjekk først at den nøyaktige adressen svarer direkte med HTTP 200 over HTTPS. Prøv deretter en syntetisk spørringsstreng som `?state=demo&code=demo` for å se at siden viser koden. Bruk bare oppdiktede verdier når du tester publiseringen.

Siden leser spørringsstrengen fra nettleserens adresse og viser feltene som tekst. Den har ingen skjemaer, eksterne ressurser eller nettverkskall. GitHub Pages mottar den første HTTPS-forespørselen med spørringsstrengen. Hold den virkelige returadressen og koden i nettleseren og den lokale terminalen.
