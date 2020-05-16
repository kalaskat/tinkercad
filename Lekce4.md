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

Budeme používat stránku repl.it, kde budeme naše webové stránky zkoušet.

## HTML element

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

Vytvořte si na stránce odstavec s jedním odstavcem textu ![Lorem Ipsum](https://cs.lipsum.com/)

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





