

# TypeScript Seminar
TypeScript ist eine Obermenge von ECMAScript 6 (ES6) und ist rückwärtskompatibel mit ECMAScript 5, d. h. JavaScript.  
Angular bietet somit auch die Vorzüge von ES6:  
- Lambdas
- Iteratoren
- for…of-Schleifen
- Generatoren im Stil von Python
- Reflexion

## Inhalt
<!-- vscode-markdown-toc -->
* 1. [Markdown (.md) Formatierungsregeln](#Markdown.mdFormatierungsregeln)
* 2. [Visual Studio Code](#VisualStudioCode)
* 3. [Git Hub](#GitHub)
	* 3.1. [Git Bash](#GitBash)
	* 3.2. [Visual Studio Code](#VisualStudioCode-1)
* 4. [Hilfsfunktionen für VS Code](#HilfsfunktionenfrVSCode)
* 5. [Debugging](#Debugging)
* 6. [Seminarablauf](#Seminarablauf)
	* 6.1. [Tag 1](#Tag1)
	* 6.2. [Tag 2](#Tag2)
	* 6.3. [Tag 3](#Tag3)
* 7. [Installation TypeScript](#InstallationTypeScript)
* 8. [Installation Webpack](#InstallationWebpack)
* 9. [ECMA-6](#ECMA-6)
	* 9.1. [Emmet Cheatsheets](#EmmetCheatsheets)
	* 9.2. [Syntaxerweiterungen](#Syntaxerweiterungen)
		* 9.2.1. [Variablen](#Variablen)
		* 9.2.2. [Spread- & Rest-Operationen](#Spread-Rest-Operationen)
		* 9.2.3. [Destructuring](#Destructuring)
		* 9.2.4. [Literale](#Literale)
		* 9.2.5. [Arrays](#Arrays)
		* 9.2.6. [Iterables -> Iterator](#Iterables-Iterator)
	* 9.3. [Funktionen vs. Arrow-Funktionen](#Funktionenvs.Arrow-Funktionen)
		* 9.3.1. [Functions](#Functions)
		* 9.3.2. [Arrow-Functions](#Arrow-Functions)
	* 9.4. [Promises -> Chains](#Promises-Chains)
	* 9.5. [fetch-API](#fetch-API)
	* 9.6. [Generatoren](#Generatoren)
	* 9.7. [class-Keyword vs. Konstruktor](#class-Keywordvs.Konstruktor)
	* 9.8. [Vererbung](#Vererbung)
	* 9.9. [Module (Webpack und TypeScript)](#ModuleWebpackundTypeScript)
	* 9.10. [Observables](#Observables)
* 10. [Typescript](#Typescript)
	* 10.1. [Decorators](#Decorators)
	* 10.2. [Types](#Types)
	* 10.3. [Interfaces](#Interfaces)
	* 10.4. [TS-Classes](#TS-Classes)
	* 10.5. [Generics](#Generics)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->

##  1. <a name='Markdown.mdFormatierungsregeln'></a>Markdown (.md) Formatierungsregeln
* [Markdown Tutorial Git](http://agea.github.io/tutorial.md/)
* [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
* [Markdown Navigation](https://github.com/AlanWalk/markdown-navigation)

##  2. <a name='VisualStudioCode'></a>Visual Studio Code
* Live Server als Extension installieren
** mit ALT + L + O wird der Server gestartet und die aktuelle Webseite geöffnet und bei jedem Speichern aktualisiert im Browser
* Formatierung des Texts mit ALT + Shift + F
* Zeilenumbruch aktivieren mit ALT + Z
* Aus-/Einkommentieren mit STRG + #
* Kommentar in JavaScript /**/ (Ein-/Mehrzeilig) oder // (Einzeilig)

##  3. <a name='GitHub'></a>Git Hub
* auf git hub ein neues Repository anlegen
* https Link kopieren
* Laufwerk/Order im Explorer öffnen in der das Repository lokal abgelegt werden soll

###  3.1. <a name='GitBash'></a>Git Bash
* mit Rechtsklick git bash öffnen
* git config --global user.name "username"
* git config --global user.email "eMail@host"
* Repository nach lokal kopieren:
    * git clone  https://github.com/grisham88/Javascript.git

###  3.2. <a name='VisualStudioCode-1'></a>Visual Studio Code
* [Visual Studio Code: How to integrate Git](https://www.theregister.co.uk/2015/12/07/visual_studio_code_git_integration/)
* Den neuen Ordner öffnen
* mit Rechtsklick "Open with Code"
* Nun ist das Repository mit git verknüpft und alle Änderungen sind direkt commit und pushbar 
    * Über die Source control (Link in Visual Studio Code) sieht man alle offenen Dateien die geändert wurden
    * Mit Button "V" können diese direkt commited werden oder einzeln zum Commit freigegeben werden
    * Beim ... kann dann push ausgeführt werden -> Git wird nach Git Hub aktualisiert

##  4. <a name='HilfsfunktionenfrVSCode'></a>Hilfsfunktionen für VS Code
- https://code.visualstudio.com/docs/getstarted/tips-and-tricks
- https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf
- https://code.visualstudio.com/docs/getstarted/keybindings
- Aufruf durch F1
    - Wenn > hinterlegt ist, werden Funktionen aufgeführt
    - Ohne > kann man nach Dateien suchen
- STRG + B für Explorer links zuklappen

##  5. <a name='Debugging'></a>Debugging
- Extension Chrome Debugger installieren
- F5 bestätigen, dann stoppen und in der neuen launch.json den korrekten Port hinterlegen
- F1 bestätigen, suchen nach User Settings, dann dort nach Debugging und die Einstellung "Allow Breakpoints Everywhere" aktivieren
- Breakpoints setzen und mit F5 Debugging starten und zur gewünschten Datei hinwechseln

##  6. <a name='Seminarablauf'></a>Seminarablauf

###  6.1. <a name='Tag1'></a>Tag 1
ECMA 6
- Syntaxerweiterungen
    - Variablen
    - Spread- & Rest-Operationen
    - Destructuring
    - Objektliterale
    - Symbols
    - Arrays
    - Iterables -> Iterator
        - for ... of

###  6.2. <a name='Tag2'></a>Tag 2
ECMA 6
- Funktionen vs. Arrow-Funktionen
- Promises -> Chains
- fetch-API
- Generatoren
- class-Keyword vs. Konstruktor
- Vererbung
- Module (Webpack und TypeScript)
- Observables

###  6.3. <a name='Tag3'></a>Tag 3
Typescript
- Decorators
- Types
- Interfaces
- TS-Classes
- Generics

Tooling
- TSC (TypeScript Compiler)
- Webpack
- RxJs

##  7. <a name='InstallationTypeScript'></a>Installation TypeScript
Installation:  
- https://code.visualstudio.com/docs/languages/typescript
- The easiest way to install TypeScript is through npm, the Node.js Package Manager. If you have npm installed, you can install TypeScript globally (-g) on your computer by:

```html
npm install -g typescript
```
You can test your install by checking the version or help.
```html
tsc --version
tsc --help
```
Compilierung:  
Eingabe im Terminal tsc und name der Datei
```html
Beispiel: tcs "typescript - example.ts"
```
Dadurch wird eine ausführbare .js-Datei erzeugt

##  8. <a name='InstallationWebpack'></a>Installation Webpack

##  9. <a name='ECMA-6'></a>ECMA-6
- https://www.w3schools.com/js/js_es6.asp
- https://www.buschmais.de/2017/08/24/cleaner-code-mit-ecmascript-6/
- Implementierungsstand  
    - http://kangax.github.io/
    - http://kangax.github.io/compat-table/es6/
        - grün (implementiert)
        - rot (nicht unterstützt)

###  9.1. <a name='EmmetCheatsheets'></a>Emmet Cheatsheets
- https://docs.emmet.io/cheat-sheet/

###  9.2. <a name='Syntaxerweiterungen'></a>Syntaxerweiterungen

####  9.2.1. <a name='Variablen'></a>Variablen

##### var
- https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Statements/var
```html
<script>
    //linearer Codeablauf
    console.log("Wir betrachten die neuen Keywords für Deklarationen");

    //kein RefErr wg. Hoisting!
    console.log(test);

    var test = "var: Das ist ein Test.";

    console.log(test);

    for (var i = 0; i < 5; i++) {
        var temp = i + i;
        console.log(temp);
    }

    //Variablen existieren global, nicht lokal
    console.log('oops...:', i, temp);    
</script>
```

##### let 
- https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Statements/let
```html
<script>
    // ECMA6: let, const

    // RefErr, Variable ist nur an der Stelle existent (TDZ -> Temporal dead Zone)
    console.log(test2);

    let test2 = "let: Auch ein Test...";
    console.log(test2);

    //im Block
    if (true) {
        let iftest = "Ich bin im Block!";
        console.log(iftest);
    }

    // RefErr, Variable ist nur im Block existent (TDZ -> Temporal dead Zone)
    console.log(iftest);

    // let und Schleife:
    for (let j = 0; j < 3; j++) {
        // temp2 wird immer wieder angelegt
        let temp2 = j * 2;
        console.log('let:', temp2);
    }

    // RefErr, Variable ist nur in der Schleife existent (TDZ -> Temporal dead Zone)
    console.log('oops...:', j, temp2);  
</script>
```

##### const
- https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Statements/const
```html
<script>
    // ECMA 6: const
    const test3 = "Das ist wieder ein Test!";
    console.log('const: ', test3);

    //Uncaught TypeError: Assignment to constant variable. Änderungen nicht erlaubt
    test3 = "Was anderes?";
    
    //Uncaught SyntaxError: Missing initializer in const declaration. Initialisierung ist ein MUSS
    const weissnicht;

    const werte = [];
    werte.push(5);
    //Möglich durch Referenztyp
    console.log('const Array:', werte); // Ausgabe [5]
     
    // Funktion ist durch const nicht mehr änderbar
    const tool = function (){
        //tue was Wichtiges...
    };

    // Funktion ist durch var änderbar
    var tool2 = function tool2(){
        //tue was Wichtiges...
    };

    // const und Schleife
    for (let k = 0; k < 3; k++) {
        //Variable wird nicht immer wieder initialisiert
        const temp3 = k * 2;
        console.log('const: ', temp3);
    }
</script>
```

####  9.2.2. <a name='Spread-Rest-Operationen'></a>Spread- & Rest-Operationen
##### Spread
- https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Operators/Spread_syntax
- Verwandelt durch ... ein Array in eine Sequenz, also in einzelne Übergabewerte
- Arrays
    ```html
    <script>
        let zahlen = [2, 3, 4];
        let addiere = function (a, b, c) {
            return a + b + c;
        }

        let erg = addiere(5, 7, 8);
        console.log('erg:', erg); // erg: 20

        erg = addiere(zahlen);
        console.log('erg:', erg); // erg: 2,3,4undefinedundefined
            
        erg = addiere(...zahlen); // Spread: Array -> Sequenz (Verwandelt)
        console.log('erg:', erg); // erg: 9

        let mehrzahlen = [7, 3, 9, 3];
        // Neues Array allezahlen -> allezahlen: (7) [2, 3, 4, 7, 3, 9, 3]
        let allezahlen = zahlen.concat(mehrzahlen);
        console.log('allezahlen:', allezahlen);

        let allezahlen2 = [2, 3, 4, allezahlen];
        console.log('allezahlen2:', allezahlen2); // allezahlen2: (4) [2, 3, 4, Array(7)]
            
        allezahlen2 = [...zahlen, ...allezahlen]; // Spread: Array -> Sequenz (Verwandelt)
        console.log('allezahlen2:', allezahlen2); // allezahlen2: (10) [2, 3, 4, 2, 3, 4, 7, 3, 9, 3]

        let zahlenClone = [...zahlen];
        console.log('zahlenClone:', zahlenClone); // zahlenClone: (3) [2, 3, 4]
    </script>
    ```
- Objects
    ```html
    <script>
         let myObjX = {
            x: "X",
            y: "Y",
            z: "Z"
        }

        console.log(myObjX); // {x: "X", y: "Y", z: "Z"}

        let myObjA = {
            a: "A",
            b: "B"
        }

        let myObjXClone = { ...myObjX };
        console.log(myObjXClone); // {x: "X", y: "Y", z: "Z"}
        console.log(myObjXClone === myObjX); // false

        myObjXClone = myObjX;
        console.log(myObjXClone); // {x: "X", y: "Y", z: "Z"}
        console.log(myObjXClone === myObjX); // true

        let myMergedObject = { ...myObjX, ...myObjA };
        console.log(myMergedObject); // {x: "X", y: "Y", z: "Z", a: "A", b: "B"}

        //Bereits vorhandes Property des Objekts kann überschrieben werden
        myMergedObject = { ...myObjX, ...myObjA, z: "Anders Z" };
        console.log(myMergedObject); // {x: "X", y: "Y", z: "Anders Z", a: "A", b: "B"}

        //Erzeugt ein neues Object
        function configurable(conf) {
            let defaults = {}
            let myConf = { ...defaults, ...conf };
            return myConf;
        }
    </script>
    ```

##### Rest
- https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Functions/rest_parameter
- Verwandelt durch ... eine Sequenz in ein Array (Funktionsparameter), also aus einzelnen Übergabewerten
```html
<script>
    let addiere2 = function (...args) {
        // Mit Funktionsparmeter als Sequenz -> Array
        console.log('args:', args);
        return args.reduce(function (a, b) {
            return a + b;
        })
    }

    let erg2 = addiere2(5, 8, 2, 9);  // args: (4) [5, 8, 2, 9]
    console.log('erg2:', erg2); // erg2: 24

    let addiere3 = function () {
        // ohne Funktionsparameter (Kein Rest)
        console.log(arguments) // Arguments(4) [5, 8, 2, 9, callee: (...), Symbol(Symbol.iterator): ƒ]
        return Array.prototype.reduce.call(arguments, function (a, b) {
            return a + b;
        });
    }

    let erg3 = addiere3(5, 8, 2, 9);  // Arguments(4) [5, 8, 2, 9, callee: ƒ, Symbol(Symbol.iterator): ƒ]
    console.log('erg3:', erg2); // erg2: 24
</script>
```

####  9.2.3. <a name='Destructuring'></a>Destructuring
- https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Operators/Destrukturierende_Zuweisung  
##### Array
 ```html
    <script>
        let blumen = ['Rosen', 'Tulpen', 'Nelken'];

        // let rosen = blumen[0];

        // einfacher mit Destructuring -> Neue Variablen entstehen direkt
        let [rose, /*Tulpen wird übersprungen*/, nelke] = blumen;
        console.log(rose); // Rosen
        console.log(nelke); // Nelken
        
        let zahlen = [4, 6, 2, 9, 5, 12, 9, 14];
        console.log(zahlen); // (8) [4, 6, 2, 9, 5, 12, 9, 14]
        // Zusammenfassung der restlichen Wert in eine Variable mittels Spread (...rest)
        let [zahl1, zahl2, zahl3, ...rest] = zahlen;
        console.log(zahl1); // 4
        console.log(rest); // (5) [9, 5, 12, 9, 14]
        
        // was ist möglich?
        let [body] = document.getElementsByTagName('body');
        // Body wird in einem Array an erster Stelle zurückgeliefert
    </script>
```

##### Object
```html
<script>
    let myObjX = {
        x: "X",
        y: "Y",
        z: "Z"
    }

    //Zugriff mittels Propertyname
    let { x, z } = myObjX;
    console.log(x); // X
    console.log(z); // Z

    //Zugriff mittels falschem Propertyname
    let { f } = myObjX;
    console.log(f); // undefined

    //Zugriff mittels falschem Propertyname
    let { g = 'geht...' } = myObjX;
    console.log(g); // geht...        

    let { x, y } = myObjX; // Uncaught SyntaxError: Identifier 'x' has already been declared

    //Alias: -> Name des neuen Objekts
    let { x: anderesX, y: y } = myObjX; // Uncaught SyntaxError: Identifier 'x' has already been declared
    console.log(anderesX); // X  
        
    let myObjA = {
        a: "A",
        b: "B",
        c: "C",
        d: "D"
    }

    //Automatisch für alle Variablen erzeugen lassen, rest enthält nicht zugewiesene Variablen
    let { a, c, ...rest } = myObjA;
    console.log(rest); // {b: "B", d: "D"}   
</script>
```
##### Object (Deep Structures)
```html
<script>
    let deepObject = {
        e1: {
            e2: "E2",
            e3: {
                e4: "E4"
            }
        }
    };

    // Zerlegen, sodass
    // let e2 = deepObject.e1.e2;
    // und
    // let e4 = deepObject.e1.e3.e4;

    let { e1: { e2: neuesE2, e3: { e4: neuesE4 } } } = deepObject;
    // Durch ":" nach "e1", kann auf das "e2" Property mittels "{}" zugegriffen 
    // und daraus eine neue Variable "neuesE2" erzeugt werden
    // Durch ein weiteres ",", kann auf die nächste Property "e3" zugegriffen
    // werden und mittels weiterem ":" auf deren Property "e4", 
    // wobei daraus  eine neue Variable "neuesE4" deklariert wird
    console.log(neuesE2); // E2
    console.log(neuesE4); // E4  
</script>
```

####  9.2.4. <a name='Literale'></a>Literale

##### Templateliterale
- https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/template_strings
```html
<script>
    let string1 = "Das ist ein einzeiliger String";
    let string2 = 'Das ist ein einzeiliger String';
    // neu:
    let string3 = `Das ist ein String.`;
    let string4 = `Es ist aber
                    ein mehrzeiliger 
                    String!`;

    let johnHtml = `
        <p>Name:John Doe</p>
        <p>Alter:42</p>
        `;

    let vorname = "Peter";
    let nachname = "Panter";
    let alter = 33;

    //Template-Variablen nutzen
    let peterHtml = `
        <p>Name: ${vorname} ${nachname}<p>
        <p>Alter ${alter}</p>
        `;
    console.log(peterHtml);
    // <p>Name: Peter Panter<p>
    // <p>Alter 33</p>

    vorname = "Paulchen";
    //Kein Binding der Variable, Variableninhalt wurde fest in peterHtml übernommen
    console.log(peterHtml);
    // <p>Name: Peter Panter<p>
    // <p>Alter 33</p>

    function personHtml(vorname, nachname, alter) {
        return `
        <p>Name: ${vorname} ${nachname}<p>
        <p>Alter ${alter}</p>
        `;
    }

    let joe = personHtml('Joe', 'Cool', 55);
    console.log(joe);
    // <p>Name: Joe Cool<p>
    // <p>Alter 55</p>

    let mickeyObj = {
        vorname: 'Mickey',
        nachname: 'Mouse',
        alter: 90,
        kinder: 'unbekannt'
    }

    //Destructuring mit Defaultparameter
    function betterPersonHtml({ vorname, nachname, haustier = 'Pluto' }) {
        return `
        <p>Name: ${vorname} ${nachname}<p>
        <p>Haustier ${haustier}</p>
        `;
    }
        
    let mickey = betterPersonHtml(mickeyObj);
    console.log(mickey);
    // <p>Name: Mickey Mouse<p>
    // <p>Haustier Pluto</p>

    //Mittels Spread nicht möglich
    function evenBetterPersonHtml(...inputObj) {
        return `
        <p>Name: ${vorname} ${nachname}<p>
        <p>Alter ${alter}</p>
        `;
    }

    let mickey2 = evenBetterPersonHtml(mickeyObj);
    console.log(mickey2);
    // ACHTUNG  
    // Propertynamen sind nicht bekannt, zugriff hier auf die globalen Variablen: 
    // vorname, nachname und alter
    // <p>Name: Paulchen Panter<p>
    // <p>Alter 33</p>
</script>
```

##### Objektliterale
- https://www.peterkropff.de/site/javascript/objektliterale.htm
```html
<script>
    let b = "B";
    let c = "C";
    let hallo = function () {
        console.log("Hallo");
    }
    let defObj = {
        d: "D",
        e: "E",
        f: "F"
    }

    let myObject = {
        a: "A",
        b: b,
        huhu: function () {
            console.log("huhu");
        },
        // "concise" Property (wenn eine Variable mit gleichem Namen wie das Proprety existiert, 
        //wird diese automatisch übernommen)
        c,
        hallo, //Function, aber als Prop!!!
        ...defObj, //Keys d, e, f werden als eigenständige Properties übernommen, nicht defObj selbst
        // concise Method
        hohoho() {
            console.log("hohoho");
        }
    };

    console.log('myObject:', myObject);
    // myObject: {a: "A", b: "B", c: "C"}
    myObject.huhu();    // huhu
    myObject.hallo();   // Hallo
    myObject.hohoho();  // hohoho

    console.log(myObject.d); // D
</script>
```
- Properties sind nichts anderes als Strings, deswegen können diese auch zur Laufzeit hinzugefügt werden, mittels String, String-Variable oder Rückgabewert einer Funktion
```html
<script>
    let eKey = 'e';
    let generateKey = function () {
        return 'f';
    }

    let myObject = {
        'egal': 'Egal',
        '': 'Echt jetzt?',
        a: "A",
        // computed Property
        [eKey]: "E",
        [generateKey()]: "F"
    };

    // erweitern, so:
    myObject.b = "B";
    // ... oder so:
    myObject['c'] = "c";
    // ... daher geht auch:
    let dKey = 'd';
    myObject[dKey] = "D";

    console.log('myObject:', myObject);
    // myObject: {egal: "Egal", "": "Echt jetzt?", 
    // a: "A", b: "B", c: "c", d: "D", e: "E", f: "F"}

    console.log(myObject['']); //Echt jetzt?
</script>
```

##### Payload
```html
In computing and telecommunications, the payload is the part of transmitted data that is the actual intended message. Headers and metadata are sent only to enable payload delivery. In the context of a computer virus or worm, the payload is the portion of the malware which performs malicious action.
```

##### Symbols
- https://developer.mozilla.org/en-US/docs/Glossary/Symbol
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Symbol
```html
<script>
    // Symbol hat eine IDENTITY! Ist aber KEIN Object
    let mySymbol = Symbol();
    console.log('mySymbol:', mySymbol); // mySymbol: Symbol()
    let myOtherSymbol = Symbol();
    console.log('myOtherSymbol', myOtherSymbol); // myOtherSymbol: Symbol()
    console.log('myOtherSymbol===mySymbol', myOtherSymbol === mySymbol);
    // myOtherSymbol===mySymbol false
        
    // ... und ein Payload
    let myThirdSymbol = Symbol('3. Symbol');
    console.log('myThirdSymbol', myThirdSymbol); // myThirdSymbol Symbol(3. Symbol)
    let nochEinSymbol = Symbol('3. Symbol');
    console.log('nochEinSymbol===myThirdSymbol', nochEinSymbol === myThirdSymbol);
    // nochEinSymbol===myThirdSymbol false
    // Identity und Payload ergeben keine Eindeutigkeit des Symbols

    let myObject = {
        'egal': 'Egal',
        // [{}]: 'Object als Key'  // führt zu nichts
        // aber so:
        [mySymbol]: 'Ich bin rein symbolisch!'
    };
    
    // Stringkeys:
    let dieKeys = Object.keys(myObject);
    console.log('dieKeys:', dieKeys);
    // dieKeys: (8) ["egal"]

    // Schleife for..in: -> Keys greifen nicht auf die Symbols zu, überspringen Sie
    // Keys sind offen zugänglich, Symbols nicht
    for (let key in myObject) {
        console.log('key', myObject[key]);
    }
    // key Egal
</script>
```

####  9.2.5. <a name='Arrays'></a>Arrays
```html
<script>
    // neue STATISCHE Methoden für Array

    // bekannt ist (vielleicht):
    let myArray = [];
    console.log('Array.isArray(myArray):', Array.isArray(myArray));
    // Array.isArray(myArray): true

    // bekannt ist (sicher):
    let zahlen = new Array(3);
    console.log('zahlen', zahlen);
    // oops! -> zahlen (3) [empty × 3]

    // ... dafür gibt's jetzt:
    let myOfArray = Array.of(3, true, 'bla', 17, undefined, null);
    console.log('myOfArray', myOfArray);
    // myOfArray [3, true, "bla", 17, undefined, null]

    // ... was nehme ich, wenn ich KEINE Sequenz habe
    // Array.from(ARRAYAEHNLICH)!!!

    let keinArray = {
        x: "X",
        length: 5,      // length MUSS enthalten sein
        '2': 'die Zwei' // mindestens einen num Key
    }

    let myFromArray = Array.from(keinArray);
    console.log('myFromArray:', myFromArray);
    // myFromArray: [undefined, undefined, "die Zwei", undefined, undefined]
</script>
```

####  9.2.6. <a name='Iterables-Iterator'></a>Iterables -> Iterator
##### for ... of
```html
<script>
    let myArray = ['dies', 'das', 'jenes'];

    // for, forEach

    // ... weil ein Array ein "Iterable" ist:
    for (let value of myArray) { // for..of: Iterable -> Iterator
        console.log(value);
    }
    // dies
    // das
    // jenes

    // wir machen jetzt SELBST einen Iterator:
    let myArrayIterator = myArray.entries();
    console.log('myArrayIterator: ', myArrayIterator);
    // myArrayIterator:  
    // Array Iterator {}:Array Iterator
    // next:ƒ next()
    // Symbol(Symbol.toStringTag):"Array Iterator"
    // __proto__:
    // Symbol(Symbol.iterator):ƒ [Symbol.iterator]()
    // __proto__:Object

    let valueObj1 = myArrayIterator.next();
    console.log('valueObj1: ', valueObj1);
    // valueObj1:  {value: Array(2), done: false, value:(2) [0, "dies"]}
    let valueObj2 = myArrayIterator.next();
    console.log('valueObj2: ', valueObj2);
    // valueObj2:  {value: Array(2), done: false, value:(2) [1, "das"]}
    let valueObj3 = myArrayIterator.next();
    console.log('valueObj3: ', valueObj3);
    // valueObj3:  {value: Array(2), done: false, value:(2) [2, "jenes"]}

    //Ende wird angegeben mit done: true
    let valueObj4 = myArrayIterator.next();
    console.log('valueObj4: ', valueObj4);
    // valueObj4: {value: undefined, done: true}

    // ACHTUNG
    // .next().next() nicht möglich, da der Rückgabetyp kein Iterator ist
    let valueObj5 = myArrayIterator.next().next();
</script>
```

###  9.3. <a name='Funktionenvs.Arrow-Funktionen'></a>Funktionen vs. Arrow-Funktionen

####  9.3.1. <a name='Functions'></a>Functions
```html
<script>
    // bei Functions wurde ein wenig nachgebessert
    let addiere = function (a, b = 0, c = 0) {
        // b = b || 0; // Alternativ zu b=0

        // Enthält nicht die Defaultwerte, enthält nur die wirklich übergebenen Werte
        // impliziter Param 1:
        console.log(arguments); // haben wir

        // impliziter Param 2:            
        console.log(this);

        return a + b;
    };

    let erg = addiere(4);
    console.log('Ergebnis:', erg);
    // Ergebnis: NaN wenn keine Defaultparameter vorhanden sind,
    // mit Default -> Ergebnis: 4

    let myObj = {
        x: "X",
        arrMeth: () => {
            // Originalkontext bleibt in Arrow-Functions bestehen
            console.log('arrMeth:',this); 
        },
        meth: function () {
            console.log('meth:', this);
            // Douglas Crockford (Speichern des Original Kontexts):
            let that = this;

            // ACHTUNG 
            // Function-Functions verlieren ihren Originakontext, außer durch vorherige Speicherung
            let innen = function () {
                console.log('x:', that.x);
            }
            innen(); // call in meth

            let innenMitOriginalKontext = function () {
                console.log('innenMitOriginalKontext:', this);
            }
            innenMitOriginalKontext.call(this);

            let innenNeuerKontext = function () {
                console.log('innen:', this);
            }
            innenNeuerKontext(); // call in meth
            
            let innenArrow = () => {
                // Originalkontext bleibt in Arrow-Functions bestehen
                console.log('innenArrow:', this);
            }
            innenArrow();
        }
    }
    myObj.meth();
    // meth: {x: "X", meth: ƒ}
    // x: X
    // innenMitOriginalKontext: {x: "X", meth: ƒ}
    // innen: Window {postMessage: ƒ, blur: ƒ, focus: ƒ, close: ƒ, frames: Window, …}
    // innenArrow: {x: "X", meth: ƒ}
</script>
```

####  9.3.2. <a name='Arrow-Functions'></a>Arrow-Functions
- kann keinen Namen haben
- ist viel Kompakter als eine normale Function
- hat einen Returnwert
- Originalkontext (this) bleibt bestehen
- Keine Übergabe des Kontexts (this) mittels .call möglich
```html
<script>    
    "use strict";
    console.log('global:', this);
    // global: Window {postMessage: ƒ, blur: ƒ, focus: ƒ, close: ƒ, frames: Window, …}

    //Normale function Mit Name
    let test = function myTest() {
        console.log('this test:', this);
        return 'Test';
    };
    console.log(test()); // Test

    let testArrow = () => 'Test';
    console.log(testArrow()); // Test

    // Speicherung der Arrow-Function in einer Variable
    // x ist der Inputparameter
    let identArrow = (x) => 2 * x;
    console.log(identArrow(5)); // 10

    // a und b sind die Inputparameter
    // mehere Parameter müssen mit () umrandet sein
    let addArrow = (a, b) => a + b;

    let luxusAddArrow = (a, b) => {
        // console.log('arguments', arguments); 
        // arguments is not defined at luxusAddArrow

        console.log('luxusAddArrow:', this); 
        // OriginalKontext bleibt bei der Arrow-Function erhalten,
        // .call ist nicht notwendig, bzw. schon implementiert
        return a + b;
    }

    console.log('typeof test:', typeof test);
    // typeof test: function
    console.log('typeof test.call:', typeof test.call);
    // typeof test.call: function
    console.log('typeof luxusAddArrow:', typeof luxusAddArrow);
    // typeof luxusAddArrow: function
    console.log('typeof luxusAddArrow.call:', typeof luxusAddArrow.call);
    // typeof luxusAddArrow.call: function

    let testObj = { a: "A" };
    // Keine Übergabe des Kontexts mittels .call möglich
    test.call(testObj);
    luxusAddArrow.call(testObj);
    // this test: {a: "A"}
    // luxusAddArrow: Window {postMessage: ƒ, blur: ƒ, focus: ƒ, close: ƒ, frames: Window, …}

    let erg = luxusAddArrow(5, 7);
    console.log(erg);
    // this: Window {postMessage: ƒ, blur: ƒ, focus: ƒ, close: ƒ, frames: Window, …}
    // 12

    let zahlen = [2, 3, 4, 5];

    // Nutzung von Functions
    zahlen.forEach(function (value, index, arrRef) {
        console.log(value);
    });
    // 2, 3, 4, 5

    // Nutzung von Arrow-Functions
    zahlen.forEach(value => console.log(value));
    // 2, 3, 4, 5
</script>
```

###  9.4. <a name='Promises-Chains'></a>Promises -> Chains
- Promise dokumentiert einen asynchronen Vorgang
- Synchron
    - https://developer.mozilla.org/en-US/docs/Glossary/Callback_function
    - https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Global_Objects/Function/call
    - Function-Call
    - ein Wert bzw. Array als Rückgabewert
- Asynchron
    - https://developer.mozilla.org/en-US/docs/Glossary/Promise
    - https://developer.mozilla.org/de/docs/Web/JavaScript/Reference/Global_Objects/Promise
    - cb -> Callback
    - Promise
        - .then (cb)
            - Ist ein Wert sofort vorhanden, verhält es sich synchron
            - Wird ein Promise auf ein then angewendet, verhält sich dieses synchron, auch nachfolgende auf weitere .then-Aufrufe im nächsten Promise
        - .catch (cb)
        - Funktionen in Promises verhalten sich immer asynchron
        - enthält immer eine Function mit 2 Objekten
            - resolve für den value des Erfolgs
            - reject für die reason des Abbruchs (Übergabe des Fehlertexts direkt mit einem String möglich, ohne implementierung)
                - reject kann mit .catch nachdem Promise überschrieben bzw. abgefangen werden
            - Jedes .then bzw. .catch hat einen Input und einen Output-Value, dies muss auch durch die genutzte Funktion aufgenommen werden
            - .catch sollte zumindest im letzten Level/Promise immer gesetzt werden, da sonst Fehler durchrutschen/unbehandelt sind
    - Observable mit .subscribe (cb) als Rückgabewert
- In Skripten wird erst der ganze Code durchlaufen, sodass Funktionen in Funktionen frühestens nach dem kompletten Durchlauf gestartet werden.

```html
<script>
    let prom1 = new Promise(function (resolve, reject) {
        console.log("Konstruiere Promise:", arguments);
        // Konstruiere Promise: 
        // Arguments(2) [ƒ, ƒ, callee: ƒ (resolve, reject), Symbol(Symbol.iterator): ƒ]

        //Funktionen in Promises verhalten sich immer asynchron
        setTimeout(function () {
            console.log('Resolve ... jetzt!');
            resolve(42); // Wert des async Vorgangs
        }, 1000);

        setTimeout(function () {
            console.log('Rejecte ... jetzt!');
            reject('ging halt schief'); //Throw!!!
        }, 2000);
    });

    //then() nimmt 1 oder 2 Function-Objects
    prom1.then(function (value) {
        console.log('Resolved:', value);
        // Resolved: 42 -> wird erst nach 1000ms ausgeführt (erste Funktion "resolve" im Promise)
    }, function (err) {
        console.log('Rejected weil', err)
    });

    setTimeout(function () {
        // ich erhalte immer noch den Wert, des thens!
        prom1.then(function (value) {
            console.log('5s später... Resolved:', value);
            // 5s später... Resolved: 42
        }).catch(function (err) {
            console.log('5s später... Rejected weil ', err)
        });
    }, 5000);

    console.log('Das Promise:', prom1);
    // Das Promise: Promise
    // [[PromiseStatus]]:"pending"
    // [[PromiseValue]]:undefined

    // Ausgabereihenfolge bei keiner resolve Ausführung:
    // Konstruiere Promise: Arguments(2) [ƒ, ƒ, callee: ƒ, Symbol(Symbol.iterator): ƒ]
    // Das Promise: Promise {<pending>}
    // Rejecte ... jetzt!
    // Rejected weil ging halt schief
    // 5s später... Rejected weil  ging halt schief

    // Ausgabereihenfolge bei resolve Ausführung:
    // Konstruiere Promise: Arguments(2) [ƒ, ƒ, callee: ƒ, Symbol(Symbol.iterator): ƒ]
    // Das Promise: Promise {<pending>}
    // Resolve ... jetzt!
    // Resolved: 42
    // Rejecte ... jetzt!
    // 5s später... Resolved: 42
</script>
```

Ausführung mit mehreren Promises hintereinandergeschalten (Nutzung eigener Promises):  
```html
<script>
    let prom1Level1 = new Promise(function (resolve, reject) {
    console.log('Konstruiere Promise:', arguments);

    setTimeout(function () {
        // console.log('Resolve ... jetzt!');
        // resolve(42); // Wert des async Vorgangs
    }, 1000);
    setTimeout(function () {
        console.log('Rejecte ... jetzt!');
        reject('ging halt schief'); // Throw!!
    }, 2000);

    });

    // a) then-Bindung b) nächstes Level zurückgeben
    let promLevel2 = prom1Level1.then(function (val) {
        console.log('Level 1 Resolved:', val);
    }, function (err) {
        console.log('Rejected weil', err);
        // return 'Error in Level 1'; -> Success im nächsten Level, da return fehlt!!!
        throw new Error('Error in Level 1');
    });

    // usw...
    let promLevel3 = promLevel2.then(function (val) {
        console.log('Level 2 Erfolg! Juhu!', val);
        return 'und so geht es weiter!';
    }, function (err) {
        console.log('Level 2 Fehler! Buh!', err);
        // return ODER throw
        throw new Error('Error in Level 2');
    });

    let promLevel4 = promLevel3.then(function (val) {
        console.log('Level 3 Erfolg! Juhu!', val);
    });
    promLevel4.catch(function (err) {
        console.log('Level 3 Fehler! Buh!', err)
    });

    // Ausgabereihenfolge bei keiner resolve Ausführung und ohne val bei promLevel2&3:
    // Konstruiere Promise: Arguments(2) [ƒ, ƒ, callee: ƒ, Symbol(Symbol.iterator): ƒ]
    // Rejecte ... jetzt!
    // Rejected weil ging halt schief
    // Level 2 Erfolg! Juhu!
    // Level 3 Erfolg! Juhu!

    // Ausgabereihenfolge bei keiner reject Ausführung und ohne val bei promLevel2&3:
    // Konstruiere Promise: Arguments(2) [ƒ, ƒ, callee: ƒ, Symbol(Symbol.iterator): ƒ]
    // Resolve ... jetzt!
    // Level 1 Resolved: 42
    // Level 2 Erfolg! Juhu!
    // Level 3 Erfolg! Juhu!

    // Ausgabereihenfolge bei keiner resolve Ausführung mit val in Level 2-4:
    // Konstruiere Promise: Arguments(2) [ƒ, ƒ, callee: ƒ, Symbol(Symbol.iterator): ƒ]
    // Rejecte ... jetzt!
    // Rejected weil ging halt schief
    // Level 2 Fehler! Buh! Error: Error in Level 1 at promises02.html:32
    // Level 3 Fehler! Buh! Error: Error in Level 2 at promises02.html:42
</script>
```

Mehrere Promises durch direkte Hintereinanderschaltung (Promise-Chain/)
```html
<script>    
    // Level 1
    new Promise(function (resolve, reject) {
        console.log('Konstruiere Promise:', arguments);

        setTimeout(function () {
            // console.log('Resolve ... jetzt!');
            // resolve(42); // Wert des async Vorgangs
        }, 1000);
        setTimeout(function () {
            console.log('Rejecte ... jetzt!');
            reject('ging halt schief'); // Throw!!
        }, 2000);
    }// Level 2
    ).then(function (val) {
        console.log('Level1 Resolved:', val);
        return 'so ist das also!';
    }, function (err) {
        console.log('Rejected weil ', err);
        // return 'Error in Level 1'; -> Success nächstes Level!!!
        throw new Error('Error in Level 1');
    }// Level 3
    ).then(function (val) {
        console.log('Level 2 Erfolg! Juhu!', val);
        return 'und so geht es weiter';
    }, function (err) {
        console.log('Level 2 Fehler! Buh!', err);
        // return ODER throw??
        throw new Error('Error in Level 2');
    }// Level 4
    ).then(function (val) {
        console.log('Level 3 Erfolg! Juhu!', val);
    }// Level 5
    ).catch(function (err) {
        console.log('Level 5 Fehler! Buh!', err);
    });

    // Ausgabereihenfolge bei keiner resolve Ausführung mit teilweisem catch und throw der Fehler durch die Levels
    // Konstruiere Promise: Arguments(2) [ƒ, ƒ, callee: ƒ, Symbol(Symbol.iterator): ƒ]
    // Rejecte ... jetzt!
    // Rejected weil  ging halt schief
    // Level 2 Fehler! Buh! Error: Error in Level 1 at promises03.html:30
    // Level 5 Fehler! Buh! Error: Error in Level 2 at promises03.html:38
</script>
```

Resolve Funktion des Promise kann direkt angesprochen werden mit einem Rückgabewert
```html
<script>
    Promise.resolve(42).then(function(val){
            console.log('Level 1 Resolved:', val);
            return 'so ist das also!';
    });
</script>
```

Promises zu einem XMLHttpRequest (Ajax)
```html
<script>
    new Promise(function (resolve, reject) {
        // hier den async Prozess bilden:
        let xhr = new XMLHttpRequest();
        //Async durchführen mittels true, Falsche Datei aufgerufen (nicht existent)
        xhr.open('get', 'data/_personen.json', true);
        //OnLoad bedeutet, der Request ist abgeschlossen
        xhr.onload = function () {
            if (this.status < 400) {
                console.log(this.responseText);
                // ... in die Chain damit
                resolve(this.responseText);
            }
            else {
                // 404 oder so...
                reject('Fehler beim Request' + this.status)
            }
        };
        //Fängt nur grundlegende Fehler, nicht z.B. keine Datei gefunden
        xhr.onerror = function () {
            console.log('Error! Wir haben kein Netz!!');
            reject('Fehler im Network');
        };
        xhr.send();
    }).then(responseText => JSON.parse(responseText))
        .then(jsonObj => jsonObj.personen)
        .then(personen => console.log(...personen))
        .catch(err => console.log(err));

        // Ausgabe mit falscher.json-Datei:
        // promises05.html:28 GET http://127.0.0.1:5500/Seminar%20ECMA6/seminar/data/_personen.json 404 (Not Found)

        // Ausgabe bei Erfolgreichen laden
        // {
        //     "success": true,
        //     "dataProp" : "personen",
        //     "primKey": "mId",
        //     "personen" : [
        //         {"vorname":"Peter", "nachname":"Panter","mId":"m001"},
        //         {"vorname":"Theo", "nachname":"Tiger","mId":"m002"},
        //         {"vorname":"Leo", "nachname":"Löwe", "mId":"m004"},
        //         {"vorname":"Anton", "nachname":"Ameise", "mId":"m007"},
        //         {"vorname":"Bruno", "nachname":"Büffel", "mId":"m006"}
        //     ]
        // }

        // {vorname: "Peter", nachname: "Panter", mId: "m001"}
        // {vorname: "Theo", nachname: "Tiger", mId: "m002"}
        // {vorname: "Leo", nachname: "Löwe", mId: "m004"}
        // {vorname: "Anton", nachname: "Ameise", mId: "m007"}
        // {vorname: "Bruno", nachname: "Büffel", mId: "m006"}
    });
</script>
```

###  9.5. <a name='fetch-API'></a>fetch-API
- https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API
- Ablösung von XML-HTTP Request Objekt
```html
<script>    
    let myFetch = fetch('data/santa.json');
    console.log(myFetch);

    // ... aha, ein Promise!
    myFetch.then(response => {
        // aha, ein Response-Objekt!
        console.log('Hab was!', response);
        // Hab was! Response

        // Daten aus dem Response rausholen:
        // ACHTUNG: Dies KONSUMIERT den Stream bereits!
        // console.log('Ooops, wieder ein Promise!', response.text());
        // was tun mit diesem Promise? Einfach auf dem Stream!
        // Dies konsumiert den Stream!
        // return response.text; // Ich hole Text raus...

        return response.json();
        // Mittels dem zweiten then kommt man erst and brauchbare Daten heran json oder text (entweder, oder)
    }).then(input => console.log(input));
    // Ausgabe: {vorname: "Santa", nachname: "Claus"}

    let myOtherFetch = fetch('data/karl.json', {
        // method:'post' // etc.
    });
</script>
```

Aufruf mehrerer Promises mit Promise.all()
```html
<script>
    let myFetch1 = fetch('data/santa.json').then(response => response.json());
    console.log(myFetch1);
    let myFetch2 = fetch('data/karl.json').then(response => response.json());
    console.log(myFetch2);
    let myFetch3 = fetch('data/frida.json').then(response => response.json());
    console.log(myFetch3);

    console.log(Promise.all([42, 17])
        .then(response => console.log(response)));
    // (2) [42, 17]

    console.log(Promise.all([myFetch1, myFetch2, myFetch3])
        .then(response => console.log(response)));
    // [{…}, {…}, {…}]
    // 0: {vorname: "Santa", nachname: "Claus"}
    // 1: {vorname: "Karl", nachname: "Karpfen"}
    // 2: {vorname: "Frida", nachname: "Forelle"}

    Promise.all([myFetch1, myFetch2, myFetch3])
        .then(([santa, karl, frida]) => {
            console.log('Santa:', santa);
            console.log('Karl:', karl);
            console.log('Frida:', frida);
            return {
                personen: [santa.vorname, karl.vorname, frida.vorname]
            }
        }).then(personen => console.log(personen));
    // Santa: {vorname: "Santa", nachname: "Claus"}
    // Karl: {vorname: "Karl", nachname: "Karpfen"}
    // Frida: {vorname: "Frida", nachname: "Forelle"}
    // personen: (3) ["Santa", "Karl", "Frida"]
</script>
```

###  9.6. <a name='Generatoren'></a>Generatoren
###  9.7. <a name='class-Keywordvs.Konstruktor'></a>class-Keyword vs. Konstruktor
###  9.8. <a name='Vererbung'></a>Vererbung
###  9.9. <a name='ModuleWebpackundTypeScript'></a>Module (Webpack und TypeScript)
###  9.10. <a name='Observables'></a>Observables

##  10. <a name='Typescript'></a>Typescript
- https://www.typescriptlang.org/

###  10.1. <a name='Decorators'></a>Decorators
###  10.2. <a name='Types'></a>Types
###  10.3. <a name='Interfaces'></a>Interfaces
###  10.4. <a name='TS-Classes'></a>TS-Classes
###  10.5. <a name='Generics'></a>Generics