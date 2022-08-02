# Doortayaasha CSS (CSS Selectors)

Waa mid kamid ah (concept) yada ugu waaweyn CSS, lana rabo in aad sifiican ufahamto.
Doortaha waxa uu go'aamiyaa (Eelemet) ga diirada inoo saaran si aan wax uga badalo (Style) kiisa; Doortayaasha CSS ka waxa ay hal diirada saari karaan wax kabadan hal (Element).
Sidaas si lamid ah hal (Element) oo (HTML) ah waxa saameyn ku yelan kara dhowr doorte hal mar.

## Doortayaahsa Asaasiga ah (Basic Selectors)

Doortayaasha asaasiga ahi waxa kamid ah kuwan

- Universal
- Element
- ID
- Class
- Attribute

### Drootaha Universal

Doortaha (Universal) ka ahi waxa utagaan calamada Xidigta (*), waxayna u taaganthy dhamaan (Element) yada ku jira (DOM) ka kaligiisa, ama waxa laracsiya doorte ugooni ah (Elements) gooni ah.

```css
* {
    margin:0;
    padding:0;
    box-sizing: border-box;
}
```

Code kaan kore waxa uu qeexayaa dhamaan (Elements) ka Kujira websitkeena oo dhan in qimayaasha asaliga ah ee (Margin) iyo (Paddin) ka element walba laga dhigo 0.

### Doortaha Elementga (Element Selectors)

Doortaha (Element) ga waxa loola jeeda in aan ku doorano (Element) ga (Tag) giis (HTML) ka, waxa laga wada hadan ku si jilciyo hadalka waxaan ula jeedna (Element) ga waxa ugu wacaynaa Tag giis HTML oo mutaxan oo aan waxa lagu darin tusaale

```css
h1 {
    font-size: 20px;
}
```

sida kor ka muuqata waxaan dooranay (Element) ga loo yaqaano (h1) oo ah heading 1aad ee (HTML) ka waxa ku doranay Taggis oo mutaxan,

sidoo kale (h1) aan kor ku doorany waxay badli doonta wax walba oo (h1) ee kujra websitkeena hal xabo kaliya mabadlyo.

### Doortaha ID (ID Selectors)

(Element) ga aan rabno in aan si gooni ah aan diirada u sarno si aan kaligiis (Style) kiis ubadalno, (HTML) (Element) ga waxaan soo sineynaa (Attribute) layiraahdo (ID) waxana sineynaa ID u gooni ah, Tusaale.

waxan ka hormarineynaa magaca ID ga claamada (#) oo utaagan waxa ku xiga in ay yihiin ID Element gooni ah leyhay

```css
#title {
    color:red;
}
```

Code ka kore waxa uu shegaya ELement ga le ID ga `title` inaa midabka fartiisa aan kadhigno casaan ama gaduud.

### Doortaha Class (Class Selectors)

Doortahan waxa aan u sineynaaa Element ga aan rabno inaa so gooni ah u beegsanno ama diirada usaarno Attribute layirhaado Class kadibna magaca gooni ah baan ubixineynaa.
si aan CSS ka ugu sheegno waxa aan ELement ga ku beegsanyno inu yahay class magaca calsska waxa aan ka hormarineyna ( . ) joogsi.

```css
.mainTitle{
    border: 1px solid red;
}
```

Code ka kore waxa uu no shegaya in ELement ga leh `.mainTitle` classkaas in aan siino xeyndaab xariiq ah cabirkeedu yahy `1px` midabkeeduna yahay `casaan`.