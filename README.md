JensenFlix

använd "Semantic Commit Messages"
https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716 och https://www.conventionalcommits.org/en/v1.0.0-beta.2/ 
t.ex. feat: (new feature for the user, not a new feature for build script)
      fix: (bug fix for the user, not a fix to a build script)

      commit -m "fix: (bug fix for the user, not a fix to a build script)"

vem som gör vad i baslayouten:
- hampus: navigationen
- axel: header & logga
- jonathan & roza: footer

vem som gör vilken sida: 
- registrering, inloggning och betalmetod: hampus
- förstasidan: axel
- lista med filmer: jonathan
- om oss & kontakta oss: roza

sidor som ska göras: förstasidan, sida med lista över filmer

färgschema: https://colorhunt.co/palette/2e073f7a1cacad49e1ebd3f8
bakgrund: 2E073F
tema: 7A1CAC


Nedanför kommer en delbeskrivning av projektet

Har skapat en navigation bar och sidor för att logga in och registrera användare. 

Till navigation baren började jag med placering av alla länkar med hjälp av grid-template columns, men det dök upp en del problem med placering av alla länkar, som hamnade lite tokigt. När jag ändrade det till flex och det löste problemen. 

Login och registrera knapparna är placerade längst till höger på navbaren eftersom det är lättåtkomligt och enkelt för de flesta användare att hitta. Användaren söker sig oftast naturligt längst upp till höger för att hitta till de sidorna.

“JensenFlix” logon figurerar som en logo och länk på navbaren, och den är placerad längst till vänster. Det är en av de vanligaste layouten där företagets logo “presenterar” resten av sidan. Majoriteten av befolkningen läser en sida uppifrån och ner, vänster till höger. Därför är det rimligt att företagets logo är det första man ser. På motsatt sida är en viktig funktion, alltså login / registrera. 

Olika spalter för Filmer/Serier/Sport är placerade i mitten av navbaren. Navbaren innehåller bland de viktigaste sakerna som användaren vill åt, därför är de länkarna placerade där. 

Har vidare byggt på layout och styling för sidorna för inlogg och registrering. 

/Hampus 