# Turtle Graphics
The tgraph function for setup, t for turtle commands, render for result show.

```
var tg =svg.tgraph(1024,1024).attr({stroke:"#000"});
tg.t("M0,0<90F50<90F1024<190F50<90F1024Z");
//console.log(tg);
tg.render(1);

```

svg.tgraph( __width__, __height__)

.t(__turtle commands string__)

.render(__force__)

## Turtle commands

### M x, y

Moves the turtle at x, y. Usually begins the path.

### F pixels

Moves turtle forward with pen down.

### < deg

Turn turtle by deg degrees right.

### > deg

Turn turtle by deg degrees left.

### [

Pushes the turtle position into the stack.

### ]

Pops the turtle position out of the stack.

### Z

Closes the path.


## Example 1

```
var tg =svg.tgraph(1024,1024).attr({stroke:"#000","fill-opacity":0, "stroke-width":4});
var j=0
for (var i=0;i<120; i++) {
    j=i*5
    tg.t("M0,0<90F"+j+"<90F"+j+"<90F"+j+"<90F"+j+"<20");
}


//console.log(tg);
tg.render(1);

```

## Example 2

```
var tg =svg.tgraph(1024,1024).attr({stroke:"#000","fill-opacity":0, "stroke-width":.4});
var sides = 7,j=0, string="M0,0"
for (var i=0;i<180; i++) {
    j=i*1
    string="M0,0"
    for (var k=0;k<sides;k++){
        string=string+"<"+360/sides+"F"+j
    }
    string = string+"<20"
    tg.t(string);
}


//console.log(tg);
tg.render(1);
```

## Example 3

```

var tg =svg.tgraph(1024,1024).attr({stroke:"#000","fill-opacity":0, "stroke-width":1});
var sides = 5,j=0, string="M0,0"
for (var i=0;i<16; i++) {
    j=i*7
    //string="M0,0"
    for (var k=0;k<sides;k++){
        string=string+"<"+360/(sides)+"F"+j
    }

    string = string+"F60<10"
    tg.t(string);
}  

//console.log(tg);
tg.render(1);

```
