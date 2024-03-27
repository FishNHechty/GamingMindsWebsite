# Dokumentation | Gaming Minds Studios | Website

Diese Dokumtation enthält die Analyse und Anmerkungen zu der Internetseite des Gaming Minds Studios und beschreibt die Umsetzung einer möglichen neuen und moderneren Seite. 

# Inhalt und Aufbau
> Aufbau | Inhalt | Grafische Darstellung

Die Seite stellt das Studio und deren Spiele, wie *Railway Empire 2, Port Royale 4* und *Grand Ages: Medieval*, vor und verweist zusätzlich auf den Shop, Jobs und das Impressum des Studios. Die Sprache ist hauptsächlich auf Englisch geschrieben. Erstellt wurde die Seite mit Wordpress. Das Logo befindet sich licks oben und auf der anderen Seite befindet sich ein Verweis auf die Facebookpage des Studios.
> [!NOTE]
> Die Seite ist zwar auf Englisch gehalten, jedoch wird im Code die Seite als Deustch ```<html lang="de-De">``` deklariert. Eine Möglichkeit die Sprache zu ändern gibt es nicht.

Seite nutzt drei verschiedene Grautöne für Banner, Navigationsleiste und Inhaltsboxen, um diese jeweils voneiander abzuheben
- ![#333333](https://placehold.co/15x15/333333/333333.png) `#333333` : Banner & Footer
- ![#222222](https://placehold.co/15x15/222222/222222.png) `#222222` : Navigationsleiste
- ![#1b1b1b](https://placehold.co/15x15/1b1b1b/1b1b1b.png) `#1b1b1b` : Inhaltsbox

Der Text ist weiß und *Open Sans* wird als Schriftart benutzt. 


## Startseite

Willkommensnachricht und Beschreibung des Studios. Vorschau von drei Spielen in Form der Cover, Titel und eine abgeschnittene Beschreibung.
Darunter finden sich Beschreibung und eine Auflistung der Features für das Spiel *Railway Empire 2* wieder. 

<img src="/Doc/WebsiteGMS.PNG" width="50%" height="50%">

> [!NOTE]
> Gamecover sind falsch ausgeschnitten, Port Royale 4 und Grand Ages: Medieval Titel sind nicht komplett zu sehen
> <img src="http://www.gamingmindsstudios.com/WordpressData/wp-content/uploads/2020/12/webheader_08122020-350x197.jpg" width="20%" height="20%">
> <img src="http://www.gamingmindsstudios.com/WordpressData/wp-content/uploads/2015/06/fheader_gradagesmedieval01-350x197.jpg" width="20%" height="20%">




## Games

Auflistung aller veröffentlichten Spiele des Studios
- Railway Empire 2
- Port Royale 4
- Railway Empire
- Grand Ages: Medieval
- Rise of Venice
- Port Royale 3
- Partician IV
- Dark Star One

Die Auflistung enthält ein quadratisches Cover des Spieles, rechts den Titel und darunter wieder eine abgeschnittene Beschreibung.

<img src="/Doc/WebsiteSpiel.PNG" width="50%" height="50%">

> [!NOTE]
> Cover, Titel und *Read...* verweisen auf das Spiel. Read wirkt sich besser auf vollen Kacheln/Cards aus, hier ist jedoch zu viel Platz vorhanden, als dass sich die Nutzung dessen als sinnvoll ergibt.
> 
> Durch die quadratischen Cover der Spiele *(200px x 200px)* wird, ausser durch das zentrierte Cover von Railway Empire 2, keines ordentlich dargestellt. Verdoppelt man min. die Breite der Cover, sind diese auch besser
> sichtbar und mehr freier Platz auf der Seite wird genutzt. 

## Jobs

Verweis für Stellenangebote auf die Internetseite der Kalypso Media Group, sowie der Hinweis auf die Filterung für die Orte Gütersloh und Paderborn. Desweiteren befindet sich rechts eine Suchleiste und ein Archiv mit zwei Einträgen.

<img src="/Doc/WebsiteJobs.PNG" width="50%" height="50%">

> [!NOTE]
> Suchleiste und das Archiv können entfernt werden, zumal das Archiv auf nicht nennenswerte Einträge führt. Man könnte auch darüber diskutieren ob die Seite nicht direkt auf Kalypso weiterleiten sollte, jedoch spricht der Hinweis auf die Filterung dagegen.
>
> Das gezeigte Bild erzeugt keinen Effekt, hier wäre jeweils ein Bild der Studios aus Gütersloh und Paderborn angebracht. 

## Shop

Außer der Headline Shop und einem Link befindet sich hier nichts.

<img src="/Doc/WebsiteShop.PNG" width="50%" height="50%">

> [!NOTE]
> Seite kann gelöscht werden. Direkte Weiterleitung spart Zeit.

## Impressum

Hier befindet sich das Impressum 

<img src="/Doc/WebsiteImprint.PNG" width="50%" height="50%">

> [!NOTE]
> Das Impressum kann im Footer verlinkt werden.

## Banner

Das Banner enthält das Logo des Studios und ein kleines Facebooklogo mit entsprechender Weiterleitung.  

<img src="/Doc/WebsiteBanner.PNG" width="50%" height="50%">

> [!NOTE]
> Banner ist viel zu hoch, die Generierung des Platzes ist unnötig. ```.wrapper {padding: 0 10px;}```


## Navigationsleiste

In der Navigationsleiste (im Code als Menu beschrieben) befinden sich | Games | Jobs and Internship | Shop | Imprint |. Hovert man über Games, so werden in einem Untermenü die acht Spiele präsentiert.

<img src="/Doc/WebsiteNav.PNG"> 

<img src="/Doc/WebsiteMenu.gif" width="10%" height="10%">

> [!NOTE]
> Rechts befindet sich die Möglichkeit auf der Internetseite nach Inhalten zu suchen, jedoch ist diese Option, aufgrund des geringen Umfangs, unnötig.

## Footer

Footer enthält typsiche Informationen und eine Verlinkung auf Catch Themes.

<img src="/Doc/WebsiteFooter.PNG">

> [!NOTE]
> Verlinkung Catch Themes kann gelöscht werden.

  
# Aufbau neue Seite

## Idee

Moderne und grafisch überarbeitete Website. Grafiken sollen die Spiele besser darstellen und durch Effekte überzeugen. Es orienert sich an den heutigen Standard andere Studios. 

## Startseite

Hier ein simples Konzept der neuen Hauptseite. Diese Seite ist simpel gehalten und enthält direkt die wichtigsten Informationen für den Besucher.
Oben befindet sich die neue schmallere Navigationsleiste, links mit dem Logo ohne blaue Schattierung, rechts Links für [SHOP] [JOBS] [GAMES] [KONTAKT]. Diese hebt sich mit der schwarzen Farbe komplett ab. 
Als Headline wird weiterhin der Willkommenstext und die Beschreibung genutzt, darunter befinden sich Cards für alle Spiele. Dies sorgt für eine verbesserte Übersicht der Inhalte für den Besucher. Die Seite schließt mit einem sehr simplen Footer ab, welcher nur die Links der Social Media Kanäle enthält. Benutzt werden dafür die weißen transparenten Logos. 

<img src="/Doc/new_frontpage.PNG" width="50%" height="50%">

> [!NOTE]
> Die Links von Shop und Jobs führen direkt auf die entsprechenden Seiten von Kalypso, um so unnötige Zeit zu sparen.

## Game | Am Beispiel von Railway Empire 2

Die Seite der Spiele wurde komplett überarbeitet. Begrüßt wird man mit dem einem großen Cover und der einer Ebene mit dem Logo und den Auszeichnungen. 
Scrollt man runter, findet man Informationsboxen über Ingamescreenshots, welche Texte und Bilder/Gifs entsprechend der Spiele enthalten.
Anschließend findet man unten die Links der jeweiligen Platformen für das Spiel (PC - XBOX - PS5 - PS4 - Nintendo Switch)

<img src="/Doc/rw4-full.png" width="50%" height="50%">

Desweiteren befindet sich in der Mitte der Navigationsleite ein Kaufbutton, der ein kleines Fenster öffnet, welches die Links der möglichen Spieleplatformen enthält. Ist das Fenster offen, wird der Hintergrund geblurrt. 

<img src="/Doc/popup.PNG" width="50%" height="50%">

## Details

Das Gaming Minds Logo passt sich den Spielen grafisch an:

<img src="Website/logorw.png" width="50%" height="50%"> / Railway Empire 2
<img src="Website/logo_pr4.png" width="50%" height="50%"> / Port Royale 4

# Code-Highlights 

Hier stelle ich Codesnippets aus dem Konzept vor, welche möglicherweise interessant und nennswert sind. 
Hauptsächlich wurde das Konzept in HTML und CSS geschrieben, aufgrund der geringen Zeit ist die "BugFix-Liste" und die "to do-Liste" noch sehr lang. Der Code ist noch weit von perfekt, trotzdessen möchte ich Ihnen diesen als Ansatz vorstellen. 

# Navigationsleiste

Die Navigationsleite ist wie folgt aufgebaut. 
HTML:
```
<div class="navbar">
      <a href="index.html"><img src="logoupdate.png" class="logo"></a>
            <nav>
                <ul>
                    <li><a href="https://www.kalypsomedia.com/de/games/">SHOP</a></li>
                    <li><a href="https://www.kalypsomedia.com/jobs">JOBS</a></li>
                    <li><a href="ganmes.html">GAMES</a></li>
                    <li><a href="contact.html">CONTACT</a></li>
                </ul>
            </nav>
        </div>
```

CSS:
```
.navbar{
    position: sticky;
    top: 0px;
    z-index: 100;
    padding-left: 10px;
    padding-right: 20px;
    height: 8%;
    display: flex;
    align-items: center;
    background-color: #000000;
}
.logo{
    width: 250px;
    cursor: pointer;
}
.menu-icon{
    width: 30px;
    cursor: pointer;
    margin-left: 40px;
}
nav{
    flex: 1;
    text-align: right;
}
nav ul li{
    list-style: none;
    display: inline-block;
    margin-left: 50px;
}
nav ul li a{
    text-decoration: none;
    color: white;
    font-size: 20px;  
}
nav ul li a:hover{
    color:rgb(161, 183, 223);
}
```
In .navbar wird die Position und die sich mitbewegenede Leiste deklariert. Die Leiste hat durch den ```z-index: 100;``` eine Priorisierung innerhalb der Seite, damit diese immer über den Elementen liegt.

Damit die Links keinen Unterstrich bekommen, nutze ich ```text-decoration: none;``` und ```nav ul li a:hover{color:rgb(161, 183, 223);}``` um die Textfarbe beim Hovern zu ändern. Damit verstärkt sich die Übersicht bei der Auswahl.

## Shop-Button

Der "Spiel holen" Button ist wie folgt implementiert:

HTML:

innerhalb der navbar:
```
<button class="bn632-hover port" onclick="toggle()">SPIEL HOLEN</button>
```
Das Popup-Fenster:
```
<div id="abfrage" class="popup">
  <img src="rw_logo.png" alt="RailwayEmpire2" class="rwlogo">
  <img src="close.png" alt="close" class="close" onclick="toggle()">
  <h2>wähle deine Platform</h2>
  <div class="plaformer">
    <a href="#" onclick="toggle()"><img src="PC.png" class="platform"></a>
    <a href="#" onclick="toggle()"><img src="xbox.png" class="platform"></a>
    <a href="#" onclick="toggle()"><img src="switch.png" class="platform"></a>
    <a href="#" onclick="toggle()"><img src="ps5.png" class="platform ps"></a>
    <a href="#" onclick="toggle()"><img src="ps4.png" class="platform ps"></a>
  </div>
</div>
```
CSS: 

```
.navbar .bn632-hover{
    position: absolute;
    left: 50%;
    transform:translateX(-50%);
}
.bn632-hover {  
    z-index: 3;
    width: 160px;
    font-size: 16px;
    font-weight: 600;
    color: #fff;
    cursor: pointer;
    margin: 20px;
    height: 55px;
    text-align:center;
    border: none;
    background-size: 300% 100%;
    border-radius: 50px;
    moz-transition: all .4s ease-in-out;
    -o-transition: all .4s ease-in-out;
    -webkit-transition: all .4s ease-in-out;
    transition: all .4s ease-in-out;
}
  
.bn632-hover:hover{
    background-position: 100% 0;
    moz-transition: all .4s ease-in-out;
    -o-transition: all .4s ease-in-out;
    -webkit-transition: all .4s ease-in-out;
    transition: all .4s ease-in-out;
}
  
.bn632-hover:focus{
    outline: none;
}
  
.bn632-hover.rail{
    background-image: linear-gradient(
      to right,
      #29323c,
      #485563,
      #2b5876,
      #4e4376
    );
    box-shadow: 0 4px 15px 0 rgba(45, 54, 65, 0.75);
}
.bn632-hover.port{
    background-image: linear-gradient(
      to right,
      #1c587c,
      #626348,
      #76682b,
      #545530
    );
    box-shadow: 0 4px 15px 0 rgba(45, 54, 65, 0.75);
}
```
Script:

```
function toggle(){
                var blur = document.getElementById('blur');
                blur.classList.toggle('active');
                var abfrage = document.getElementById('abfrage');
                abfrage.classList.toggle('active');
}
```

Erklärung: Hovert man mit der Maus über den Button, ensteht ein Farbwechsel. Die Farben jeweils für die enstprechenden Spiele farblich angepasst.

## GameCards

In der Hauptseite ist eine 2x4 Anlegung der Cards, mit entsprecheden Gamecover zu sehen. Hovert man über ein Spiel, vergrößert sich die Card. 

HTML:

```
<div class="cards">
  <a href="railwayempire2.html"><div class="card card1"></div></a>
  <a href="portroyale4.html"><div class="card card2"></div></a>
  <a href="grandages.html"><div class="card card3"></div></a>
  <a href="darkstarone.html"><div class="card card4"></div></a>
  <a href="riseofvenice.html"><div class="card card5"></div></a>
  <a href="portroyale3.html"><div class="card card6"></div></a>
  <a href="patricianIV.html"><div class="card card7"></div></a>
  <a href="railwayempire.html"><div class="card card8"></div></a>
</div>
```
Innerhalb der Div fungieren die Cards als Links.


CSS: 

```
.cards{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    margin-bottom: 20px;
    align-items: center;
}
.card {
    width: 430px;
    height: 200px;
    border-radius: 10px;
    padding: 15px 25px;
    box-sizing: border-box;
    cursor: pointer;
    margin: 10px;
    background-position: center;
    background-size: cover;
    transition: transform 0.3s;
    box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
}

.card:hover {
    transform: scale(1.03);
}
.card1{
    background-image: url(RailwayEmpire2.jpg);
}
.card2{
    background-image: url(PortRoyale4.jpg);
}
.card3{
    background-image: url(GandAgesMedieval.jpg);
}
.card4{
    background-image: url(DarkStarOne.jpg);
}
.card5{
    background-image: url(RiseOfVenice.jpg);
}   
.card6{
    background-image: url(PortRoyale3.jpg);
}
.card7{
    background-image: url(PatricianIV.jpg);
}
.card8{
    background-image: url(RailwayEmpire.jpg);
}
```
Vergrößerung der Cards: ```.card:hover {transform: scale(1.03);}```

# Bug-Fix & ToDo - Liste

- Die Seiten sollen sich der Skalierung der Monitore/Fenster anpassen - Hohe Prio
- Popup-Fenster soll schließen wenn onclick != abfrage ist  - Geringe Prio
- Platformlinks zentrieren - Mittlere Prio
- Container besitzt ein 4px padding-bottom, welches nie deklariert worden ist - Geringe Prio durch Workaround der Bilder
- Button scale fix
- Navbar verschwindet beim scrollen auf Games

- Mobile Support
- Restliche Seiten für die Spiele erstellen [Bisher: Port Royale 4 & Railway Empire 2]
- Contact erstellen
- UI für Games erstellen
- Animations 
