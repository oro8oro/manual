# L-System
The lsys function for setup, iter for l-sys commands, render for results.

```
var tg =svg.lsys(1024,1024).attr({stroke:"#000","stroke-width":.5,fill:"#fff"});
tg.iter("F", {F: "F<G<<G>F>>FF>G<", G: ">F<GG<<G<F>>F>G"},4,4,1/6);
//console.log(tg);
tg.render(1);

```

svg.lsys( __width__, __height__ )

.iter( __start__, __L-System rules__, __no. of iterations__, __length of forward__, __angle in radians__)

.render( __force__ )

## Example 1


```
var tg =svg.lsys(1024,1024).attr({stroke:"#000","stroke-width":.5,fill:"#fff"});
tg.iter("F<G<G", {F: "F<G>F>G<F", G: "GG"},6,4,1/3);
//console.log(tg);
tg.render(1);
```

## Example 2


```
var tg =svg.lsys(1024,1024).attr({stroke:"#000","stroke-width":.5,fill:"#fff"});
tg.iter("XYXYXYX>XYXYXYX>XYXYXYX>XYXYXYX", {F: "", X: "FX>FX>FXFY<FY<",Y: ">FX>FXFY<FY<FY"},3,4,1/4);
//console.log(tg);
tg.render(1);
```


## Example 3

```
var tg =svg.lsys(1024,1024).attr({stroke:"#000","stroke-width":.5,fill:"#fff"});
tg.iter("FX", {F: "", X: "X<YF<",Y: ">FX>Y"},14,4,1/4);
//console.log(tg);
tg.render(1);
```

## Example 5

```
var tg =svg.lsys(1024,1024).attr({stroke:"#000","stroke-width":.5,fill:"#fff"});
tg.iter("F>>F>>F", {F: "F<F>>F<F", X: "FF"},5,4,1/6);
//console.log(tg);
tg.render(1);
```

## Example 6

```
var tg =svg.lsys(1024,1024).attr({stroke:"#000","stroke-width":.5,fill:"#fff"});
tg.iter("X", {Y: ">XF<YFY<FX>", X: "<YF>XFX>FY<"},6,4,1/4);
//console.log(tg);
tg.render(1);
```
