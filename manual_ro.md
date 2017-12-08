[![](http://orobo.go.ro:5500/file/JZXXMo5N38iwgfNAG/0.2/notemplate)](http://orobo.go.ro:5500/browse/file/JZXXMo5N38iwgfNAG/1/3)

# Orobo.ro

## Despre

Oroboro este o platformă deschisă pentru proiectarea colaborativă în SVG (grafică vectorială scalabilă).

## Cum se utilizează acest manual

* (!) = Facilitate la locul de muncă

## Bug-uri cunoscute

![](http://orobo.go.ro:5500/images/tutorial/fileinfo.png)

* Atunci când nu se poate selecta un element / grup, după o acțiune, vă rugăm să faceți clic din meniul de control pe butonul reload al fișierului sau reîncărcarea paginii.
* Atunci când creați un grup parametrizat (cu PointSymmetry, LineSymmetry, ItemArray) puteți selecta grupul numai prin selectarea elementului original (calea) utilizat pentru crearea sau prin utilizarea Shift + trageți mouse-ul.

## Caracteristici unice

* Colaborarea în direct (orice modificare făcută de un designer va fi redată instant pentru toţi utilizatorii cu permisiuni de vizionare sau editare asupra documentului)

[![](http://orobo.go.ro:5500/images/tutorial/filebrowser2.png)](http://orobo.go.ro:5500/browse/file/ZzhbWoiGpMEoA9i3M/1/5)
[![](http://orobo.go.ro:5500/images/tutorial/filebrowser3.png)](http://orobo.go.ro:5500/browse/file/ZzhbWoiGpMEoA9i3M/1/5)

* Bază de date on-line a operelor reutilizabile (oricine poate reutiliza lucrări sau părți din baza de date publică)

* Functie de Morphing pentru animații (în lucru)
* Animație 2D (în lucru)
* grafica SVG turtle
* Redare fractal şi vectorială de reguli matematice
* Operații booleene pe poligoane, cu posibilitatea de a transforma elemente cu curbe în poligoane cu mai multe linii
* Mod de prezentare pentru lucrările create (de asemenea, poate fi folosit ca o aplicatie Power Point sau ca o galerie de portofoliu)
* Protocoale de gestionare a drepturilor de atribuire
* Gratuit


## De ce SVG

[![](http://orobo.go.ro:5500/file/mQa8FQtSDWpLaYy38/0.2/notemplate)](http://orobo.go.ro:5500/filem/mQa8FQtSDWpLaYy38)

* Toate problemele legate de scalarea la diferite rezoluții (pentru proiectarea aplicațiilor mobile, componente de jocuri etc.) au dispărut. Pot fi scalate la infinit!
* Nu există pixeli urâţi când măriți
* [Semantic Web](http://www.w3.org/standards/semanticweb/) prietenos
* Posibilități nelimitate de extindere: animație, benzi desenate, atlase cu componente SVG și straturi de conectori și etichete.

## Open Design & Open Source

Acesta este un proiect open source, sub licență GPLv3. Oroboro va rămâne liber pentru oricine care contribuie comunitaţii prin eliberarea muncii lor sub o licență comparabilă. Ne gandim la gazduirea unui numar limitat de lucrari private gratuit.

Noi dorim să construim o comunitate de design axată pe abilitarea de colaborare și reutilizare, la fel ca comunitățile open source pentru programatori. Imparţiţi pentru a primi la rândul vostru și pentru a va face  observat.


## Cum să incepeţi

* [Creaţi un cont](http://orobo.go.ro:5500/) și clonaţi un fișier din FileBrowser cu [![](http://orobo.go.ro:5500/file/menuItemClone/0.04 )](http://orobo.go.ro:5500/filem/menuItemClone) sau duceţi-vă pe [Playground](http://orobo.go.ro:5500/filem/eGfQyh6jCqxeEYmex)

![](http://orobo.go.ro:5500/images/tutorial/addElement.png)

* (singura metodă de creeare a unui element) Crearea de noi elemente se face prin apăsarea butonului addElement din filebrowser și apoi editarea lui (aspect, geometrie, punctele path-ului etc.)


[![](http://orobo.go.ro:5500/images/tutorial/filebrowser4.png)](http://orobo.go.ro:5500/browse/file/4wtih642DRCZ5eFxq/1/5)

## Filebrowser

### Meniu Filebrowser

#### [![](http://orobo.go.ro:5500/file/menuItemEdit/0.04)](http://orobo.go.ro:5500/filem/menuItemEdit) Editare fișier
#### [![](http://orobo.go.ro:5500/file/menuItemClone/0.04)](http://orobo.go.ro:5500/filem/menuItemClone) Clonare fișier
#### [![](http://orobo.go.ro:5500/file/menuItemDelete/0.04)](http://orobo.go.ro:5500/filem/menuItemDelete) Ștergere fișier
#### [![](http://orobo.go.ro:5500/file/menuItemExport/0.04)](http://orobo.go.ro:5500/filem/menuItemExport) Export fișier
#### [![](http://orobo.go.ro:5500/file/menuItemSearch/0.04)](http://orobo.go.ro:5500/filem/menuItemSearch) Vizualizare fișier

### Iconiţele din Filebrowser

#### [![](http://orobo.go.ro:5500/file/menuItemFolder/0.04)](http://orobo.go.ro:5500/filem/menuItemFolder) Folder

Această pictogramă vă arată că fișierul are copii structurale sub ea.

#### [![](http://orobo.go.ro:5500/file/menuItemDisector/0.04)](http://orobo.go.ro:5500/filem/menuItemDisector) Director

Această pictogramă vă arată că fișierul are grupuri sub ea pe care le puteți naviga, până la elementele pe care le conține.

![](http://orobo.go.ro:5500/images/tutorial/breadcrumbs.png)

#### FileBrowser Breadcrumbs

Aceasta este calea folderului curent, cu rădăcina Oroboro ca primul miez.


## Editorul Oroboro

### Caracteristici generale

* Mărire și micșorare cu mouse-ul
* Pan făcând clic pe fundalul alb și trăgând
* De / blocare pan & zoom făcând clic pe pictograma de blocare  [![](http://orobo.go.ro:5500/file/2j4FekqSWwTfFGSeX/0.02)](http://orobo.go.ro:5500/filem/2j4FekqSWwTfFGSeX) din dreapta jos
* Minimap a documentului (fișier) și pânza (fundal alb), în colțul din dreapta jos
* Selectare elemente făcând clic pe acestea, selectii multiple cu Shift + clic pe acestea sau prin utilizarea Shift + tragere.


### Articole
#### Tipuri de elemente

##### Cale

###### [![](http://orobo.go.ro:5500/file/7fFtAL9AgJaWp9G7q/0.04)](http://orobo.go.ro:5500/filem/7fFtAL9AgJaWp9G7q) Cale simplă

* Doar linii drepte: 'M870 512L153 925L153 98L870 512Z'
* Important pentru a face [operații booleene](http://en.wikipedia.org/wiki/Boolean_operations_on_polygons))

###### [![](http://orobo.go.ro:5500/file/eAywEx5e5cNwe6BpC/0.04)](http://orobo.go.ro:5500/filem/eAywEx5e5cNwe6BpC) Cale Complexă

* Cu toate curbele simplificate pentru curbe Bezier cubice: 'M112 512C112 291 291 112 512 112 912 291 112C732 912 733 733 912 512C912 512 912C291 912 112 733 112 512Z')

##### [![](http://orobo.go.ro:5500/file/sh8BiMTztrdGXaPsS/0.04)](http://orobo.go.ro:5500/filem/sh8BiMTztrdGXaPsS) Raster Image
##### [![](http://orobo.go.ro:5500/file/AETqEKboPMEEnPHkj/0.04)](http://orobo.go.ro:5500/filem/AETqEKboPMEEnPHkj) Text
##### [![](http://orobo.go.ro:5500/file/44W6oHqR5woPp474S/0.04)](http://orobo.go.ro:5500/filem/44W6oHqR5woPp474S) Cale parametrizată

###### Căi simple parametrizate
###### Căi complexe parametrizate
Căi bazate pe Funcții ######

####### [![](http://orobo.go.ro:5500/file/2oBer6NfjwHpWjYXm/0.04)](http://orobo.go.ro:5500/filem/2oBer6NfjwHpWjYXm) Grafice carteziene pentru funcții

De exemplu, `3 * Math.sin (3 * x)` este funcția utilizată pentru

[![](http://orobo.go.ro:5500/file/2oBer6NfjwHpWjYXm/0.2)](http://orobo.go.ro:5500/filem/2oBer6NfjwHpWjYXm)

####### [![](http://orobo.go.ro:5500/file/srWR38tZRknYDeSbJ/0.04)](http://orobo.go.ro:5500/filem/srWR38tZRknYDeSbJ)  Grafice polare pentru Funcții

De exemplu, `Math.cos (7/4 * x)` este funcția utilizată pentru

[![](http://orobo.go.ro:5500/file/i5CppdgDDB5LpKn3S/0.2)](http://orobo.go.ro:5500/filem/i5CppdgDDB5LpKn3S)

Mai multe funcții pentru spirala archimedeană și trandafiri polari la [graficele de ecuații polare](http://www.mathamazement.com/Lessons/Pre-Calculus/06_Additional-Topics-in-Trigonometry/graphs-of-polar-equations.html). Asigurați-vă că oferiţi o gamă suficient de mare pentru unghiul polar theta.


##### [![](http://orobo.go.ro:5500/file/5zk5HoNdJXisEcYMD/0.04)](http://orobo.go.ro:5500/filem/5zk5HoNdJXisEcYMD) Formulele

* Latex Input

De exemplu, `e = mc ^ 2` este formula utilizată pentru

[![](http://orobo.go.ro:5500/file/5zk5HoNdJXisEcYMD/0.2)](http://orobo.go.ro:5500/filem/5zk5HoNdJXisEcYMD)

##### [![](http://orobo.go.ro:5500/file/arHQ6fwEmaZmwQCbu/0.04)](http://orobo.go.ro:5500/filem/arHQ6fwEmaZmwQCbu) QRcode
##### [![](http://orobo.go.ro:5500/file/JrTR22Q3d56xWRkc2/0.04)](http://orobo.go.ro:5500/filem/JrTR22Q3d56xWRkc2) Markdown
##### [![](http://orobo.go.ro:5500/file/TQWiptxM8BDzyR3uv/0.04)](http://orobo.go.ro:5500/filem/TQWiptxM8BDzyR3uv) iFrame
##### [![](http://orobo.go.ro:5500/file/CW976umbSxzA53byY/0.04)](http://orobo.go.ro:5500/filem/CW976umbSxzA53byY) Canvas
##### [![](http://orobo.go.ro:5500/file/Pcp7avZpjfQ3fZXCb/0.04)](http://orobo.go.ro:5500/filem/Pcp7avZpjfQ3fZXCb) HTML
##### [![](http://orobo.go.ro:5500/file/d8RDkZdNnHZipaCbK/0.04)](http://orobo.go.ro:5500/filem/d8RDkZdNnHZipaCbK) NestedSvg

#### Articole speciale

##### [![](http://orobo.go.ro:5500/file/tJGWoeZnxtAsoDuvy/0.04)](http://orobo.go.ro:5500/filem/tJGWoeZnxtAsoDuvy) Conector
##### [![](http://orobo.go.ro:5500/file/arHQ6fwEmaZmwQCbu/0.04)](http://orobo.go.ro:5500/filem/arHQ6fwEmaZmwQCbu) Gradient

#### Modificare a elementelor

![](http://orobo.go.ro:5500/images/tutorial/appearance.png)

##### Aspectul Elementelor

* Umplere: culoare, opacitate
* Contur: culoare, latime, dasharray, linecap, linejoin, opacitate
* Opacitate generală

##### Poziţia Elementelor

![](http://orobo.go.ro:5500/images/tutorial/geometry.png)

###### Comenzile meniului

Controlul exact cu valori numerice: coordonate x,y, coordonatele centrului, lățime, înălțime, unghiul de rotație.

###### Cu mouse-ul

* Tragere
* Selectare
* Shift + trageți pentru menținerea raportul.

##### perspectivă 3D

După selectarea unui element, faceți clic pe butonul din dreapta jos [![](http://orobo.go.ro:5500/file/isqRsRCPhGeSPNhoh/0.03)](http://orobo.go.ro:5500/file/isqRsRCPhGeSPNhoh) sau apăsați pe Alt + 3. Shift + trageți pentru menținerea raportul.

Acest lucru poate fi folosit pentru a crea umbre. De exemplu: [![](http://orobo.go.ro:5500/file/gXJDaFEbjPbdNTdfp/0.03)](http://orobo.go.ro:5500/filem/gXJDaFEbjPbdNTdfp) clonare formă , se aplică un 0,5 opacitate / culoare gri click pe butonul de perspectiva, apoi click pe unul dintre puncte si trage-ti pana obtine-ti forma dorită :)

[![](http://orobo.go.ro:5500/file/nzumC3jDDPK6jnPTZ/0.3)](http://orobo.go.ro:5500/filem/nzumC3jDDPK6jnPTZ)

[![](http://orobo.go.ro:5500/file/Caj6Gda3CFZGnvn8v/0.2)](http://orobo.go.ro:5500/file/Caj6Gda3CFZGnvn8v)

##### Fine Tuning Căi (path-uri)

Caleaeste directionata cu ajutorul mouse-lui  (după selectarea unui element, faceți click pe butonul din stânga jos [![](http://orobo.go.ro:5500/file/MeSC479WX69b9GATS/0.03)](http://orobo.go.ro:5500/file/MeSC479WX69b9GATS) sau apăsați Alt + P):

* [![](http://orobo.go.ro:5500/file/P2BZPG7qy42sWFrFA/0.02)](http://orobo.go.ro:5500/filem/P2BZPG7qy42sWFrFA) = punctul de cale
* [![](http://orobo.go.ro:5500/file/uzrFnBmQCxoicpGS6/0.02)](http://orobo.go.ro:5500/filem/uzrFnBmQCxoicpGS6) = primul punct (subcalea)
* [![](http://orobo.go.ro:5500/file/4Wb7jMkaZxEBFwkqD/0.02)](http://orobo.go.ro:5500/filem/4Wb7jMkaZxEBFwkqD) = adaugă un punct nou
* [![](http://orobo.go.ro:5500/file/Qys966QrtRMGcYRDK/0.02)](http://orobo.go.ro:5500/filem/Qys966QrtRMGcYRDK) = atractor curba


* Informaţii puncte de cale si atractori curbă
* Șterge puncte de cale - dublu click pe [![](http://orobo.go.ro:5500/file/P2BZPG7qy42sWFrFA/0.02)](http://orobo.go.ro:5500/filem/P2BZPG7qy42sWFrFA)
* Șterge curba - dublu click pe una din curbele lui  [![](http://orobo.go.ro:5500/file/Qys966QrtRMGcYRDK/0.02)](http://orobo.go.ro:5500/filem/Qys966QrtRMGcYRDK)
* Adaugă punct simplu (linie dreaptă) - click pe  [![](http://orobo.go.ro:5500/file/4Wb7jMkaZxEBFwkqD/0.02)](http://orobo.go.ro:5500/filem/4Wb7jMkaZxEBFwkqD)
* Adaugă punct curba (2 curbe) - Shift + click pe [![](http://orobo.go.ro:5500/file/4Wb7jMkaZxEBFwkqD/0.02)](http://orobo.go.ro:5500/filem/4Wb7jMkaZxEBFwkqD)


Punctul de control al căilor din meniul (Puncte submeniu) (!) - fiecare punct poate fi mutat la coordonatele furnizate.


### Grupuri
#### Tipuri de grupuri

##### Layer

Fiecare fișier are cel puțin un strat sub care sunt grupate elementele.

##### [![](http://orobo.go.ro:5500/file/cRiQceYEsBNr2MuAx/0.04/notemplate)](http://orobo.go.ro:5500/filem/cRiQceYEsBNr2MuAx) Grup simplu

Orice grup svg clasic, care conține elemente: `<g> </ g>`

##### Grup parametrizat

Grupuri speciale care au funcții care pot sa dicteze comportamentul / tiparele elementelor conținute

#### Grupuri de editare
##### Grupul Transform

Valori neutre matrice: 1,0,0,1,0,0. Valoare semnificație:
1. scală pe axa x
2. oblic pe axa x
3. oblic pe axa y
4. scara pe axa y
5. traduce pe axa x
6. traduce pe axa y

### Fișiere
#### Tipuri de fisiere

##### [![](http://orobo.go.ro:5500/file/9tQyfodBmtdRpcEML/0.04/notemplate)](http://orobo.go.ro:5500/filem/9tQyfodBmtdRpcEML) SVG
##### [![](http://orobo.go.ro:5500/file/QLjb9RprCCEPo5LFk/0.04/notemplate)](http://orobo.go.ro:5500/filem/QLjb9RprCCEPo5LFk) PNG
##### [![](http://orobo.go.ro:5500/file/k6oThcBq7HrPE2hEN/0.04/notemplate)](http://orobo.go.ro:5500/filem/k6oThcBq7HrPE2hEN) JPEG
##### [![](http://orobo.go.ro:5500/file/E2fB5224ac5mkDcro/0.04/notemplate)](http://orobo.go.ro:5500/filem/E2fB5224ac5mkDcro) JavaScript
##### [![](http://orobo.go.ro:5500/file/xNdm3hx4M3WLhGd7x/0.04/notemplate)](http://orobo.go.ro:5500/filem/xNdm3hx4M3WLhGd7x) CSS
##### [![](http://orobo.go.ro:5500/file/fhTRHbcDGmHxFEdM4/0.04/notemplate)](http://orobo.go.ro:5500/filem/fhTRHbcDGmHxFEdM4) Text

#### Tipuri de fișiere speciale

##### [![](http://orobo.go.ro:5500/file/9soqDH7MhEw8rcXBx/0.04/notemplate)](http://orobo.go.ro:5500/filem/9soqDH7MhEw8rcXBx) Format


#### Editarea fișierelor

[![](http://orobo.go.ro:5500/images/tutorial/fileinfo.png)]

##### Informații fișier

Info submeniu: creator, rezoluție, cale, titlul fișierului, permisiuni de editare, răsfoire fişier în File Browser, reîncărcați fișierul, resetview (Revenirea camerei in poziţia iniţială) .

Permisiuni fișier ######

Info submeniu. Adăugați adrese de e-mail separate prin virgulă:,
Adresele de e-mail trebuie să aibă un cont oroboro.

[![](http://orobo.go.ro:5500/images/tutorial/fileactions.png)]



Operații generale ###

[![](http://orobo.go.ro:5500/images/tutorial/actions.png)](http://orobo.go.ro:5500/filem/2ME5he36GPCNCaFhY)

** din meniul de control, operațiunile sunt în submeniul Acțiuni; unele dintre ele au comenzi rapide de la tastatură

##### [![](http://orobo.go.ro:5500/file/bvDoMyozQm4cBLrFK/0.04/notemplate)](http://orobo.go.ro:5500/filem/bvDoMyozQm4cBLrFK) Codul sursă

* Vizualiza și editarea codului sursă SVG a fișierului: faceți clic pe `source` (meniul de control al fișierului)
* vizualiza și edita codul sursă de 1 /> articole și grupuri: selectați obiecte / grupuri, apoi faceți clic pe `source` (meniu de control)

##### [![](http://orobo.go.ro:5500/file/EqPANkXeM2cFSKfTC/0.04/notemplate)](http://orobo.go.ro:5500/filem/EqPANkXeM2cFSKfTC) Clone

Clonare obiecte / grupuri în interiorul fișierului, în cadrul elementului original.

* Selectați elemente / grupuri, apoi faceți clic pe `Clone` (meniu de control)
* Selectaţi elemente / grupuri, apoi apăsați pe Alt + C

##### [![](http://orobo.go.ro:5500/file/ggFTeKHeA8vGFn9Z5/0.04/notemplate)](http://orobo.go.ro:5500/filem/ggFTeKHeA8vGFn9Z5) Ștergere

Ștergeți elementele / grupuri din dosar.

* Selectaţi elemente / grupuri, apoi faceți clic pe `Delete` (meniu de control)
* Selecta elemente / grupuri, apoi apăsați pe Alt + D

##### [![](http://orobo.go.ro:5500/file/Bg5p7KxDexx7wp2vr/0.04/notemplate)](http://orobo.go.ro:5500/filem/Bg5p7KxDexx7wp2vr) Se aduce la Față

Adu element / grup în față, care suprapun alte elemente (!)

* Selectaţi element / grup, apoi faceți clic pe `toFront` (meniu de control)
* Selectaţi element / grup, apoi apăsați pe Alt + F

##### [![](http://orobo.go.ro:5500/file/STsJzqTqRyi6JX8rN/0.04/notemplate)](http://orobo.go.ro:5500/filem/STsJzqTqRyi6JX8rN) Trimite Înapoi

Trimite element / grup în spate, fiind suprapus de toate celelalte elemente (!)

* Selectaţi element / grup, apoi faceți clic pe (meniu de control) `toBack`
* Selectaţi element / grup, apoi apăsați pe Alt + B

##### [![](http://orobo.go.ro:5500/file/QWz5HkQwwqgqNpNZJ/0.04/notemplate)](http://orobo.go.ro:5500/filem/QWz5HkQwwqgqNpNZJ) Selectați părinte grup

Selectați grupul care conține elementul / grup (dacă nu este un strat).

* Selectaţi element / grup, apoi faceți clic pe `toGroup` (meniu de control)
* Selectaţi element / grup, apoi apăsați pe Alt + Săgeată în sus

##### [![](http://orobo.go.ro:5500/file/cRiQceYEsBNr2MuAx/0.04/notemplate)](http://orobo.go.ro:5500/filem/cRiQceYEsBNr2MuAx) Creați un grup principal

Creați un grup care conține elementele selectate / grupuri

* Selectați elemente / grupuri, apoi faceți clic pe `group` (meniu de control)
* Selectați elemente / grupuri, apoi apăsați pe Alt + G

##### [![](http://orobo.go.ro:5500/file/cRiQceYEsBNr2MuAx/0.04/notemplate)](http://orobo.go.ro:5500/filem/cRiQceYEsBNr2MuAx) Import Selector

Creați un grup care conține elementul original și selectorul prezent în acel moment (selectorul care poate fi tras, selectorul de puncte, selectorul 3D).

* Selectați element, apoi faceți clic pe `importSelector` (meniu de control)
* Selectați elementul, apoi apăsați pe Alt + I

#### Operațiuni

##### Operațiuni Path

###### [![](http://orobo.go.ro:5500/file/4YptMH9My37sYj5mm/0.04/notemplate)](http://orobo.go.ro:5500/filem/4YptMH9My37sYj5mm) Închide / Deschide calea

Închide / deschide calea

* Selectați calea, apoi faceți clic pe `closeOpen` (meniu de control) pentru opțiunea de comutare

###### [![](http://orobo.go.ro:5500/file/fEv7RE3LdYpQ4Q8TW/0.04/notemplate)](http://orobo.go.ro:5500/filem/fEv7RE3LdYpQ4Q8TW) Răsucire Orizontală

Răsucire element pe orizontală

* Selectați calea, apoi faceți clic pe `mirrorH` (meniu de control)

###### [![](http://orobo.go.ro:5500/file/n6yMHex8KcBPBC9Ts/0.04/notemplate)](http://orobo.go.ro:5500/filem/n6yMHex8KcBPBC9Ts) Răsucire Herticală

Răsucire element pe verticala

* Selectați calea, apoi faceți clic pe `mirrorV` (meniu de control)

###### [![](http://orobo.go.ro:5500/file/8JyQRohBkBZvzRwEp/0.04/notemplate)](http://orobo.go.ro:5500/filem/8JyQRohBkBZvzRwEp) Inversare Căi

Inversarea căilor.

* selectați calea, apoi faceți clic pe `reverse` (meniu de control)

 ###### [![](http://orobo.go.ro:5500/file/ngiimZYX6f5FtJdY2/0.04/notemplate)](Http://orobo.go.ro:5500/filem/ngiimZYX6f5FtJdY2) Intersectare Căi

Join 1 /> căi într-o singură formă cu subpaths.

* Shift selectați căi, apoi faceți clic pe `joinPaths` (meniu de control)

###### [![](http://orobo.go.ro:5500/file/7jLp2apKztDxd6Siv/0.04/notemplate)](http://orobo.go.ro:5500/filem/7jLp2apKztDxd6Siv) Split, Subpaths din Cale

subpaths separate pentru a forma elemente separate.

* Selectați calea, apoi faceți clic pe `splitPaths` (meniu de control)

###### [![](http://orobo.go.ro:5500/file/CBH7KZbutnGPknCNf/0.04/notemplate)](http://orobo.go.ro:5500/filem/CBH7KZbutnGPknCNf) Grup Point Symmetry

Creați un __Parametrized Group__ folosind calea selectată și un punct cu coordonate x și y pentru construirea de clone simetrice ale căii, în raport cu punctul dat.

[![](http://orobo.go.ro:5500/file/AZrdxkdEjk3yCgLpJ/0.2/notemplate)](http://orobo.go.ro:5500/filem/AZrdxkdEjk3yCgLpJ) [![](http://orobo.go.ro:5500/file/A5TCgpQdRXeQus9iu/0.2/notemplate)](http://orobo.go.ro:5500/filem/A5TCgpQdRXeQus9iu) [![](http://orobo.go.ro:5500/file/nPW3sGvBa57m87d7d/0.2/notemplate)](http://orobo.go.ro:5500/filem/nPW3sGvBa57m87d7d) [![](http://orobo.go.ro:5500/file/SzvW7PjwnchXPFwnj/0.2/notemplate)](http://orobo.go.ro:5500/filem/SzvW7PjwnchXPFwnj)

* Selectați calea, apoi faceți clic pe `pointSymmetry` (meniu de control)
* Grupul parametrizat va avea toate caracteristicile prezentate în subcapitolul parametrizat Group.

Cu această caracteristică se pot realiza spirale.

###### [![](http://orobo.go.ro:5500/file/AnNnDaf2HrmyHBTYE/0.04/notemplate)](http://orobo.go.ro:5500/filem/AnNnDaf2HrmyHBTYE) Grup Line Symmetry

[![](http://orobo.go.ro:5500/file/h2bNyDpySrwrsG5N2/0.2)](http://orobo.go.ro:5500/filem/h2bNyDpySrwrsG5N2) [![](http://orobo.go.ro:5500/file/KBtAqH623Src52i96/0.2)](http://orobo.go.ro:5500/filem/KBtAqH623Src52i96) [![](http://orobo.go.ro:5500/file/zrsJTCFpCXKYh8dxE/0.2)](http://orobo.go.ro:5500/filem/zrsJTCFpCXKYh8dxE)

Creați un __Group Parametrizat__ folosind calea selectată și o anumită linie pentru construirea de clone simetrice ale căii, în raport cu linia.

* Selectați calea, apoi faceți clic pe `lineSymmetry` (meniu de control)
* Grupul parametrizat va avea toate caracteristicile prezentate în subcapitolul parametrizat Group.

###### [![](http://orobo.go.ro:5500/file/jLXYjXxyTTecoYv9C/0.04/notemplate)](http://orobo.go.ro:5500/filem/jLXYjXxyTTecoYv9C) Grup Item Array

[![](http://orobo.go.ro:5500/file/2CC2YmbKH9pzL4rb8/0.2)](http://orobo.go.ro:5500/filem/2CC2YmbKH9pzL4rb8) [![](http://orobo.go.ro:5500/file/xkYrgQSscp4yoKM9v/0.2)](http://orobo.go.ro:5500/filem/xkYrgQSscp4yoKM9v) [![](http://orobo.go.ro:5500/file/iQdYEY4DHG5EJkTLd/0.2)](http://orobo.go.ro:5500/filem/iQdYEY4DHG5EJkTLd)

Creați un __Parametrized Group__ folosind calea aleasă pentru construirea de clone ale căii aranjate într-un format de matrice .

* Selectați calea, apoi faceți clic pe `itemArray` (meniu de control)
* Grupul parametrizat va avea toate caracteristicile prezentate în subcapitolul parametrizat Group.

Puteți face acum cu ușurință modele și dale și chiar mozaicare.

#### Operațiuni Path combinate

Putem combina operațiunile de mai sus pentru a crea obiecte complexe și modele.

[![](http://orobo.go.ro:5500/file/JoXEZALTNoz9JgHLg/0.2/notemplate)](http://orobo.go.ro:5500/filem/JoXEZALTNoz9JgHLg)

Acest model de tip fagure a fost creat folosind Item Array cu [![](http://orobo.go.ro:5500/file/zS26Fh445Wqdu4ND3/0.1)](http://orobo.go.ro:5500/filem/zS26Fh445Wqdu4ND3) - obținută prin utilizarea Point Symmetry cu [![](http://orobo.go.ro:5500/file/2DzGLexiPZYpzSt69/0.1)](http://orobo.go.ro:5500/filem/2DzGLexiPZYpzSt69)

[![](http://orobo.go.ro:5500/file/tSwejJnAEKPBSazp6/0.2/notemplate)](http://orobo.go.ro:5500/filem/tSwejJnAEKPBSazp6)

Acest model a fost creat folosind Item Array cu [![](http://orobo.go.ro:5500/file/zS26Fh445Wqdu4ND3/0.1)](http://orobo.go.ro:5500/filem/zS26Fh445Wqdu4ND3) - obținută prin utilizarea Punctul Symmetry cu [![](http://orobo.go.ro:5500/file/zS26Fh445Wqdu4ND3/0.1)](http://orobo.go.ro:5500/filem/zS26Fh445Wqdu4ND3)

[![](http://orobo.go.ro:5500/file/z5CTy2uBPegog5Bnv/0.2)](http://orobo.go.ro:5500/filem/z5CTy2uBPegog5Bnv)

Această spirală a fost creat folosind point symmetry și Funcții Polare. [![](http://orobo.go.ro:5500/file/i5CppdgDDB5LpKn3S/0.1)](http://orobo.go.ro:5500/filem/i5CppdgDDB5LpKn3S) este generat de `Math.cos (7 / 4 * x) `(arunca o privire la intervalul unghiului polar). Dacă vom selecta această cale și faceți clic pe `genPath` din meniu, vom obține un path obişnuit, care poate fi utilizat cu toate acestea: [![](http://orobo.go.ro:5500/file/ssMswfKiZfWLseY3b/0.1)](http://orobo.go.ro:5500/filem/ssMswfKiZfWLseY3b). În acest caz, prin selectarea și făcând clic pe `pointSymmetry` din meniu.

##### Operațiuni Path simple

Operațiuni Boolean ######

####### [![](http://orobo.go.ro:5500/file/ACKSA92hnv8Xm7TdQ/0.04/notemplate)](http://orobo.go.ro:5500/filem/qDRbePmMAJgGhgzcg) Uniune

Creează o altă cale de unirea căile selectate.

* selectați căi, apoi faceți clic pe `union` (meniu de control)

####### [![](http://orobo.go.ro:5500/file/5j8hem49B5c8Wmf8w/0.04/notemplate)](http://orobo.go.ro:5500/filem/qDRbePmMAJgGhgzcg) Diferență

Creează un alt articol din diferența dintre căile.

* Selectați căi, apoi faceți clic pe `difference` (meniu de control)


####### [![](http://orobo.go.ro:5500/file/Li8SBbTjjfmwdhAg8/0.04/notemplate)](http://orobo.go.ro:5500/filem/qDRbePmMAJgGhgzcg) XOR

Creează un alt articol din XOR căilor.

* Selectați căi, apoi faceți clic pe `xor` (meniu de control)


####### [![](http://orobo.go.ro:5500/file/MTeMg4fEryLvaSoBX/0.04/notemplate)](http://orobo.go.ro:5500/filem/MTeMg4fEryLvaSoBX) Intersecție

Creează un alt articol din intersecția căilor.

* Selectați căi, apoi faceți clic pe `intersection` (meniu de control)


##### Operațiuni Path complexe

###### [![](http://orobo.go.ro:5500/file/cSYwm8DpLd5iLhL7v/0.04/notemplate)](http://orobo.go.ro:5500/filem/cSYwm8DpLd5iLhL7v) Simplificați

* Transforma curbele în mai multe linii drepte
* Numărul de puncte afișate în colțul din stânga sus al ecranului
* Acest lucru este foarte important pentru imitarea operații booleene cu trasee complexe: vă simplifica în primul rând calea complexă și transformarea acesteia într-o cale simplă și apoi să-l utilizați pentru unire, XOR etc.

* selectați calea, apoi faceți clic pe `simplify` (meniu de control)

[![](http://orobo.go.ro:5500/file/mk49q5vXnGB6qNoNH/0.2/notemplate)](http://orobo.go.ro:5500/filem/mk49q5vXnGB6qNoNH)

Aceasta este o cale simplă - un cerc format din linii drepte, cu 104 de puncte.


#### Morphing 2 Căi

* Cadre Morph: Shift + clic pe elemente + selectați tipul Morph (morphopt) + mouse-ul poziția tragere Morph (morphpos) -> primul element dat click = sursa, doilea element dat click = destinație;

#### Animație

(!) Mai multe tipuri de animație între trasee simple bazate pe caracteristica Morph


#### Operations Group

Faceți clic pe grup / faceți clic pe element din grup + Alt + Săgeată în sus pentru selectarea unui grup.

##### Transformarea

Transformare submeniul din meniul de control controlează opțiunile de transformare pentru grup. Transformări sunt întotdeauna aplicate în subteran ca matrice.

###### Reset Matrix

Resetarea matrice la valori neutre.

* selectați grupul, apoi faceți clic pe `reset` (meniu de control)

###### Modificare Matrix

* Grup select, apoi șir edita matrice și apoi apăsați Enter

###### Transform Opțiuni

Chiar dacă se pare că puteți schimba opțiunile transforma în mod individual, de fapt, Orobo.ro calculează și utilizează matrici pentru toate transformă.

####### [![](http://orobo.go.ro:5500/file/teCfvFfWYPYLMojLM/0.04/notemplate)](http://orobo.go.ro:5500/filem/teCfvFfWYPYLMojLM) Scară

* ScaleX = scara pe axa x
* ScaleY = scara pe axa y
* Grup select, apoi modificați / faceți clic pe caseta de intrare + trageți în sus-jos pentru schimbarea valorilor la scară

####### [![](http://orobo.go.ro:5500/file/2JnwWF5LLiRRoYwXg/0.04/notemplate)](http://orobo.go.ro:5500/filem/2JnwWF5LLiRRoYwXg) [![](http://orobo.go.ro:5500/file/eX4Wu2kgHyXoMxRDf/0.04/notemplate)](http://orobo.go.ro:5500/filem/eX4Wu2kgHyXoMxRDf) Oblic

* SkewX = oblic pe axa x
* SkewY = oblic pe axa y
* Grup select, apoi modificați / faceți clic pe caseta de intrare + trageți în sus-jos pentru a schimba valorile oblic

####### [![](http://orobo.go.ro:5500/file/GGtj38efypxcnHxcb/0.04/notemplate)](http://orobo.go.ro:5500/filem/GGtj38efypxcnHxcb) Traduceți

* TranslateX = traduce pe axa x
* TranslateY = traduce pe axa y
* Grup select, apoi modificați / faceți clic pe caseta de intrare + trageți în sus-jos pentru modificarea traduce valorile

####### [![](http://orobo.go.ro:5500/file/KHB5HoSxDkSwJ25kx/0.04/notemplate)](http://orobo.go.ro:5500/filem/KHB5HoSxDkSwJ25kx) Rotire

* Grup select, apoi edit / faceți clic pe caseta de intrare + trageți în sus-jos pentru a schimba valoarea de rotire în grade.

###### [![](http://orobo.go.ro:5500/file/9QBE7E6diHF9ryLQn/0.04/notemplate)](http://orobo.go.ro:5500/filem/9QBE7E6diHF9ryLQn) Degrupeaza

Elementele se degrumează

* Grup select, apoi faceți clic pe `ungroup` (meniu de control)
* Grup select, apoi apăsați pe Alt + U

###### [![](http://orobo.go.ro:5500/file/sqbFjivb2v2N2QSt8/0.04/notemplate)](http://orobo.go.ro:5500/filem/sqbFjivb2v2N2QSt8) [![](http://orobo.go.ro:5500/file/EyEg6X6FAT7sFc45e/0.04/notemplate)](http://orobo.go.ro:5500/filem/EyEg6X6FAT7sFc45e) Toggle Lock

Comutați proprietatea de blocare a unui grup; atunci când este adevărat, puteți selecta direct grupul puteţi efectua acțiuni pe el; atunci când este fals, puteți selecta drect elementele de sub el (a se vedea toGroup pentru cum se ajunge la grupul unui articol).

* Grup select, apoi faceți clic pe `toggLock` (meniu de control)
* Grup select, apoi apăsați pe Alt + L

#### Operațiuni Layer

[![](http://orobo.go.ro:5500/file/mcQgyXHF75RSjEbez/0.1/notemplate)](http://orobo.go.ro:5500/filem/mcQgyXHF75RSjEbez)

Straturile sunt prezentate ca dreptunghiuri colorate pal, în partea dreaptă a ecranului.

* Click strat: arata numai elementele de pe acel strat
* Strat dublu clic: ascunde strat din ecranul principal
* Shift + clic strat: strat și șterge toate elementele / grupurile de sub el
* Dublu clic pe stratul superior din dreapta (alb): a crea un nou layer
* Click strat superior din dreapta (alb): prezinta toate straturile
* Click element + clic strat: mutați elementul pe stratul de făcut clic


#### Operațiuni de fișiere

acţiuni submeniul

* Deschidere sursa: vizualizare și editare sursă SVG
* SaveNew: face o copie a întregului dosar și deschide fișierul nou într-o altă filă
* AddElement: adaugă un element de bază de date publică la dosar

### În Plan

* Versiune de lansare 0.0.5 cu un timp mai rapid de încărcare și interacțiune
* Export fişier / element / grup ca png
* Animație 2D
* Aplicații mobile (tablete, telefoane)
* Descărca toate lucrările personale în toate formatele
* Integrarea fractalilor în editorul vectorial
