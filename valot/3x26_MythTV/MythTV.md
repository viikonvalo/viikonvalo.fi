<!--
Title: MythTV
Week: 3x26
Number: 130
Date: 2013/06/23
Pageimage: valo130-mythtv.png
Tags: Linux,Windows,Mac OS X,FreeBSD,Video,Mediakeskus,Multimedia,Televisio,Elokuva
-->

**MythTV on avoimen lähdekoodin digitaalinen videotallennin (DVR) ja
kodin mediakeskus.**

![](images/valo130-mythtv.png "fig:valo130-mythtv.png") MythTV on monipuolinen
ja lisäosilla laajennettava kodin mediakeskus. MythTV:n valikko-ohjattu
käyttöliittymä on peruskäytössä selkeä ja vaivaton. Sillä onnistuu
toisaalta suorien televisiolähetysten seuranta ja toisaalta
tv-tallenteiden tai muualta tuotujen mediatiedostojen toistaminen. Sitä
voi käyttää musiikki- ja videotiedostojen toistamiseen, CD-, DVD- ja
BlueRay-levyjen toistoon, kuvagallerioiden näyttämiseen sekä
nettivideoiden, esimerkiksi Youtube-videoiden, toistamiseen.

MythTV tukee hyvin erilaisia kaukosäätimiä ja sen perustoiminnot on
mahdollista ohjelmoida kaukosäätimen nappuloihin haluamallaan tavalla.
Käyttöliittymän toimintoja on kytketty myös useisiin näppäimistön
näppäimiin ja esimerkiksi jonkinlaisen mininäppäimistön käyttäminen
voikin olla hyvä ajatus.

Suoraa televisiolähetystä katsottaessa MythTV tallentaa ohjelmaa aina
automaattisesti kiintolevylle. Näin ohjelman voi halutessaan pysäyttää
jääkaappikäynnin ajaksi taikka pomppia ohjelmassa taaksepäin, jos jonkin
kohdan haluaa nähdä uudelleen. Automaattiset live-tallennukset
poistetaan automaattisesti tilantarpeen mukaan. Televisiokanavia voi
selata suoraan numeronäppäimillä, nuolinäppäimillä sekä aikajanana
näytettävää ohjelmaopasta käyttäen. Televisio-ohjelmien tallennuksia voi
ajastaa monella tapaa, esimerkiksi ohjelmaoppaasta valitsemalla taikka
tekstihakuja asettamalla. MythTV pitää tallenteiden, mediatiedostojen ja
ohjelmaoppaan metatiedot järjestyksessä tallentamalla ne tietokantaan,
jonka ansiosta niitä on helppo hakea.

MythTV:n rakenne on joustavasti asiakas-palvelin -mallin mukainen.
Toisin sanoen MythTV sisältää erillisen taustaohjelmiston, joka
huolehtii tv-virittimistä, ohjelmien tallentamisesta ja tallenteiden
hallinnasta, sekä erillisen edustaohjelmiston, joka toimii
käyttöliittymänä ja toistaa taustaohjelmiston tarjoilemat
mediatiedostot. Käytännössä tämä jako tarkoittaa sitä, että
taustaohjelmisto voi olla asennettuna yhdelle tai useammalle erilliselle
koneelle, jotka keskittyvät vain sisällön tarjoilemiseen, ja
edustaohjelmisto voi olla asennettuna yhteen tai useampaa
katselulaitteeseen. Näin aina päällä oleva taustaohjelmistoa käyttävä
laite on mahdollista laittaa toimimaan varastossa tai jossain muussa
piilossa, jossa se on mahdollisimman vähän häiriöksi, ja jättää vain
sirommat edustalaitteet esille esimerkiksi olohuoneeseen. Edusta- ja
taustaohjelmistoja on toki mahdollista käyttää myös samalla laitteella.
Android- ja iOS-laitteille löytyy myös sovelluksia, joita voidaan
käyttää joko kaukosäätiminä taikka katselulaitteina.

MythTV osaa käyttää alustan, esimerkiksi Linuxin, tukemia
viritinkortteja, jotka voivat olla joko sisäisiä tai usb-liittimellä
kytkettäviä laitteita. Yhdellä virittimellä voi katsoa ja tallentaa
yhtäaikaisesti yhdestä kanavanipusta tulevia ohjelmia. Näin esimerkiksi
YLE:n kanavanipusta voi saman aikaisesti tallentaa yhdeltä kanavalta ja
katsoa ohjelmaa toiselta. Useammalla virittimellä yhtä aikaa
käytettävien kanavanippujen määrä kasvaa.

MythTV on laajennettavissa erilaisilla lisäosilla ja teemoilla. Siihen
löytyvät erilliset lisäosat esimerkiksi musiikin ja videotiedostojen
toistamiseen, kuvien näyttämiseen, optisten medioiden käsittelyyn,
nettivideoiden selaamiseen, hakuun ja näyttämiseen sekä tallenteiden
muuttamiseen kannettaviin laitteisiin sopivaan muotoon. MythTV:n ulkoasu
puolestaan on monipuolisesti muokattavissa erilaisilla teemoilla, jotka
muuttelevat valikkotekstien sijainteja, taustakuvia ja muuta ohjelman
yleisilmettä. MythTV:n toimintoja voi käyttää myös Mythweb-lisäosan
tarjoaman webkäyttöliittymän kautta. Muita MythTV:n lisäosilla saatavia
ominaisuuksia ovat muun muassa rss-syötteiden lukija, säätiedotukset
sekä ZoneMinder-valvontakameroiden käyttö.

MythTV:n ympärille on koostettu kokonaisia Linux-jakeluita, joista
[Mythbuntu](http://www.mythbuntu.org/) on ehkä tunnetuin ja suosituin.
Mythbuntu tarjoaa helpon tavan asentaa kokonainen toimiva
MythTV-järjestelmä. Mythbuntu sisältää yksinkertaiset käyttöliittymät
ohjelman asetusten tekemiseen mahdollisimman helposti.

Kotisivu
:   <http://www.mythtv.org/>

Lisenssi
:   [GNU GPL](GNU_GPL)

Toimii seuraavilla alustoilla
:   Linux, FreeBSD, Mac OS X, Windows

Asennus
:   MythTV löytyy useimmille Linux-jakeluille suoraan
    paketinhallinnasta. Helpointa asentaminen on käyttämällä erityisesti
    MythTV:n käyttöä varten tehtyä jakelua, kuten
    [Mythbuntu](http://www.mythbuntu.org/). Muille alustoille MythTV
    löytyy sen kotisivujen kautta joko valmiina pakettina tai
    lähdekoodina. Windows-ympäristöön ei valitettavasti ole tarjolla
    valmiita suoritettavia ohjelmia vaan MythTV pitää kääntää sille
    lähdekoodeista.

<div class="psgallery" markdown="1">
-   [MythTV:n päävalikko suomenkielisenä ja selkeällä
    käyttöliittymäteemalla.](images/mythtv-1.png)
-   [Suoran televisiolähetyksen katselua. Ylös ja alas nuolilla
    selaamalla voi etsiä haluamansa kanavan ja valita sen OK- tai
    enter-näppäimellä.](images/mythtv-2.png)
-   [Ohjelmaoppaan nurkassa näytetään suoran lähetyksen kuva ja eri
    kanavien ohjelmistoa voi selata eteen- ja taaksepäin. Ohjelmien
    ajastaminen onnistuu tästä näkymästä halutut ohjelmat
    merkitsemällä.](images/mythtv-3.png)
-   [Ohjelmia voi merkitä myös toistuviksi tallennuksiksi. Samalla
    hakuajastimella tallennetut ohjelmat ovat selattavissa samasta
    katselunäkemästä.](images/mythtv-4.png)
-   [MythMusic-lisäosalla voi kuunnella musiikkia ja luoda
    musiikkitiedostoista soittolistoja.](images/mythtv-5.png)
-   [Nettivideoita voi etsiä valituista videopalveluista hakusanoilla ja
    valita hakutuloksista katsottavaksi.](images/mythtv-6.png)
-   [Mediakirjasto-valikosta ovat katsottavissa ja kuunneltavissa
    tv-tallenteet, videotiedostot, musiikit, Internet-videot ja
    kuvagalleriat.](images/mythtv-7.png)
-   [MythTV:n ulkoasu on valittavissa useista
    teemoista.](images/mythtv-8.png)
-   [Mediakirjasto-valikko toisella teemalla.](images/mythtv-9.png)
-   [Kuvagallerian kuvat ovat selattavissa
    kansioittain.](images/mythtv-10.png)
</div>

*Teksti: Pesasa* <br />
*Kuvakaappaukset: Pesasa*

