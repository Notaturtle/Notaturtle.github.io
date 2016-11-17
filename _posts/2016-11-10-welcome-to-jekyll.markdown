---
layout: post
comments: true
title:  Questions
date:   2016-11-10 15:42:24
categories: jekyll update
---
- What do you think of pre-compiling your CSS?
<br>
    Jag tyckte det var svårt att hålla koll på var allt låg, men det berodde nog mest på att jag själv inte skrev allt. Det är svårt att veta vart något ligger när jag själv inte gjort det tycker jag.

  A - Compare to regular CSS
  <br>
        Lite enklare att navigera i, men det beror på att jag är ovan med pre-compiling css. Allt som behövdes förrut var ett css dokument med allt i.

  B - Which techniques did you use?
  <br>
      SASS

  C - Pros and cons?
  <br>
        Fördelarna är att koden går att ärva så man inte behöver upprepa sig. Det ska även vara enklare att navigera i css koden, men jag har som sagt lite problem med det och jag vet inte om det beror på att jag själv inte skrivit all kod eller inte. Den enda nackdelen som jag kan komma på är debugg. Det borde var aganska svårt att debugga en kod om det finns fler apotentiella filer där det kan ligga i.

- What do you think of static site generators?
<br>
    När de används rätt så är dem bra. Om vi tar en webbplats för sociala medier så vill användaren kanske inte uppdatera sitt flöde hela tiden så där är det antagligen bättre och mer användarvänligt med en dynamiskt webbplats. Men i detta fall när vi bara har en blogg så är det nog fördelaktigt med en statisk webbplats.

    - What type of projects are they suitable for?
    <br>
        Webbplatser som inte använder sig av ett flöde som måste uppdateras hela tiden till exempel. Ett bra exempel på något som det skulle passa till är som sagt vår blogg. Där har vi en global navigering med samma design hela tiden. Det finns ingen mening med att göra den dynamisk för det kommer ändån inte hända något förens ägaren väljer att lägga in ett nytt blogginlägg.  
<br>
- What is robots.txt and how have you configure it for your site?
<br>
    Detta ger en introduktion om webbplatsen för webb-robotar. Så om en robot vill besöka webbplatsen så kollar den först i robots.txt filen för att hittar
    <br>
    User-agent: *
    Disallow: /
    <br>
    och detta att inte besöka några sidor på denna webbplats.

- What is humans.txt and how have you configure it for your site?
<br>
    Det är en textfil som innehåller information om skaparen/skaparna. Det kan även finnas allmän information om webbplatsen, ex när den uppdaterades.

- How did you implements comments to blog posts
<br>
    I uppgiftsbeskrivningen hänvisade kursledningen till en webbplats vid namn Disqus som hade skapat ett fungerande tema för just kommentarsfälten. Det enda som krävdes för att kunna använda sig av det var att skriva in ett simpelt kodstyckesom är följande: comments: true. Detta kodstycke gör antagligen det möjligt att kommentera skulle jag gissa på.

- What is Open Graph and how do you make use of it?
<br>
    Det gör det möjligt att kommentera på en webbplats utan att behöva skapa ett account. Du som användare loggar helt enkelt in via facebook och kan sedan skriva kommentarer på ett flertal webbplatser.


[jekyll]:      http://jekyllrb.com
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-help]: https://github.com/jekyll/jekyll-help
