# Parliamo! 🇮🇹

En liten webbapp för att öva italienska genom vardagsdialoger.

## Användning

1. Välj **Restaurang**, **Affär** eller **Museum**.
2. Lyssna på personalens italienska replik och läs den svenska översättningen.
3. Läs ditt italienska svar högt, med svensk översättning som stöd.
4. Fortsätt med **Nästa replik** när du är redo.

Varje dialog har åtta utbyten. Du kan repetera uppläsningen, välja talhastighet och navigera bakåt. Appen använder ingen mikrofon och bedömer inte ditt uttal.

## Kör lokalt

Öppna `index.html` i webbläsaren. Ingen installation eller server behövs.

## GitHub Pages

Aktivera under **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root)**.

Publicerad adress: https://weehorse.github.io/Parliamo/

## Teknik

HTML, CSS och JavaScript utan externa beroenden. Uppläsning sker med webbläsarens Web Speech API (`speechSynthesis`). Tillgängliga italienska röster kan variera mellan enheter och webbläsare.
