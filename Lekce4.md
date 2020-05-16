# Základy HTML a HTML5

HTML nebo HyperText Markup Language je značkovací jazyk používaný k popisu struktury webové stránky. K uspořádání a poskytování informací o stránce v prohlížeči používá speciální syntaxi nebo zápis. Prvky mají obvykle otevírací a zavírací značky, které obklopují a dávají obsahu formát. Například kolem textu lze umístit různé možnosti značek, které ukazují, zda se jedná o nadpis, odstavec nebo seznam.

Například:
```html
<h1>Název stránky</h1>

<p>Odstavec textu. Nějaké informace, které bychom chtěli divákovi sdělit. Může to být tak dlouhé nebo krátké, jak bychom chtěli.</p>

<ol>
  <li>položka 1</li>
  <li>položka 2</li>
  <li>položka 3</li>
</ol>
```

### Jak to ve skutečnosti vypadá

<h1>Název stránky</h1>

<p>Odstavec textu. Nějaké informace, které bychom chtěli divákovi sdělit. Může to být tak dlouhé nebo krátké, jak bychom chtěli.</p>

<ol>
  <li>položka 1</li>
  <li>položka 2</li>
  <li>položka 3</li>
</ol>

Část HTML HyperText pochází z raných dnů webu a jeho původního případu použití. Stránky obvykle obsahovaly dokumenty, které obsahovaly odkazy na jiné dokumenty. Tyto odkazy obsahovaly hypertextové odkazy používané prohlížečem k navigaci do původního dokumentu, takže uživatel mohl přečíst dokument, aniž by jej musel ručně hledat.

S rostoucí složitostí webových stránek a webových aplikací konsorcium W3 aktualizuje specifikace HTML, aby bylo možné spolehlivě zobrazit webovou stránku v libovolném prohlížeči. Poslední verze HTML je HTML5.

Budeme používat stránku [repl.it](www.repl.it), kde budeme naše webové stránky kódovat a testovat. 

V horní části dokumentu musíte prohlížeči sdělit, jakou verzi HTML vaše stránka používá. HTML je vyvíjející se jazyk a je pravidelně aktualizován. Většina hlavních prohlížečů podporuje nejnovější specifikace, což je HTML5. Starší webové stránky však mohou používat předchozí verze jazyka. Tohle za nás repl.it kontroluje samo.

[ODKAZ NA TŘÍDU](https://repl.it/classroom/invite/qjsnxSM)

## HTML element

```html
<h1>Vítejte</h1>
```

Většina prvků HTML má počáteční a závěrečnou značku. Píší se malými písmeny. Některé prvky nemají závěrečnou značku. Některé prvky mají takzvané atributy neboli vlastnosti. Například obrázek má vlastnost, že něco ukazuje a že se někde nachází (nahraný někde na serveru).

Počáteční značky vypadají takto:
```html
<h1>
```

Závěrečné značky vypadají takto:
```html
</h1>
```

Jediným rozdílem mezi otevíracími a zavíracími značkami je lomítko za otevírací závorkou uzavírací značky.

### Úkol 1

Naučte se na klávesnici napsat ***<*** a ***>*** a ***/***. Napište nadpis stránky (element h1) jako "Cat Photo App"

## Další elementy

Prvek h2 přidá na webovou stránku nadpis druhé úrovně.

Tento prvek informuje prohlížeč o struktuře vašich webových stránek. Prvky h1 se často používají pro hlavní položky, zatímco prvky h2 se obecně používají pro podpoložky. Existují také prvky h3, h4, h5 a h6, které označují různé úrovně podpoložek.

### Úkol 2

Vyzkoušejte si typy nadpisů h1 (Hlavní nadpis), h2 (Podnadpis 1), h3 (Podnadpis 2), h4 (Podnadpis 3).

## Paragraf

Prvky p jsou preferovaným prvkem textu odstavce na webových stránkách. p je zkratka pro „odstavec“ (anglicky paragraph).
Můžete vytvořit prvek odstavce, jako je tento:

```html
<p> Jsem značka p! </p>
```

### Úkol 3

Vytvořte si na stránce odstavec s jedním odstavcem textu [Lorem Ipsum](https://cs.lipsum.com/)

## Komentáře

Komentář je způsob, jak můžete zanechat komentáře pro ostatní vývojáře/programátory v rámci vašeho kódu, aniž by to ovlivnilo výsledný výstup, který se zobrazí koncovému uživateli.

Komentování je také pohodlný způsob, jak kód deaktivovat, aniž byste jej museli zcela smazat. Tedy webové stránky to, co je v komentáři napsáno ignorují

Komentáře v HTML začínají ```<!``` - a končí znakem ```->```

```html
<!--
Toto je komentář
-->
<x>Lorem ipsum</x>
```

### Úkol 4

Napište na začátek HTML komentář, kde popíšete webovou stránku. Bude se jednat o stránku s fotkami koček. Dále napište komentáře u nadpisu a odstavce s textem "Toto je nadpis stránky" a "Toto je text v odstavci".

## Další značky

HTML5 zavádí popisnější značky HTML. Patří mezi ně  ***main*** (hlavní), ***header*** (záhlaví), ***footer*** (zápatí), ***nav*** (navigace), ***video***, ***article*** (článek), ***section*** (rubrika) a další.

Tyto značky dodávají vašemu HTML popisnou strukturu, usnadňují čtení vašeho HTML a pomáhají s optimalizací vyhledávače (SEO) a přístupností. Stránka je lépe vyhledatelná např. na Googlu. Hlavní značka HTML5 pomáhá vyhledávacím strojům a dalším vývojářům najít hlavní obsah vaší stránky.

Příklad použití, hlavní prvek se dvěma prvky vnořenými uvnitř:

```html
<main> 
  <h1>Hello World</h1>
  <p>Hello Paragraph</p>
</main>
```

### Úkol 5

Vložte váš odstavec s Lorem ipsum do značky main. Nezapomeňte na ukončovací značku.

## Obrázky

Na svůj web můžete přidat obrázky pomocí prvku ***img*** a pomocí atributu/vlastnosti ***src*** přejděte na adresu URL konkrétního obrázku. URL adresa je např. www.google.com.

Příklad

```html
<img src = "https://www.your-image-source.com/your-image.jpg">
```

Upozorňujeme, že prvky img se samouzavírají. -> NENÍ ZDE UKONČOVACÍ ZNAČKA!!!

Všechny prvky img musí mít také svůj vlastní ***alt***. Text uvnitř alt se používá pro čtečky obrazovky ke zlepšení přístupnosti a zobrazí se, pokud se obrázek nepodaří načíst. Popisujeme zde, co je na obrázku.

Poznámka: Pokud je obraz čistě dekorativní, je nejlepším postupem použití atributu prázdný alt.

V ideálním případě by atribut alt neměl obsahovat speciální znaky, pokud to není nutné.

Pojďme se podívat, jak to vypadá:

```html
<img src = "https://seojake.com/wp-content/uploads/2017/05/when-people-dont-close-html-elements-meme.jpg" alt = "HTML meme.">
```

<img src = "https://seojake.com/wp-content/uploads/2017/05/when-people-dont-close-html-elements-meme.jpg" alt = "HTML meme.">

Odkaz na obrázek zjistíte tak, že na obrázek kliknete pravým tlačítkem na myši a kliknete na ***ZKOPÍROVAT ADRESU OBRÁZKU*** 

### Úkol 6

Do existujícího hlavního prvku ***main*** vložte ***před*** existující prvky ***p*** prvek ***img***.

Nyní nastavte ***src*** tak, aby ukazoval na tuto adresu URL:

https://bit.ly/fcc-relaxing-cat

Nakonec nezapomeňte dát vašemu prvku ***img*** atribut ***alt*** s použitelným textem!

## Odkazy

Prvky ***a*** (z angličtiny anchor = kotva) můžete použít k propojení s obsahem mimo vaši webovou stránku. Třeba s další webovou stránkou.

Prvky potřebují cílovou webovou adresu nazvanou ***href***. Potřebují také ***kotevní text*** -> co bude na stránce napsáno. Zde je příklad:

```html
<a href="https://google.com"> Odkaz na Google </a>
```

<a href="https://google.com"> Odkaz na Google </a>

Poté váš prohlížeč zobrazí text „Odkaz na Google“ jako odkaz, na který můžete kliknout. A tento odkaz vás přesune na webovou adresu https://www.google.org.

### Úkol 7

Vytvořte prvek, který odkazuje na http://freecatphotoapp.com a jako jeho kotevní text obsahuje „kočičí fotografie“.

### Odkaz na místo na stránce

(Kotevní) prvky ***a*** lze také použít k vytvoření interních odkazů pro přechod na různé sekce na webové stránce. Třeba na konec stránky. Nebo na podsekci "Napište nám!".

Každý HTML kód se dá rozdělit na několik častí a každá může mít svojí vlastní "občanku", které se říká ***id***. To musíme ale jednotlivým elementům přiřadit, jak? Uvidíte na příkladu. :)
Chcete-li vytvořit interní odkaz, napište do ***href*** odkazu hash symbol ***#*** a id pro prvek, kam chceme odkazovat. 

Příklad

Normální nadpis 2
```html
<h2 Kontakty </h2>
```
Nadpis 2 s id "Kontakty"
```html
<h2 id = "Kontakty"> Kontakty </h2>
```

Zde máme odkaz, který říká, že chci vytvořit odkaz, když na něj kliknu, tak mě přeskočí stránka na sekci kontakty. 
```html
<a href="#contacts-header"> Kontakty </a>
```
### Úkol 8

Přidejte si nový element zápatí = konec stránky.
```html
<footer>Vaše jméno</footer>
```
Přidejte tomuto elementu id "konec".

Změňte svůj původní (externí) odkaz na (interní) odkaz. Změňte href na „#konec“ a text z „kočičí fotky“ na „Přejít na konec stránky“.

## Vložení odkazu do textu

Odkazy můžeme vkládat do textů v odstavcích (elementy p).

```html
<p>
  Zde je <a target="_blank" href="http://google.com"> odkaz na google.com </a>, který můžete použít k vyhledávání.
</p>
```
Zde je <a target="_blank" href="http://google.com"> odkaz na google.com </a>, který můžete použít k vyhledávání.

Podívejme se na příklad: 
Normální text je zabalen do prvku p:
<p> Zde je ... text pro vás. </p> Další je kotevní prvek <a> (který vyžaduje uzavírací značku </a>):
<a> ... </a> target je atribut kotevní značky, který určuje, kde se má odkaz otevřít, a hodnota "_blank" určuje otevření odkazu na nové kartě. href je atribut kotevní značky, který obsahuje adresu URL odkaz:
<a href="http://freecodecamp.org"> ... </a> Text, „odkaz na freecodecamp.org“, v elementu zvaném kotevní text, zobrazí odkaz na kliknutí:
<a href=" ... "> odkaz na freecodecamp.org </a> Konečný výstup z příkladu bude vypadat takto:

### Úkol 9

Nyní vložte existující prvek do nového prvku p (hned za existujícím hlavním prvkem). Nový odstavec by měl obsahovat text „Zobrazit více kočičích fotografií“, kde „kočičí fotografie“ je odkaz a zbytek textu je normální prostý text.

Mělo by to tedy vypadat takto:
<p>Zobrazit více <a href="http://freecatphotoapp.com" target="_blank">kočičích fotografií</a>.</p>

### Mrtvé odkazy

Někdy budete chtít na svůj web přidat odkazy, ale ještě nebudete vědět, kam přesně budou odkazovat (třeba na podstránku, kterou ještě nebudete mít vytvořenou).

### Úkol 10

Aktuální hodnota atributu ***href*** je odkaz, který odkazuje na „http://freecatphotoapp.com“. Chcete-li vytvořit mrtvý odkaz, nahraďte hodnotu atributu href znakem #, známým také jako hash symbol.

Například: 
```
href = "#"
```

## Klikací obrázek s odkazem

Místo textu můžete mít jako odkaz přímo nějaký obrázek. Zde je příklad:

```html
<a href="#"> <img src = "https://bit.ly/fcc-running-cats" alt = "Tři koťata běží směrem k fotoaparátu."> </a>
```

<a href="#"> <img src = "https://bit.ly/fcc-running-cats" alt = "Tři koťata běží směrem k fotoaparátu."> </a>

Nezapomeňte použít # jako vlastnost prvku href vašeho prvku, abyste ji proměnili v mrtvý odkaz.

### Úkol 11

Udělejte z obrázku, který máte na stránce, mrtvý odkaz (pomocí href = "#").

Jakmile to uděláte, umístěte kurzor na obrázek. Normálním ukazatelem kurzoru by se měl stát ukazatel odkazující na odkaz. Fotografie je nyní odkazem.

## Seznamy

HTML má speciální prvek pro vytváření seznamů nebo seznamů stylů odrážek.

Neuspořádané seznamy (nepotřebujeme tady číslování 1. 2. 3. atd) začínají otevíracím elementem ***<ul>***, po kterém následuje libovolný počet elementů ***<li>***. Konečně, neuspořádané seznamy uzavírají ***</ul>***.

Například:

```html
<ul>
   <li> mléko </li>
   <li> sýr </li>
</ul>
```
by vytvořil seznam stylů „mléko“ a „sýr“ s odrážkami.

<ul>
   <li> mléko </li>
   <li> sýr </li>
</ul>

### Úkol 12
Vytvořte neuspořádaný seznam tří věcí, které kočky milují ve spodní části stránky.

### Číslované seznamy
HTML má další speciální prvek pro vytváření uspořádaných seznamů nebo číslovaných seznamů.

Seřazené seznamy začínají otevíracím elementem ***<ol>***, po kterém následuje libovolný počet elementů ***<li>***. Nakonec jsou uspořádané seznamy uzavřeny značkou ***</ol>***.

Například:
```html
<ol>
   <li> Garfield </li>
   <li> Sylvester </li>
</ol>
```
by vytvořil očíslovaný seznam "Garfield" a "Sylvester".

<ol>
   <li> Garfield </li>
   <li> Sylvester </li>
</ol>

### Úkol 13

Vytvořte uspořádaný seznam tří věcí, které kočky nejvíce nenávidí.

## Okénka pro vyplnění návštěvníkem 

Občas chceme, aby nám návštěvník vyplnil na stránce nějaké informace.

Můžete vytvořit textový vstup takto:
```html
<input type = "text">
```

Všimněte si, že vstupní prvky jsou samouzavírací. NEMAJÍ UKONČOVACÍ ZNAČKU.

Zástupný text je to, co se zobrazí ve vašem okénku předtím, než uživatel/návštěvník stránky něco zadá.

Zástupný text můžete vytvořit takto:

```html
<input type = "text" placeholder = "toto je zástupný text">
```

Poznámka: Nezapomeňte, že vstupní prvky jsou samouzavírací.

### Úkol 14

Pod seznamy vytvořte okénko textu. Nastavte zástupný text na „cat cat URL“.

### Webový formulář

Webové formuláře, které skutečně odesílají data na server, můžete vytvářet čistě pomocí HTML. To lze provést zadáním akce na prvek formuláře. ***<form>*** ***</form>***

Například:

```html
<form action = "/ adresa-kam-se-má-informace-nahrát"> </form>
```

### Úkol 15
Vložte své okénko do elementu formuláře a do formuláře přidejte atribut ***action = "/ submit-cat-photo"***.

### Tlačítko ODESLAT

Přidáme do formuláře tlačítko pro odeslání. Kliknutím na toto tlačítko odešlete data z formuláře na adresu, kterou jste uvedli předtím.

Tlačítko odeslat:

```html
<button type = "submit"> toto tlačítko odešle formulář </button>
```

Formulář s tlačítkem odeslat:

```html
<form action = "/ submit-cat-photo"> 
<button type = "submit"> toto tlačítko odešle formulář </button>
</form>
```

Zde je příklad formuláře s okénkem a s tlačítkem odeslání:

```html
<form action = "/ submit-cat-photo"> 
<input type = "text" placeholder = "toto je zástupný text">
<button type = "submit"> toto tlačítko odešle formulář </button>
</form>
```

### Úkol 16

Přidejte tlačítko jako poslední prvek uvnitř do formuláře (pod okénko) a jako text zadejte „Odeslat“.

## Další tlačítka

https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/create-a-set-of-radio-buttons
https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/create-a-set-of-checkboxes
https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/use-the-value-attribute-with-radio-buttons-and-checkboxes
https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/check-radio-buttons-and-checkboxes-by-default
https://www.freecodecamp.org/learn/responsive-web-design/basic-html-and-html5/nest-many-elements-within-a-single-div-element


