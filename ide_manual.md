# Orobo.ro IDE

## How to Start

* Go to  [Oro IDE](http://orobo.go.ro:3500/file/8tKjNXB6TuxBSsf5c)
* Make sure you have some code to try in the lefthand side
* Modify the code by uncommenting/commenting code lines
* Learn by trial

## Try this code

```
var tg =svg.lsys(1024,1024).attr({stroke:"#000","stroke-width":.5,fill:"#fff"});

tg.iter("F", {F: "F<G<<G>F>>FF>G<", G: ">F<GG<<G<F>>F>G"},4,4,1/6);

//var tg =svg.tgraph(1024,1024).attr({stroke:"#000"});
//tg.t("M0,0<90F50<90F1024<190F50<90F1024Z");

//var tg =svg.puppet(424,424, "show","/file/2bQfWx8fDbWMgddmj").mirror().attr({stroke:"#000"}).say("Habem!");

//console.log(tg);
tg.render(1);

```


## API
### Turtle Graphics
The tgraph function for setup, t for turtle commands, render for result show.

### L-System
The lsys function for setup, iter for l-sys commands, render for results.

### Puppet
The puppet function for construction.
