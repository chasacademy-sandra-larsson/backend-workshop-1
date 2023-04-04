
# Backendutveckling och API:er #1: Intro Node.js och Express  


👋 Se Linus Rudbecks föreläsning från 3 april ✅ 

### Innehåll denna workshop:

* Skriva Javascript i backend med Node.js 
* Använda ramverket Express
* Handlebars som view engine

### Redovisning:
* Du redovisar resultatet av övningarna

***Om du inte kan delta på workshopen, redovisar du ovanstående nästkommande workshop***



# 👩🏽‍💻 Övning 1: Läsa och skriva till fil 

Syftet med övningen är att använda Javascript i backend med Node.js genom att skriva och läsa till fil.

### Din uppgift

Du ska läsa ett antal tal från en fil, sedan sortera dem, för att sedan skriva de sorterade till en anna fil.

Använd fs-modulen och funktiorna ```readFile``` och ```writeFile``` för att läsa och skriva till fil. Se [https://nodejs.dev/en/learn/writing-files-with-nodejs/](https://nodejs.dev/en/learn/writing-files-with-nodejs/) 

**Obs!** I Node.js används require istället för import.

Du kör ett skript i Node.js med kommandot (här används alltså ingen browser 😃)

```
node din-fil.js
```

# 👩🏽‍💻 Övning 2: Intro till ramverket Express

För denna övning behöver du installera Express lokalt i mappen:

```
npm install express
```

Du ska skapa en webbserver med Node.js och Express som tar emot en begäran och skickar ett välkomstmeddelande ("Hello World"). D.v.s när använder besöker http://localhost:8000/ ska meddelandet skrivas ut i browsern.



# 👩🏽‍💻 Övning 3: Enkel filmsida med Express & Handlebars

För denna övning behöver du installera Express och Handlebars lokalt i mappen:

```
npm install express express-handlebars
```
Du ska skapa en enkel filmsida som listar dina topp 5 filmer. Sidan ska ha en layout med header, main och footer, där header och footer är partials i Handlebars.
Listan med dina topp 3 filmer ska hämtas från en text-fil och visas på url http://localhost:8000/my-movies.

Bilder och css-fil ska ligga under ```public``` och hämtas enligt [https://expressjs.com/en/starter/static-files.html](https://expressjs.com/en/starter/static-files.html)

Styla enligt egna preferenser.


# 💬 Diskutera

Diskutera med en klasskamrat/er. Vad finns det för fördelar att använda Javascript, Node.js och Express. Nackdelar? Sök även på nätet på alternativ på ramverk för serverprogrammering och diskutera dessa.
