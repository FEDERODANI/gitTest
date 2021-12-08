# H1 header
## H2 header
### H3 header
#### H4 header
##### H5 header

## Links
[Proyecto Macarena](https://macaaaguirre.github.io/proyectocoder/index.html)

## Imágenes

![](https://pandao.github.io/editor.md/examples/images/4.jpg)


## Código en línea

`pip installl -r requirements`

## Código Javascript　

```javascript
function test(){
	console.log("Hello world!");
}
 
(function(){
    var box = function(){
        return box.fn.init();
    };

    box.prototype = box.fn = {
        init : function(){
            console.log('box.init()');

			return this;
        },

		add : function(str){
			alert("add", str);

			return this;
		},

		remove : function(str){
			alert("remove", str);

			return this;
		}
    };
    
    box.fn.init.prototype = box.fn;
    
    window.box =box;
})();

var testBox = box();
testBox.add("jQuery").remove("jQuery");
```



## Integrantes
- Federico Aguirre
- Macarena Aguirre
- Adriana Aguirre