[![](http://orobo.go.ro:3500/file/JZXXMo5N38iwgfNAG/0.2/notemplate)](http://orobo.go.ro:3500/browse/file/JZXXMo5N38iwgfNAG/1/3)

# Orobo.ro

## General Considerations

Oroboro is an open platform for collaborative design in SVG (scalable vector graphics).

## How to Use this Manual

* (!) = feature in work

## Known Bugs

![](http://orobo.go.ro:3500/images/tutorial/fileinfo.png)

* when you cannot select an item/group, after an action, please click reload from the file's control menu or refresh the page.
* when you create a parametrized group (with Point Symmetry, Line Symmetry, Item Array) you can select the group only by selecting the original element (path) used for creating it or by using Shift + mouse drag.

## Unique Features

* live collaboration (any change made by a designer is instantly rendered to anyone who has editing or viewing permissions on the document)

[![](http://orobo.go.ro:3500/images/tutorial/filebrowser2.png)](http://orobo.go.ro:3500/browse/file/ZzhbWoiGpMEoA9i3M/1/5)
[![](http://orobo.go.ro:3500/images/tutorial/filebrowser3.png)](http://orobo.go.ro:3500/browse/file/ZzhbWoiGpMEoA9i3M/1/5)

* online database of reusable works (anyone can reuse works or parts from the public database)

* morphing feature for animations (in work)
* 2D animation (in work)
* SVG turtle graphics
* vectorial fractal rendering by mathematical rules
* boolean operations on polygons, with possibility to transform items with curves in multi-line polygons
* presentation mode for created works (can also be used as a Power Point application or as a portfolio gallery)
* protocols of attribution and rights management
* free


## Why SVG

[![](http://orobo.go.ro:3500/file/mQa8FQtSDWpLaYy38/0.2/notemplate)](http://orobo.go.ro:3500/filem/mQa8FQtSDWpLaYy38)

* all issues with creating different types of resolutions (for designing mobile apps, game components etc.) are gone. You can scale infinitely!
* no ugly pixels when zooming in
* [Semantic Web](http://www.w3.org/standards/semanticweb/) friendly
* unlimited possibilities of extension: animation, comic strips, atlases with svg components and layers of connectors and labels.

## Open Design & Open Source

This is an open source project, under GPLv3 license. Oroboro will remain free for anyone who contributes to the community by releasing their work under a comparable license. We may think about hosting a limited number of private works for free.

We are building a design community focused on empowering collaboration and reusability, much like the open source communities for programmers. Share to receive and to be noticed.


## How to Start

* [create an account](http://orobo.go.ro:3500/) and clone a file from the filebrowser with [![](http://orobo.go.ro:3500/file/menuItemClone/0.04)](http://orobo.go.ro:3500/filem/menuItemClone) or go to our [Playground](http://orobo.go.ro:3500/filem/eGfQyh6jCqxeEYmex)

![](http://orobo.go.ro:3500/images/tutorial/addElement.png)

* creating new elements is now made by clicking addElement from the file's control menu and then editing it (appearance, geometry, path points etc.)


[![](http://orobo.go.ro:3500/images/tutorial/filebrowser4.png)](http://orobo.go.ro:3500/browse/file/4wtih642DRCZ5eFxq/1/5)

## Filebrowser

### Filebrowser Menu

#### [![](http://orobo.go.ro:3500/file/menuItemEdit/0.04)](http://orobo.go.ro:3500/filem/menuItemEdit) Edit File
#### [![](http://orobo.go.ro:3500/file/menuItemClone/0.04)](http://orobo.go.ro:3500/filem/menuItemClone) Clone File
#### [![](http://orobo.go.ro:3500/file/menuItemDelete/0.04)](http://orobo.go.ro:3500/filem/menuItemDelete) Delete File
#### [![](http://orobo.go.ro:3500/file/menuItemExport/0.04)](http://orobo.go.ro:3500/filem/menuItemExport) Export File
#### [![](http://orobo.go.ro:3500/file/menuItemSearch/0.04)](http://orobo.go.ro:3500/filem/menuItemSearch) View File

### Filebrowser Icons

#### [![](http://orobo.go.ro:3500/file/menuItemFolder/0.04)](http://orobo.go.ro:3500/filem/menuItemFolder) Folder

This icon shows you that the file has structural children under it.

#### [![](http://orobo.go.ro:3500/file/menuItemDisector/0.04)](http://orobo.go.ro:3500/filem/menuItemDisector) Disector

This icon shows you that the file has groups under it that you can browse, up to the items it contains.

![](http://orobo.go.ro:3500/images/tutorial/breadcrumbs.png)

#### Filebrowser Breadcrumbs

This is the path of the current folder, with the Oroboro root as the first crumb.


## Oroboro Editor

### General Features

* zoom in and out by mouse
* pan by clicking the white background and dragging it
* un/lock pan&zoom by clicking the lock icon - bottom right corner [![](http://orobo.go.ro:3500/file/2j4FekqSWwTfFGSeX/0.02)](http://orobo.go.ro:3500/filem/2j4FekqSWwTfFGSeX)
* minimap of the document(file) and the canvas (white background) in the bottom right corner
* select items by clicking them, multiple select by Shift + clicking them or by using Shift + drag.


### Items
#### Item Types

##### Path

###### [![](http://orobo.go.ro:3500/file/7fFtAL9AgJaWp9G7q/0.04)](http://orobo.go.ro:3500/filem/7fFtAL9AgJaWp9G7q) Simple Path

* only straight lines: 'M870 512L153 925L153 98L870 512Z'
* important for doing [boolean operations](http://en.wikipedia.org/wiki/Boolean_operations_on_polygons) )

###### [![](http://orobo.go.ro:3500/file/eAywEx5e5cNwe6BpC/0.04)](http://orobo.go.ro:3500/filem/eAywEx5e5cNwe6BpC) Complex Path

* with all curves simplified to cubic Bezier curves: 'M112 512C112 291 291 112 512 112C732 112 912 291 912 512C912 733 733 912 512 912C291 912 112 733 112 512Z ')

##### [![](http://orobo.go.ro:3500/file/sh8BiMTztrdGXaPsS/0.04)](http://orobo.go.ro:3500/filem/sh8BiMTztrdGXaPsS) Raster Image
##### [![](http://orobo.go.ro:3500/file/AETqEKboPMEEnPHkj/0.04)](http://orobo.go.ro:3500/filem/AETqEKboPMEEnPHkj) Text
##### [![](http://orobo.go.ro:3500/file/44W6oHqR5woPp474S/0.04)](http://orobo.go.ro:3500/filem/44W6oHqR5woPp474S) Parametrized Path

###### Simple Parametrized Paths
###### Complex Parametrized Paths
###### Functions-based Paths

####### [![](http://orobo.go.ro:3500/file/2oBer6NfjwHpWjYXm/0.04)](http://orobo.go.ro:3500/filem/2oBer6NfjwHpWjYXm) Cartezian Graphs for Functions

For example, `3*Math.sin(3*x)` is the function used for

[![](http://orobo.go.ro:3500/file/2oBer6NfjwHpWjYXm/0.2)](http://orobo.go.ro:3500/filem/2oBer6NfjwHpWjYXm)

####### [![](http://orobo.go.ro:3500/file/srWR38tZRknYDeSbJ/0.04)](http://orobo.go.ro:3500/filem/srWR38tZRknYDeSbJ) Polar Graphs for Functions

For example, `Math.cos(7/4*x)` is the function used for

[![](http://orobo.go.ro:3500/file/i5CppdgDDB5LpKn3S/0.2)](http://orobo.go.ro:3500/filem/i5CppdgDDB5LpKn3S)

More functions for Archimedian spirals and polar roses at [graphs-of-polar-equations](http://www.mathamazement.com/Lessons/Pre-Calculus/06_Additional-Topics-in-Trigonometry/graphs-of-polar-equations.html). Make sure you provide a large enough range for the theta polar angle.


##### [![](http://orobo.go.ro:3500/file/5zk5HoNdJXisEcYMD/0.04)](http://orobo.go.ro:3500/filem/5zk5HoNdJXisEcYMD) Formulae

* latex input

For example, `e=mc^2` is the formula used for

[![](http://orobo.go.ro:3500/file/5zk5HoNdJXisEcYMD/0.2)](http://orobo.go.ro:3500/filem/5zk5HoNdJXisEcYMD)

##### [![](http://orobo.go.ro:3500/file/arHQ6fwEmaZmwQCbu/0.04)](http://orobo.go.ro:3500/filem/arHQ6fwEmaZmwQCbu) QRcode
##### [![](http://orobo.go.ro:3500/file/JrTR22Q3d56xWRkc2/0.04)](http://orobo.go.ro:3500/filem/JrTR22Q3d56xWRkc2) Markdown
##### [![](http://orobo.go.ro:3500/file/TQWiptxM8BDzyR3uv/0.04)](http://orobo.go.ro:3500/filem/TQWiptxM8BDzyR3uv) iFrame
##### [![](http://orobo.go.ro:3500/file/CW976umbSxzA53byY/0.04)](http://orobo.go.ro:3500/filem/CW976umbSxzA53byY) Canvas
##### [![](http://orobo.go.ro:3500/file/Pcp7avZpjfQ3fZXCb/0.04)](http://orobo.go.ro:3500/filem/Pcp7avZpjfQ3fZXCb) Html
##### [![](http://orobo.go.ro:3500/file/d8RDkZdNnHZipaCbK/0.04)](http://orobo.go.ro:3500/filem/d8RDkZdNnHZipaCbK) NestedSvg

#### Special Items

##### [![](http://orobo.go.ro:3500/file/tJGWoeZnxtAsoDuvy/0.04)](http://orobo.go.ro:3500/filem/tJGWoeZnxtAsoDuvy) Connector
##### [![](http://orobo.go.ro:3500/file/arHQ6fwEmaZmwQCbu/0.04)](http://orobo.go.ro:3500/filem/arHQ6fwEmaZmwQCbu) Gradient

#### Editing Items

![](http://orobo.go.ro:3500/images/tutorial/appearance.png)

##### Item Appearance

* fill: color, opacity
* stroke: color, width, dasharray, linecap, linejoin, opacity
* general opacity

##### Item Position

![](http://orobo.go.ro:3500/images/tutorial/geometry.png)

###### Controls Menu

Exact control with pixel numeric values: x,y coordinates, center coordinates, width, height, rotation angle.

###### By Mouse

* drag item
* drag selector circles for changing dimensions
* Shift + drag for maintaining ratio.

##### 3D perspective

After selecting an element, click on the right bottom button [![](http://orobo.go.ro:3500/file/isqRsRCPhGeSPNhoh/0.03)](http://orobo.go.ro:3500/file/isqRsRCPhGeSPNhoh) or press Alt+3. Shift+drag for maintaining ratio.

This can be used for creating shadows. For example: clone shape [![](http://orobo.go.ro:3500/file/gXJDaFEbjPbdNTdfp/0.03)](http://orobo.go.ro:3500/filem/gXJDaFEbjPbdNTdfp), apply a 0.5 opacity / grey color to the future shadow and drag the 3D selector's circles until you get the right shadow: )

[![](http://orobo.go.ro:3500/file/nzumC3jDDPK6jnPTZ/0.3)](http://orobo.go.ro:3500/filem/nzumC3jDDPK6jnPTZ)

[![](http://orobo.go.ro:3500/file/Caj6Gda3CFZGnvn8v/0.2)](http://orobo.go.ro:3500/file/Caj6Gda3CFZGnvn8v)

##### Fine Tuning Paths

Point control by mouse (after selecting an element, click on the left bottom button [![](http://orobo.go.ro:3500/file/MeSC479WX69b9GATS/0.03)](http://orobo.go.ro:3500/file/MeSC479WX69b9GATS) or press Alt+P):

* [![](http://orobo.go.ro:3500/file/P2BZPG7qy42sWFrFA/0.02)](http://orobo.go.ro:3500/filem/P2BZPG7qy42sWFrFA) = path point
* [![](http://orobo.go.ro:3500/file/uzrFnBmQCxoicpGS6/0.02)](http://orobo.go.ro:3500/filem/uzrFnBmQCxoicpGS6) = first subpath point
* [![](http://orobo.go.ro:3500/file/4Wb7jMkaZxEBFwkqD/0.02)](http://orobo.go.ro:3500/filem/4Wb7jMkaZxEBFwkqD) = add new point
* [![](http://orobo.go.ro:3500/file/Qys966QrtRMGcYRDK/0.02)](http://orobo.go.ro:3500/filem/Qys966QrtRMGcYRDK) = curve attractor


* drag path points & curve attractors
* delete path points - double click on [![](http://orobo.go.ro:3500/file/P2BZPG7qy42sWFrFA/0.02)](http://orobo.go.ro:3500/filem/P2BZPG7qy42sWFrFA)
* delete curve - double click on one of the curve's [![](http://orobo.go.ro:3500/file/Qys966QrtRMGcYRDK/0.02)](http://orobo.go.ro:3500/filem/Qys966QrtRMGcYRDK)
* add simple point (straight line) - click on [![](http://orobo.go.ro:3500/file/4Wb7jMkaZxEBFwkqD/0.02)](http://orobo.go.ro:3500/filem/4Wb7jMkaZxEBFwkqD)
* add curve point (2 curves) - Shift + click on [![](http://orobo.go.ro:3500/file/4Wb7jMkaZxEBFwkqD/0.02)](http://orobo.go.ro:3500/filem/4Wb7jMkaZxEBFwkqD)


Point control from controls menu (Points submenu) (!) - each point can be moved at the provided coordinates.


### Groups
#### Group Types

##### Layer

Every file has at least one layer under which the elements are grouped.

##### [![](http://orobo.go.ro:3500/file/cRiQceYEsBNr2MuAx/0.04/notemplate)](http://orobo.go.ro:3500/filem/cRiQceYEsBNr2MuAx) Simple Group

Any classic svg group which contains elements: `<g></g>`

##### Parametrized Group

Special groups which have callback functions for dictating the behaviour/patterns of the contained elements

#### Editing Groups
##### Group Transform

Neutral matrix values: 1,0,0,1,0,0. Value meaning:
1. scale on x axis
2. skew on x axis
3. skew on y axis
4. scale on y axis
5. translate on x axis
6. translate on y axis

### Files
#### File Types

##### [![](http://orobo.go.ro:3500/file/9tQyfodBmtdRpcEML/0.04/notemplate)](http://orobo.go.ro:3500/filem/9tQyfodBmtdRpcEML) SVG
##### [![](http://orobo.go.ro:3500/file/QLjb9RprCCEPo5LFk/0.04/notemplate)](http://orobo.go.ro:3500/filem/QLjb9RprCCEPo5LFk) PNG
##### [![](http://orobo.go.ro:3500/file/k6oThcBq7HrPE2hEN/0.04/notemplate)](http://orobo.go.ro:3500/filem/k6oThcBq7HrPE2hEN) JPEG
##### [![](http://orobo.go.ro:3500/file/E2fB5224ac5mkDcro/0.04/notemplate)](http://orobo.go.ro:3500/filem/E2fB5224ac5mkDcro) JavaScript
##### [![](http://orobo.go.ro:3500/file/xNdm3hx4M3WLhGd7x/0.04/notemplate)](http://orobo.go.ro:3500/filem/xNdm3hx4M3WLhGd7x) CSS
##### [![](http://orobo.go.ro:3500/file/fhTRHbcDGmHxFEdM4/0.04/notemplate)](http://orobo.go.ro:3500/filem/fhTRHbcDGmHxFEdM4) Text

#### Special File Types

##### [![](http://orobo.go.ro:3500/file/9soqDH7MhEw8rcXBx/0.04/notemplate)](http://orobo.go.ro:3500/filem/9soqDH7MhEw8rcXBx) Template


#### Editing Files

[![](http://orobo.go.ro:3500/images/tutorial/fileinfo.png)]

##### File Info

Info submenu: creator, resolution, hierarchical path, file title, edit permissions, browse file in File Browser, reload file, reset view (reset zoom to neutral level).

###### File Permissions

Info submenu. Add email addresses separated by a comma: ,
The email addresses must have an oroboro account.

[![](http://orobo.go.ro:3500/images/tutorial/fileactions.png)]



### General Operations

[![](http://orobo.go.ro:3500/images/tutorial/actions.png)](http://orobo.go.ro:3500/filem/2ME5he36GPCNCaFhY)

**in the controls menu, the operations are under the Actions submenu; some of them have keyboard shortcuts

##### [![](http://orobo.go.ro:3500/file/bvDoMyozQm4cBLrFK/0.04/notemplate)](http://orobo.go.ro:3500/filem/bvDoMyozQm4cBLrFK) Source Code

* view and edit the file's svg source code: click `source` (file's controls menu)
* view and edit the source code of 1/> items and groups: select items/groups, then click `source` (controls menu)

##### [![](http://orobo.go.ro:3500/file/EqPANkXeM2cFSKfTC/0.04/notemplate)](http://orobo.go.ro:3500/filem/EqPANkXeM2cFSKfTC) Clone

Clone items/groups inside the file, under the original item's parent.

* select items/groups, then click `clone` (controls menu)
* select items/groups, then press Alt+C

##### [![](http://orobo.go.ro:3500/file/ggFTeKHeA8vGFn9Z5/0.04/notemplate)](http://orobo.go.ro:3500/filem/ggFTeKHeA8vGFn9Z5) Delete

Delete items/groups from the file.

* select items/groups, then click `delete` (controls menu)
* select items/groups, then press Alt+D

##### [![](http://orobo.go.ro:3500/file/Bg5p7KxDexx7wp2vr/0.04/notemplate)](http://orobo.go.ro:3500/filem/Bg5p7KxDexx7wp2vr) Bring to Front

Bring item/group to front, overlapping the other items (!)

* select item/group, then click `toFront` (controls menu)
* select item/group, then press Alt+F

##### [![](http://orobo.go.ro:3500/file/STsJzqTqRyi6JX8rN/0.04/notemplate)](http://orobo.go.ro:3500/filem/STsJzqTqRyi6JX8rN) Send to Back

Send item/group to back, being overlapped by all other items (!)

* select item/group, then click `toBack` (controls menu)
* select item/group, then press Alt+B

##### [![](http://orobo.go.ro:3500/file/QWz5HkQwwqgqNpNZJ/0.04/notemplate)](http://orobo.go.ro:3500/filem/QWz5HkQwwqgqNpNZJ) Select parent Group

Select group containing the item/group (if not a layer).

* select item/group, then click `toGroup` (controls menu)
* select item/group, then press Alt+Up Arrow

##### [![](http://orobo.go.ro:3500/file/cRiQceYEsBNr2MuAx/0.04/notemplate)](http://orobo.go.ro:3500/filem/cRiQceYEsBNr2MuAx) Create parent Group

Create a group containing the selected items/groups

* select items/groups, then click `group` (controls menu)
* select items/groups, then press Alt+G

##### [![](http://orobo.go.ro:3500/file/cRiQceYEsBNr2MuAx/0.04/notemplate)](http://orobo.go.ro:3500/filem/cRiQceYEsBNr2MuAx) Import Selector

Create a group containing the original item and the selector present at that moment (draggable selector, points selector, 3D selector).

* select item, then click `importSelector` (controls menu)
* select item, then press Alt+I

#### Item Operations

##### Path Operations

###### [![](http://orobo.go.ro:3500/file/4YptMH9My37sYj5mm/0.04/notemplate)](http://orobo.go.ro:3500/filem/4YptMH9My37sYj5mm) Close/Open Path

Close / open path.

* select path, then click `closeOpen` (controls menu) for toggling option

###### [![](http://orobo.go.ro:3500/file/fEv7RE3LdYpQ4Q8TW/0.04/notemplate)](http://orobo.go.ro:3500/filem/fEv7RE3LdYpQ4Q8TW) Horizontal Mirror

Flip item horizontally.

* select path, then click `mirrorH` (controls menu)

###### [![](http://orobo.go.ro:3500/file/n6yMHex8KcBPBC9Ts/0.04/notemplate)](http://orobo.go.ro:3500/filem/n6yMHex8KcBPBC9Ts) Vertical Mirror

Flip item vertically.

* select path, then click `mirrorV` (controls menu)

###### [![](http://orobo.go.ro:3500/file/8JyQRohBkBZvzRwEp/0.04/notemplate)](http://orobo.go.ro:3500/filem/8JyQRohBkBZvzRwEp) Reverse Path Points Order

Reverse order of path points.

* select path, then click `reverse` (controls menu)

###### [![](http://orobo.go.ro:3500/file/ngiimZYX6f5FtJdY2/0.04/notemplate)](http://orobo.go.ro:3500/filem/ngiimZYX6f5FtJdY2) Join Paths

Join 1/> paths into one shape with subpaths.

* Shift select paths, then click `joinPaths` (controls menu)

###### [![](http://orobo.go.ro:3500/file/7jLp2apKztDxd6Siv/0.04/notemplate)](http://orobo.go.ro:3500/filem/7jLp2apKztDxd6Siv) Split Subpaths from Path

Separate subpaths to form separate items.

* select path, then click `splitPaths` (controls menu)

###### [![](http://orobo.go.ro:3500/file/CBH7KZbutnGPknCNf/0.04/notemplate)](http://orobo.go.ro:3500/filem/CBH7KZbutnGPknCNf) Point Symmetry Group

Create a __Parametrized Group__ using the selected path and a point with x and y coordinate for building simetric clones of the path, relative to the given point .

[![](http://orobo.go.ro:3500/file/AZrdxkdEjk3yCgLpJ/0.2/notemplate)](http://orobo.go.ro:3500/filem/AZrdxkdEjk3yCgLpJ) [![](http://orobo.go.ro:3500/file/A5TCgpQdRXeQus9iu/0.2/notemplate)](http://orobo.go.ro:3500/filem/A5TCgpQdRXeQus9iu) [![](http://orobo.go.ro:3500/file/nPW3sGvBa57m87d7d/0.2/notemplate)](http://orobo.go.ro:3500/filem/nPW3sGvBa57m87d7d) [![](http://orobo.go.ro:3500/file/SzvW7PjwnchXPFwnj/0.2/notemplate)](http://orobo.go.ro:3500/filem/SzvW7PjwnchXPFwnj)

* select path, then click `pointSymmetry` (controls menu)
* the parametrized group will have all the features presented in the Parametrized Group subchapter.

With this powerfull feature we can even make spirals.

###### [![](http://orobo.go.ro:3500/file/AnNnDaf2HrmyHBTYE/0.04/notemplate)](http://orobo.go.ro:3500/filem/AnNnDaf2HrmyHBTYE) Line Symmetry Group

[![](http://orobo.go.ro:3500/file/h2bNyDpySrwrsG5N2/0.2)](http://orobo.go.ro:3500/filem/h2bNyDpySrwrsG5N2) [![](http://orobo.go.ro:3500/file/KBtAqH623Src52i96/0.2)](http://orobo.go.ro:3500/filem/KBtAqH623Src52i96) [![](http://orobo.go.ro:3500/file/zrsJTCFpCXKYh8dxE/0.2)](http://orobo.go.ro:3500/filem/zrsJTCFpCXKYh8dxE)

Create a __Parametrized Group__ using the selected path and a given line for building simetric clones of the path, relative to the line.

* select path, then click `lineSymmetry` (controls menu)
* the parametrized group will have all the features presented in the Parametrized Group subchapter.

###### [![](http://orobo.go.ro:3500/file/jLXYjXxyTTecoYv9C/0.04/notemplate)](http://orobo.go.ro:3500/filem/jLXYjXxyTTecoYv9C) Item Array Group

[![](http://orobo.go.ro:3500/file/2CC2YmbKH9pzL4rb8/0.2)](http://orobo.go.ro:3500/filem/2CC2YmbKH9pzL4rb8) [![](http://orobo.go.ro:3500/file/xkYrgQSscp4yoKM9v/0.2)](http://orobo.go.ro:3500/filem/xkYrgQSscp4yoKM9v) [![](http://orobo.go.ro:3500/file/iQdYEY4DHG5EJkTLd/0.2)](http://orobo.go.ro:3500/filem/iQdYEY4DHG5EJkTLd)

Create a __Parametrized Group__ using the selected path for building clones of the path arranged in a matrix/array format.

* select path, then click `itemArray` (controls menu)
* the parametrized group will have all the features presented in the Parametrized Group subchapter.

You can now easily make patterns and tiles and even tessellations.

#### Combined Path Operations

We can combine the above operations for creating complex objects and patterns.

[![](http://orobo.go.ro:3500/file/JoXEZALTNoz9JgHLg/0.2/notemplate)](http://orobo.go.ro:3500/filem/JoXEZALTNoz9JgHLg)

This honeycomb pattern was created by using Item Array with [![](http://orobo.go.ro:3500/file/zS26Fh445Wqdu4ND3/0.1)](http://orobo.go.ro:3500/filem/zS26Fh445Wqdu4ND3) - obtained by using Point Symmetry with [![](http://orobo.go.ro:3500/file/2DzGLexiPZYpzSt69/0.1)](http://orobo.go.ro:3500/filem/2DzGLexiPZYpzSt69)

[![](http://orobo.go.ro:3500/file/tSwejJnAEKPBSazp6/0.2/notemplate)](http://orobo.go.ro:3500/filem/tSwejJnAEKPBSazp6)

This jigsaw puzzle was created by using Item Array with [![](http://orobo.go.ro:3500/file/zS26Fh445Wqdu4ND3/0.1)](http://orobo.go.ro:3500/filem/zS26Fh445Wqdu4ND3) - obtained by using Point Symmetry with [![](http://orobo.go.ro:3500/file/zS26Fh445Wqdu4ND3/0.1)](http://orobo.go.ro:3500/filem/zS26Fh445Wqdu4ND3)

[![](http://orobo.go.ro:3500/file/z5CTy2uBPegog5Bnv/0.2)](http://orobo.go.ro:3500/filem/z5CTy2uBPegog5Bnv)

This spiral was created by using Point Symmetry and Polar Functions. [![](http://orobo.go.ro:3500/file/i5CppdgDDB5LpKn3S/0.1)](http://orobo.go.ro:3500/filem/i5CppdgDDB5LpKn3S) is generated by `Math.cos(7/4*x)` (take a look at the polar angle range). If we select this path and click `genPath` from the menu, we get a classic path object, which can be used however we want: [![](http://orobo.go.ro:3500/file/ssMswfKiZfWLseY3b/0.1)](http://orobo.go.ro:3500/filem/ssMswfKiZfWLseY3b). In this case, by selecting it and clicking `pointSymmetry` from the menu.

##### Simple Path Operations

###### Boolean Operations

####### [![](http://orobo.go.ro:3500/file/ACKSA92hnv8Xm7TdQ/0.04/notemplate)](http://orobo.go.ro:3500/filem/qDRbePmMAJgGhgzcg) Union

Creates another path from the union of the selected paths.

* select paths, then click `union` (controls menu)

####### [![](http://orobo.go.ro:3500/file/5j8hem49B5c8Wmf8w/0.04/notemplate)](http://orobo.go.ro:3500/filem/qDRbePmMAJgGhgzcg) Difference

Creates another item from the difference of the paths.

* select paths, then click `difference` (controls menu)


####### [![](http://orobo.go.ro:3500/file/Li8SBbTjjfmwdhAg8/0.04/notemplate)](http://orobo.go.ro:3500/filem/qDRbePmMAJgGhgzcg) Xor

Creates another item from the xor of the paths.

* select paths, then click `xor` (controls menu)


####### [![](http://orobo.go.ro:3500/file/MTeMg4fEryLvaSoBX/0.04/notemplate)](http://orobo.go.ro:3500/filem/MTeMg4fEryLvaSoBX) Intersection

Creates another item from the intersection of the paths.

* select paths, then click `intersection` (controls menu)


##### Complex Path Operations

###### [![](http://orobo.go.ro:3500/file/cSYwm8DpLd5iLhL7v/0.04/notemplate)](http://orobo.go.ro:3500/filem/cSYwm8DpLd5iLhL7v) Simplify

* transform curves into multiple straight lines
* number of points shown in the upper left corner of the screen
* this is very important for mimicking boolean operations with complex paths: you first simplify the complex path and transform it into a simple path and then use it for union, xor etc.

* select path, then click `simplify` (controls menu)

[![](http://orobo.go.ro:3500/file/mk49q5vXnGB6qNoNH/0.2/notemplate)](http://orobo.go.ro:3500/filem/mk49q5vXnGB6qNoNH)

This is a simple path - a circle made from straight lines, with 104 points.


#### Morphing 2 Paths

* morph frames: Shift+ click items + select morph type (morphopt) + mouse drag morph position (morphpos) -> first clicked item = source, second clicked item = destination;

#### Animation

(!) Multiple types of animation between simple paths, based on the morph feature


#### Group Operations

Click group / click item from group + Alt+Up Arrow for selecting a group.

##### Transform

Transform submenu from controls menu controlls the transform options for the group. Transforms are always applied in underground as matrices.

###### Reset Matrix

Reset matrix to neutral values.

* select group, then click `reset` (controls menu)

###### Modify Matrix

* select group, then edit matrix string and then press Enter

###### Transform Options

Even though it seems that you can change transform options individually, Orobo.ro actually computes and uses matrices for all transforms.

####### [![](http://orobo.go.ro:3500/file/teCfvFfWYPYLMojLM/0.04/notemplate)](http://orobo.go.ro:3500/filem/teCfvFfWYPYLMojLM) Scale

* scaleX = scale on the x axis
* scaleY = scale on the y axis
* select group, then edit / click input box + drag up-down for changing the scale values

####### [![](http://orobo.go.ro:3500/file/2JnwWF5LLiRRoYwXg/0.04/notemplate)](http://orobo.go.ro:3500/filem/2JnwWF5LLiRRoYwXg) [![](http://orobo.go.ro:3500/file/eX4Wu2kgHyXoMxRDf/0.04/notemplate)](http://orobo.go.ro:3500/filem/eX4Wu2kgHyXoMxRDf) Skew

* skewX = skew on the x axis
* skewY = skew on the y axis
* select group, then edit / click input box + drag up-down for changing the skew values

####### [![](http://orobo.go.ro:3500/file/GGtj38efypxcnHxcb/0.04/notemplate)](http://orobo.go.ro:3500/filem/GGtj38efypxcnHxcb) Translate

* translateX = translate on the x axis
* translateY = translate on the y axis
* select group, then edit / click input box + drag up-down for changing the translate values

####### [![](http://orobo.go.ro:3500/file/KHB5HoSxDkSwJ25kx/0.04/notemplate)](http://orobo.go.ro:3500/filem/KHB5HoSxDkSwJ25kx) Rotate

* select group, then edit / click input box + drag up-down for changing the rotate value in degrees.

###### [![](http://orobo.go.ro:3500/file/9QBE7E6diHF9ryLQn/0.04/notemplate)](http://orobo.go.ro:3500/filem/9QBE7E6diHF9ryLQn) Ungroup

Deletes group and moves elements under the deleted group's parent.

* select group, then click `ungroup` (controls menu)
* select group, then press Alt+U

###### [![](http://orobo.go.ro:3500/file/sqbFjivb2v2N2QSt8/0.04/notemplate)](http://orobo.go.ro:3500/filem/sqbFjivb2v2N2QSt8) [![](http://orobo.go.ro:3500/file/EyEg6X6FAT7sFc45e/0.04/notemplate)](http://orobo.go.ro:3500/filem/EyEg6X6FAT7sFc45e) Toggle Lock

Toggle the lock property of a group; when true, you can directly select the group and perform actions on it; when false, you can drectly select the items under it (see toGroup for how to get to an item's group).

* select group, then click `toggLock` (controls menu)
* select group, then press Alt+L

#### Layer Operations

[![](http://orobo.go.ro:3500/file/mcQgyXHF75RSjEbez/0.1/notemplate)](http://orobo.go.ro:3500/filem/mcQgyXHF75RSjEbez)

Layers are shown as pale colored rectangles, on the right of the screen.

* click layer: show only items on that layer
* double click layer: hide layer from main view
* Shift+click layer: delete layer and all items/groups under it
* double click right upper layer (white): create new layer
* click right upper layer (white): shows all layers
* click item + click layer: move item on clicked layer


#### File Operations

Actions submenu

* press source: view and edit svg source
* saveNew: makes a copy of the entire file and opens the new file in another tab
* addElement: adds a public database element to the file

### In Plan

* release version 0.0.5 with faster loading and interaction time
* export file / item / group as png
* 2D animation
* mobile app (tablets, phones)
* download all personal works in all formats
* integration with the vectorial fractals creator
