# Všechny CSS Příkazy

## Selektory

- `*` : Selektor všech elementů.
- `element` : Selektor konkrétního HTML elementu.
- `.class` : Selektor třídy.
- `#id` : Selektor ID.
- `element, element2` : Selektor více elementů.
- `element > element2` : Selektor přímého potomka.
- `element + element2` : Selektor sousedního elementu.
- `element ~ element2` : Selektor sourozence (element v rámci stejného rodiče).

## Barvy

- `color` : Nastavuje barvu textu.
- `background-color` : Nastavuje barvu pozadí.
- `border-color` : Nastavuje barvu okraje.

## Velikosti a rozměry

- `width` : Nastavuje šířku elementu.
- `height` : Nastavuje výšku elementu.
- `max-width` : Nastavuje maximální šířku elementu.
- `max-height` : Nastavuje maximální výšku elementu.
- `min-width` : Nastavuje minimální šířku elementu.
- `min-height` : Nastavuje minimální výšku elementu.
- `padding` : Nastavuje vnitřní okraje (vzdálenost mezi obsahem a okrajem elementu).
- `margin` : Nastavuje vnější okraje (vzdálenost mezi elementy).
- `border` : Nastavuje šířku a styl okraje elementu.

## Písmo

- `font-family` : Nastavuje písmo textu.
- `font-size` : Nastavuje velikost písma.
- `font-weight` : Nastavuje tloušťku písma (např. bold).
- `font-style` : Nastavuje styl písma (např. italics).
- `text-align` : Nastavuje zarovnání textu (např. left, right, center).
- `text-decoration` : Nastavuje dekoraci textu (např. underline, line-through).

## Zarovnání a pozicování

- `text-align` : Zarovnání textu uvnitř elementu.
- `vertical-align` : Vertikální zarovnání textu nebo inline elementů.
- `display` : Určuje, jak se element zobrazuje (např. block, inline, flex).
- `position` : Určuje způsob pozicování elementu (např. static, relative, absolute, fixed).
- `top`, `right`, `bottom`, `left` : Určují vzdálenosti pro pozicované elementy.
- `z-index` : Určuje vrstvení elementů (který element je "nahoře").

## Flexbox

- `display: flex` : Aktivuje Flexbox layout pro rodičovský element.
- `justify-content` : Zarovnání elementů v horizontálním směru (např. center, space-between).
- `align-items` : Zarovnání elementů ve vertikálním směru (např. center, stretch).
- `flex-direction` : Určuje směr flexboxu (např. row, column).
- `flex-wrap` : Určuje, zda elementy mohou přetékat do další řady.
- `align-self` : Nastavuje zarovnání jednotlivého elementu v rámci flexboxu.

## Grid

- `display: grid` : Aktivuje Grid layout pro rodičovský element.
- `grid-template-columns` : Definuje sloupce mřížky.
- `grid-template-rows` : Definuje řádky mřížky.
- `grid-column` : Určuje umístění elementu v rámci sloupce.
- `grid-row` : Určuje umístění elementu v rámci řádku.
- `grid-gap` : Určuje mezery mezi sloupci a řádky.

## Pozadí

- `background-image` : Nastavuje obrázek na pozadí.
- `background-size` : Určuje velikost pozadí (např. cover, contain).
- `background-repeat` : Určuje, zda se pozadí opakuje (např. repeat, no-repeat).
- `background-position` : Určuje umístění pozadí (např. center, top left).
- `background-attachment` : Určuje, zda pozadí zůstane na místě při posouvání stránky.

## Okraje a rámečky

- `border` : Nastavuje okraje elementu (včetně šířky, stylu a barvy).
- `border-width` : Nastavuje šířku okraje.
- `border-style` : Nastavuje styl okraje (např. solid, dashed).
- `border-radius` : Zaobluje rohy elementu.
- `box-shadow` : Nastavuje stín pro element.

## Přechody a animace

- `transition` : Nastavuje přechody mezi stavy elementu.
- `transition-duration` : Určuje dobu trvání přechodu.
- `transition-timing-function` : Určuje, jak se přechod chová (např. ease, linear).
- `@keyframes` : Definuje animaci a její fáze.
- `animation` : Aktivuje animaci pro element.

## Viditelnost

- `visibility` : Určuje viditelnost elementu (např. visible, hidden).
- `opacity` : Nastavuje průhlednost elementu (0 - neviditelný, 1 - plně viditelný).

## Z-index

- `z-index` : Určuje, který element je "nad" ostatními v případě překrývání.

## Media Queries

- `@media` : Umožňuje definovat styly pro různé velikosti obrazovky nebo zařízení.

## Pseudo-třídy a Pseudo-elementy

- `:hover` : Aktivuje styly při najetí myší na element.
- `:focus` : Aktivuje styly při zaostření elementu (např. při kliknutí na formulářové pole).
- `:active` : Aktivuje styly při kliknutí na element.
- `:first-child` : Selektor pro první dítě elementu.
- `:last-child` : Selektor pro poslední dítě elementu.
- `::before` : Vkládá obsah před element.
- `::after` : Vkládá obsah za element.

