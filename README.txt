Inlämningsuppgift 2 - Grupp: Marcus Rosin Lindberg, Linus Hammarberg

Hemsidan vi skapade: www.4chan.org, https://boards.4channel.org/g/

Vi valde sidan då vi ville ha en utmaning kring layout, eftersom de flesta moderna sidor för företag eller där
det erbjuds tjänster ser väldigt likadana ut. Med en Forum-sida behöver vi lägga fokuset på en textruta, utan att 
göra det klottrigt eller för tomt.

Vi har använt två olika metoder för att skapa vår layout. Då grundhemsidan inte hade varken flexbox eller någon
annan igenkännbar struktur. Home-page är strukturerad med hjälp av flexbox och float, medan board-sidan är uppbyggd 
med hjälp av bootstrap.

Vi stötte inte på några problem under vår första uppbyggnad av hemsidan, men när vi skulle lägga till en aside
och en karusell på home-page så blev det problem med formatteringen. Vi fick därför börja om från början och justera
width, height, margins osv. Detta gjorde att vår kod blev mer enhetlig och mer förståerlig än tidigare.
Då vi bytte från individuella element-styling till en enhetlig glass med övergripande kod.

Vi använde en klass för alla "headers" för divarna som heter .title, för att kunna iterera mellan våra divar.

Den största problematiken var att byta mindset från att skapa en snygg sida, till att skapa något som faktiskt
skulle fungera som ett forum. Vi fokuserade därför på att skapa en home-page som navigerar användaren in på en board
så fort som möjligt, och lät den övergripande board-menyn ligga kvar. 

En annan avgränsning vi valde att göra var att inte innefatta content som var klassad NSFW. Vilket är varför vår
board-list är kortare än grundhemsidans. Mycket av det innehållet vi lagt till är inte funktionellt i dagsläget
då det hade krävt att vi skapade fler än 2 sidor, och använde oss av scripts, som vi inte lärt oss ännu.

Vi lade inget tryck på funktionalitet på sidan, utan fokuserade på "förväntad" funktionalitet. Knappar, searchbars
och sidebars har intentionen att vara funktionella.

OBS: Vårt form-element använde vi för att skapa vår search-bar då det inte fanns någon annan stans att skapa det.
Då animationer inte heller kände sig passa på hemsidan har vi lagt in en fade-in animation på loggan när sidan
laddar in. Det blev något litet då det egentligen inte kändes bra att ha med i första taget men var på betygskrav.
