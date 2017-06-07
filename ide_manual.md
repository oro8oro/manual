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

## Loading and Saving to Oroboro Editor

```
var Oro = "orobo.go.ro:3500" // change it to your own install of Oroboro server

var toOro = function(path1,path2id){
$.ajax({
  url: "http://"+Oro+"/api/item/"+path2id,
  "async": true,
 "crossDomain": true,
  "headers": {
   "content-type": "application/json",
   "cache-control": "no-cache"
 },
  method:"POST",
  //processData: false,
data: '{"d":"'+path1.attr("d")+'"}',
//dataType: "json"
//dataType: "json",
contentType: "application/json"
}).done(function() {
  console.log("ok")
});

}

var fromOro= function(id){
    $.getJSON(
  "http://"+Oro+"/api/item/"+id,
  function(data){
      var path =svg.path(data.pointList)
      path.attr(data.palette)
      path.attr({id: data._id})
  });

}

// examples of use
toOro(tg,"PDuXckg3Qtk7pFXtk")
fromOro("PDuXckg3Qtk7pFXtk")


```

## API
### Turtle Graphics
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

### L-System
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

### Puppet
The puppet function for construction.

```
var tg =svg.puppet(424,424, "show","/file/2bQfWx8fDbWMgddmj").mirror().attr({stroke:"#000"}).say("Habem!");
//console.log(tg);
```

svg.puppet( __x__, __y__, __stance__, __url for head image__)

.say(__string for talk balloon__)

The puppet is the basis for the future comic strips and animations plugins.
