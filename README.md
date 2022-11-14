# witryny
HTML - HyperText Markup Language (hipertekstowy jezyk znacznikow ktory pozwala na wyswietlanie stron internetowych)<br>
HyperText - text z hiperłączmi do innych linków<br>
MarkUp - znacznik<br>
Doena - nazwa (github.com/LukaszButurla)<br>
Hosting - serwer z plikami stron WWW<br>
Link - zmieniony adres ip strony <br>
HTML 4 vs XHTML vs HTML 5<br>
Deprecated - przestarzale <br>
JavaScript - jezyk programowania stron<br>
CSS - Cascading Style Sheets<br>
<br>
<h1>znacznik "<.h1>...<./h1>"</h1>
<.html lang="pl"> - kodowanie z polskimi znakami 
<.meta charset="UTF-8"> - kodowanie z polskimi znakami
<.html>...<./html> - poczatek i koniec dokumentu html<br>
<.head>...<./head> - poczatek i koniec naglowka html<br>
<.body>...<./body> - poczatek i koniec zawartosci dokumentu html<br>
<.br> - znak nowej lini<br>
<.p>...<./p> - poczatek i koniec paragrafu<br>
<.b>...<./b> - pogrubienie<br>
<.i>...<./i> - pochylenie <br>
<.h1>...<./h1> - naglowek 1 stopnia<br>
<.h2>...<./h2> - naglowek 2 stopnia<br>
<.h3>...<./h3> - naglowek 3 stopnia<br>
<.h4>...<./h4> - naglowek 4 stopnia<br>
<.h5>...<./h5> - naglowek 5 stopnia<br>
<.h6>...<./h6> - naglowek 6 stopnia<br>
<.body bgcolor="red"> - kolor tla strony (nie uzywac w html5)<br>
<.hr> linia horyzontalna <hr><br>
<.strong> pogrubiony tekst, tak samo jak <.b><br>
<.em> pochylony tak samo jak <.i><br>
<.small...<./small> zmniejszanie tekstu<br>
<.mark>...<./mark> - wyroznienie tekstu<br>
<.sup>...<./sup> - indeks gorny<br>
<.sub>...<./sub> - indeks dolny<br>
<.s>...<./s> - przekreslenie tekstu<br>
<.del>...<./del> - przekreslenie - zostalo usuniete ze strony<br>
<.ins>...<./ins> - fragment dodany do poprzedniego tekstu<br>
<.ol>...<./ol> - poczatek i koniec uporzadkowanej listy<br>
<.ul>...<./ul> - poczatek i koniec nieuporzadkowanej listy<br>
<.li>...<./li> - element listy<br>

<ol>
  <li>jeden</li>
  <li>tak</li>
  <li>trzy</li>
</ol>

<.dl>...<./dl> - poczatek i koniec listy definicji<br>
<.dt>...<./dt> - definicja<br>
<.dd>...<./dd> - opis definicji<br>

<dl>
  <dt>HTML</dl>
  <dd>definicja HTML</dd>
</dl>

<hr>
  <h3>Linki HTML</h3>
<.a>...<./a> - poczatek i koniec linku np. <.a>www.youtube.pl<./a><br>
<.a href= onet.pl>LINK<./a> - poczatek i koniec linku do innej lokalizcaji, np. <a href onet.pl>LINK</a>
<.a target= onet.pl>LINK 2<./a> - poczatek i koniec linku z okresleniem w jakim miejscu ma byc otwarty link, np. <a href=onet.pl target="_blank">LINK</a>
<.h3>grafika na stronie<./h3><br>
<.img src="" width="" height="" alt="" title=""> - dodanie obrazu wraz z wymiarami, tekst alternatywny (kiedy obraz nie bedzie dostepny), tytulem<br>
<img src ="https://st2.depositphotos.com/1823785/7251/i/450/depositphotos_72516833-stock-photo-people-hold-straight-danish-tak.jpg"  width="100" height="150" alt="Nie dziala" title="Tajtyl"><br>
<.figcaption>....<./figcaption> - podpis obrazu
<figure>
  <img src="https://st2.depositphotos.com/1823785/7251/i/450/depositphotos_72516833-stock-photo-people-hold-straight-danish-tak.jpg">
  <figcaption>tsss</figcaption>
  </figure>

  <h1><strong>Co to jest jpg i jakie ma cechy</strong></h1>
  
<.table>...<./table> - poczatek i koniec tabeli
<.tr>...<./tr> - pocztek i koniec wiersza tabeli
<.td>...<./td> - poczatek i koniec komorki tabeli
  
 <table>
   <tr>
     <th>naglowek 1</th>
     <td>komorka 2</td>
   </tr>
   <tr>
     <td colspan = "2">komorka 3</td>
   </tr>
  </table><br>
  
<.th>...<./th> - poczatek i koniec naglowka wiersza<br>
atrybut "scope" - czy jest to naglowek dot. kolumna(col) czy wiersz(row)
atrybut "colspan" - polaczenie komorki wedlug kolumny
<.thead>...<./thead> - poczatek i koniec sekcji naglowka tabeli<br>
<.tbody>...<./tbody> - poczatek i koniec sekcji glowne tabeli<br>
<.tfoot>...<./tfoot> - poczatek i koniec sekcji stopki tabeli

<h2>elementy blokowe i liniowe</h2>

http://how2html.pl/wp-content/uploads/2014/09/element-liniowy-i-blokowy.png

linia 1 i 3 to elementy blokowe np.znaczniki: h1, olm ul, dl, p
linia 2 o 4 to elementy liniowe np.znaczniki: a, b, strong, i ,img

<h2>identyfikatory</h2>
id="..." - atrybut znaznika pozwalajacy odroznic elementy html i odnosic sie do konkretnych elementow,  moga byc wykorzystane jako wewnetrzny odnosnik do miejsca na stronie (w a href="#id")<br>
  
class="nazwa klasy" - selektror klasy, podobne do id. Mozna nimi rozrozniac poszczegolne elementy html. Stosuje sie glownie gdy chcemy nadac taki sam wyglad dla grupy elementow html, rzadziej odnosimy sie za ich pomoca do konkretnego miejsca na stronie. Atrybut "clasa" moze powtarzac sie w dokumencie html<br>
  
  <h3>identyfikatory w css</h3>
  #nazwa - odniesienie sie do selektrora id w pliku css<br>
  .nazwa - odniesienie sie do selektora class w pliku css<br>
  
  <h2>sekcje</h2>
  <.div>...<./div> - element blokowy strony, nazywany rowniez boxem albo kontenerem wenatrz tego elementu dodajemy wszystkie znaczniki potrzebne w tej sekcji. mozna stosowac z identyfikatorem id lub class<br>
 <.header>...<./header> - poczatek i koniec sekcji naglowka strony (logo i menu glowne)<br>
 <.footer>...<./footer> - poczatek i koniec sekcji stopki strony (prawa autorskie, kontakt)<br>
 <.main>...<./main> - poczatek i koniec sekcji  glownej strony (tresc strony)<br>
 <.nav>...<./nav> - poczatek i koniec sekcji nawigacyjnej strony (linki do innych podstron<br>
 <.aside>...<./aside> - poczatek i koniec sekcji bocznej strony (nie zwiazane z trescia, np. boczne menu<br>
 <.article>...<./article> - poczatek i koniec sekcji artykulu (np. tekst z bloga)<br>
 
  
  
