---


---

<h1 id="cseresznye_q8e6ez">Cseresznye_Q8E6EZ</h1>
<p>Név: Hodosi Veronika<br>
Neptun: Q8E6EZ</p>
<h2 id="projekt-rövid-leírása">Projekt rövid leírása</h2>
<p>A Genshin Impact nevű játéknak készített saját adatbázisnak készítettem egy weboldalt, ahol lehet listázni a karaktereket, és azokat lehet hozzáadni (index.html). A forms-ban lehet szintén látni a karaktereket egy DataGridView-ban, és oldalt két ListBoxban vannak felsorolva az elemek és régiók.</p>
<h1 id="saját-adatbázis">Saját adatbázis</h1>
<p><img src="https://i.imgur.com/PKIsLUW.png" alt="Azure-ban készített kép a saját adatbázisról"></p>
<ul>
<li><code>3x1p</code> Az alkalmazásban használt táblánként pont (például a GVersion, Element és Region táblák)</li>
<li><code>1x1p</code> Az adatbázis tartalmaz Constraint-eket (min 2)</li>
<li><code>1x1p</code> Az adatbázis adatainak forrásmegjelölése:<br>
A Microsoft SQL Server Management Studio-ban készítettem. Az első  három  tábla (Element, Gversion, Region) adatát Genshin Impact hivatalos  oldaláról, illetve a játék Wiki oldaláról  szereztem.<br>
<a href="https://genshin.hoyoverse.com/en/map?region=0">https://genshin.hoyoverse.com/en/map?region=0</a><br>
<a href="https://genshin-impact.fandom.com/wiki/Version">https://genshin-impact.fandom.com/wiki/Version</a><br>
<a href="https://genshin.gg/elements/">https://genshin.gg/elements/</a><br>
A másik  két  tábla (Character, Weapon) adatát a ChatGPT-vel generáltam. A Character táblában a karakterek, a Weapon táblában a fegyverek, GVersion  táblában a verziók, Element táblában  az  elemek  és  végül a Region táblában a régiók  kérdezhetők le.</li>
<li><code>1x2p</code> Az adatbázis saját Azure SQL szerveren van</li>
</ul>
<h5 id="részösszeg-7pt">Részösszeg: 7pt</h5>
<h2 id="egyéb-extra">Egyéb, extra</h2>
<ul>
<li><code>2x1p</code>  <code>Scaffold-DbContext</code> használata<br>
<img src="https://i.imgur.com/yUqCcok.png" alt="ASP.NET Scaffold"><img src="https://i.imgur.com/pTtunwy.png" alt="Forms Scaffold"></li>
</ul>
<h5 id="részösszeg-2p-összesen-9p">Részösszeg: 2p, Összesen: 9p</h5>
<h2 id="asp.net"><a href="http://ASP.NET">ASP.NET</a></h2>
<ul>
<li>
<p><code>1x2p</code>  <code>program.cs</code> beállítása <code>wwwroot</code> mappában tárolt statikus tartalmak megosztására<br>
<img src="https://i.imgur.com/0z85XjX.png" alt="app.UseStaticFiles();"></p>
</li>
<li>
<p><code>1x3p</code> Teljes SQL tábla adatainak szolgáltatása API végponton keresztül<br>
<img src="https://i.imgur.com/AggkFzM.png" alt="Teljes SQL tábla"></p>
</li>
<li>
<p><code>2x2p</code> SQL tábla egy választható rekordjának szolgáltatása API végponton keresztül<br>
<img src="https://i.imgur.com/NLgnzx8.png" alt="Választható rekord CH"><img src="https://i.imgur.com/el7cRcI.png" alt="Választható rekord W"></p>
</li>
<li>
<p><code>1x3p</code> SQL tábla egy választható rekordjának törlése<br>
<img src="https://i.imgur.com/jizBizu.png" alt="Törlés"></p>
</li>
<li>
<p><code>1x5p</code> Új rekord felvétele <code>HttpPost</code> metóduson keresztül SQL táblába</p>
</li>
<li>
<p><code>2x3p</code> Rekord módosítása <code>HttpPost</code> metóduson keresztül SQL táblában<br>
<img src="https://i.imgur.com/zFQPdBM.png" alt="Felvétel, módosítás CH"><img src="https://i.imgur.com/3z1VXYy.png" alt="Felvétel, módosítás W"></p>
</li>
</ul>
<h5 id="részösszeg-23p-összesen-32p">Részösszeg: 23p, Összesen: 32p</h5>
<h2 id="weboldal">Weboldal</h2>
<ul>
<li><code>1x1p</code> A weboldalnak van egy értelmezhető struktúrája<br>
<img src="https://i.imgur.com/RwkWHvk.png" alt="Struktúra">Legelöl lehet hozzáadni egy új karaktert, utána a karaktert lehet listázni táblában</li>
<li><code>1x1p</code> A weboldal dinamikus tartalommal tölthető fel adatbázison keresztül</li>
<li><code>1x1p</code> A weboldal javascriptet használ API végpont által szolgáltatott adatok betöltésére, hozott anyagként<br>
<img src="https://i.imgur.com/xZXj7vU.png" alt="Adatok betöltése"></li>
<li><code>1x1p</code> A weboldal javascriptje más funkciót is ellát, mint az adatok betöltése: új karakter hozzáadása<br>
<img src="https://i.imgur.com/cO2V00y.png" alt="Új karakter"></li>
<li><code>1x1p</code> A weboldal használ legalább 20 sor értelmes css-t<br>
<img src="https://i.imgur.com/qmqx0f8.png" alt="CSS"></li>
</ul>
<h5 id="részösszeg-5p-összesen-37p">Részösszeg: 5p, Összesen: 37p</h5>
<h2 id="windows-forms-application">Windows Forms Application</h2>
<h3 id="user-interface">User Interface</h3>
<ul>
<li><code>1x2p</code> <strong>Anchorok alkalmazása</strong>: az alkalmazás egészében meg van oldva, hogy az ablak átméretezésekor ki legyen használva a rendelkezésre álló terület.<br>
<img src="https://i.imgur.com/iTtFWgY.png" alt="ListBox Anchor"></li>
</ul>
<h5 id="részösszeg-2p-összesen-39p">Részösszeg: 2p, Összesen: 39p</h5>
<h3 id="tábla-adatainak-megjelenítése-listbox-ban.">Tábla adatainak megjelenítése <code>ListBox</code>-ban.</h3>
<ul>
<li><code>1x2p</code> Adatok  megjelenítése (Element, Region)</li>
<li><code>2x2p</code> Ha az adatok tetszőleges módszerrel, pl. <code>TextBox</code>-on keresztül szűrhetőek.<br>
<img src="https://i.imgur.com/YY3Nlse.png" alt="Kód"><img src="https://i.imgur.com/PmP1ev5.png" alt="Form"></li>
</ul>
<h5 id="részösszeg-6p-összesen-45p">Részösszeg: 6p, Összesen: 45p</h5>
<h2 id="tábla-adatainak-megjelenítése-datagridview-ban">Tábla adatainak megjelenítése <code>DataGridView</code>-ban</h2>
<ul>
<li><code>1x2p</code> Adatok  megjelenítése<br>
<img src="https://i.imgur.com/TKT82MI.png" alt="Kód"><img src="https://i.imgur.com/WKCqrPu.png" alt="Form"></li>
</ul>
<h5 id="részösszeg-2p-összesen-47p">Részösszeg: 2p, Összesen: 47p</h5>
<h2 id="adatkötés-bindingsource--on-keresztül">Adatkötés <code>BindingSource</code> -on keresztül</h2>
<ul>
<li><code>1x2p</code> Működő  <code>BindingSource</code></li>
<li><code>3x1p</code> Egy <code>BindingSource</code>-ra egy gyűjemény megjelenítésére alkalmas vezérlő (ListBox, ComboBox, DataGridVIew) mellett más adatkötött vezérlő is van kötve, mint <code>TextBox</code>, <code>DateTimePicker</code>, <code>ComboBox</code> idegen kulcs értékének beállítására, stb.<br>
<img src="https://i.imgur.com/wRH9eQj.png" alt="TextBox"></li>
</ul>
<h5 id="részösszeg-5p-összesen-52p">Részösszeg: 5p, Összesen: 52p</h5>
<h1 id="összesen-52p">Összesen: 52p</h1>

