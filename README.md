JensenFlix

tips:
- tänk på att <input> och <button> inte ärver CSS för text, så som storlek, font, osv. detta måste anges manuellt igen i varje element.

använd "Semantic Commit Messages"
https://gist.github.com/joshbuchegia/6f47e86d2510bce28f8e7f42ae84c716 och https://www.conventionalcommits.org/en/v1.0.0-beta.2/ 
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
bakgrund: #19161c
tema: #512B81


# Grafisk Profil (Filmsida Jonatan)

## Färgval:
      Mörklila, lila och ljusblå är de dominerande färgerna, med inslag av vitt och nyanser av lila. Lila nyanser förknippas ofta med dramatik, lyx, premium, framgång och kreativitet. Den lila färgen skapar en stark identitet och ger en modern känsla, vilket ger en sofistikerad kontrast och bra läsbarhet. Blått är en väldigt populär färg i webbdesign och både blått och lila upplevs ofta som seriösa, trygga och lugnande.

## Typografi:
      Användningen av **Roboto** som huvudtypsnitt, med *sans-serif* som fallback, ger sidan en modern och ren känsla. Typsnittet är lättläst både på stora skärmar och mindre enheter, vilket förbättrar användarupplevelsen genom att säkerställa god läsbarhet.

## Bildmaterial:
      Bilder på filmerna är centralt placerade och användningen av affischer i bildkort ger en känsla av att bläddra i en digital videobutik. Detta gör sidan mer visuell och engagerande.

# UX-perspektiv (Användarupplevelse)

## Responsivitet:
      Designen är responsiv och anpassar sig väl till olika skärmstorlekar (desktop, tablet, mobil). På desktop finns en bredare grid-layout med fler filmer per rad, medan tablet och mobilversionerna smalnar av för att ge användaren en enkel skrollupplevelse. Detta säkerställer att användaren får en konsistent och lättnavigerad upplevelse oavsett enhet.

## Navigering:
      Tydlig navigering finns genom den horisontella menyn högst upp med en enkel och minimalistisk stil. På mobil och tablet ersätts den med en **hamburgermeny**, vilket är en vanlig praxis för att spara utrymme och göra gränssnittet mer renodlat.  
      En enkel sökfunktion samt filtrering baserat på "Genre" och "Sortera efter" hjälper användaren att snabbt hitta relevant innehåll, vilket förbättrar användarupplevelsen genom att minska tiden det tar att navigera genom stora innehållsbibliotek.

## Pagination:
      Paginering längst ner på sidan gör det lätt för användaren att navigera genom ett stort urval av filmer utan att överbelasta skärmen med för många objekt samtidigt. Tydliga pilar för att bläddra mellan sidor gör processen intuitiv.

## Användarinteraktion:
      Stora knappar med tydlig text (exempelvis "Ta del av erbjudandet" och "Läs mer") gör det enkelt att interagera med sidan. Att visa **betyg** på filmer direkt ger en användbar guide för snabbare beslut, vilket minskar kognitiv belastning för användaren.

# UI-perspektiv (Användargränssnitt)

## Grid-layout:
      På desktop används ett flerradigt grid-system för att maximera utrymmet och visa fler filmer samtidigt, medan på tablet och mobil visas färre element per rad för att anpassa sig till mindre skärmar och ge en mer användarvänlig vertikal upplevelse. Den enkla grid-layouten gör att sidan känns strukturerad och lätt att förstå visuellt.

## Horisontell och vertikal balans:
      Layouten är välbalanserad mellan horisontella och vertikala element. På desktop finns en tydlig sidomeny till vänster med profiler för skådespelare som medverkar i filmen man hovrar på (exempelvis **Ben Affleck** och **Henry Cavill**), vilket gör användarupplevelsen mer dynamisk. På mobil och tablet försvinner denna meny för att spara plats, vilket förbättrar den vertikala skrollupplevelsen.
