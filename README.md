
# Xml-Http-Request

Bir XMLHttpRequest nesnesi oluşturur:
```
var xhttp = new XMLHttpRequest();
```

onreadystatechange özelliği, XMLHttpRequest nesnesinin durumu her değiştiğinde yürütülecek bir işlevi belirtir:

```
var xhttp = new XMLHttpRequest();
```

İşlem başarılı ise ReadyState==4  ve HttpStatus==200 eşit olur
```
  if (this.readyState == 4 && this.status == 200) {
       // Typical action to be performed when the document is ready:
      console.log(xhttp.responseText);
    }
```
