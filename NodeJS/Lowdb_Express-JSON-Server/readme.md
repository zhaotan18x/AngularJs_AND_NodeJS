<H2> NodeJS Lowdb JSON serveri 6.7.2021</H2>

Operaatiossa:: yritettään kuin terminaalissa/komento lähteessä antaa jokin komento, että kirjataan jokinlainen muistiinpanno(note) ylös, että uuden (note) jälkeen muodostuu aina uusi id sille. Kuin oma viesti, ja sillä on oma id.


Tää on tooi npm paketin "lowdb" mikäli oli edellisen swagger-routesmehod ohjelman toiminta, mitä lukaisee olemassa olevan json tiedoston. Ja sisältyy muutama paketti, mitä voidaan kuin editoita sitä olemassa sisäisen json tiedoston toiminnan. 

Tässä kehityspalvelimen määrittyksessä on, tärkeimmät muutama kokoonpanno lataukset paketit. Kun terminaalissa annetaan lataus "npm install <package-name".

<b>
Muutama tärkeät pakeit:<br>
<br>
- lowdb : datan varastointi <br> 
- morgan : pyyntojen vastaanotto <br>
- nanoid : tunnuksen/id luomiseen <br>
- cors : alkuperäisen välisen politiikan laatimiseksi. <br>
</b>
<br>

Ennen sitä pitää antaa terminal (komentolähteeseen) mitä npm pakettia pitää ladata. 
NPM on pakettihallintaohjelmisto javascriptiin varten.npm on JavaScript-ajonaikaisen ympäristön Node.js paketin oletushallinta. Se koostuu komentoriviasiakkaasta, jota kutsutaan myös nimellä npm, ja online-tietokannasta julkisista ja maksetuista yksityisistä paketeista, nimeltään npm-rekisteri. Rekisteriin pääsee asiakkaan kautta, ja saatavilla olevia paketteja voi selata ja hakea npm-verkkosivuston kautta.
<br>
Tässä on jotakin toimintoja RESTful juttuja eli (GET, PUT, DELETE & POST) tekijöitä, mitä jokaisella on oma toiminta ominaisuus. Tässä sovelluksessa käytettään vain perus terminaali komentolähdettä CMD:tä, että mitä haluttaan kuin tehdä. Ennen sitä pitää tehdä JavaScript toiminta asetukset, jotta CMD:tä kuin ymmärtäisi sen asetuksen parametrin/methodin. 

<br>
Käynnistä ensin tämä nodejs sovellus pyörimään ensin, ja minkä jälkeen käyttäjä avaa terminaalissa/shell:ssä, mitä tapahtuu pari komentoa.

Tämä kuin luo pienen viestin tai muistion ensimmäisenä, sekä pitää olla tarkana noiden merkien kanssa, ja lopussa pitää määrittää TÄSMÄLLEEN sama portti mikäli käynnistettiin tätä nodejs sovellusta;;
curl --header "Content-Type: application/json" --request POST --data '{"text" : "moi miten meenee?"}' http://localhost:8080/notes/new

Viimeisenä kuin toistettan niitä kaikkia viestejä mitä kirjoitettiin edellisen kommenon mukaan. Koska jokaisen viesti tallentuvat suoraan kohti kuin tietokannan json:lle;;
curl http://localhost:8080/notes

vaihtoehtoisena on avatta uusi ikkuna, ja toistaa tämän json tietokannan datan, mutta lopussa pitää lisätä ( /notes) , koska tälle polulle määritettiin toiminta, että toistaa json sisäisen datan. Kuten;; https://AlertYellowishPhp.zhaotan18x.repl.co/notes

<b>API json inside of the files</b><br>
<b>Example before </b>
![Alt text](images/NodeJS-1.PNG?raw=true "None") <br>

<b>Example after </b>
![Alt text](images/NodeJS-2.PNG?raw=true "None") <br>


<b>Commands / Shell operations </b><br>
First one is like give a some of note, then it will success <br> 
Second one is replay it, but it will show all inside of json notes anyway <br>
![Alt text](images/NodeJS-3.PNG?raw=true "None")
