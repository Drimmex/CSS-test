# CSS-test
## Selectores
* Selector universal
Se utiliza para dar estilos a todo, y es representado con un asterisco.
Selectores de tipo
Se utilizan cuando deseas aplicar estilos sobre un elemento en concreto, como por ejemplo un div, p, o img.
* Clases e ID
Se utilizan cuando se desea aplicar estilos sobre un elemento que contenga uno de los dos atributos, al aplicarlos, se representan en CSS como un punto seguido del nombre de la clase y un numeral seguido del nombre del ID respectivamente.
* Elementos con atributos similares
Podemos dar estilo a elementos con atributos similares colocándolo separados por comas, esto aplica para selectores de tipo, de clase y de ID.
* selectores de encadenamiento
Se utilizan cuando deseamos dar estilos a un elemento en concreto que cuenta con dos clases, sin embargo existe otro elemento con una de las dos clases repetidas podemos solo darle estilo a uno de los dos elementos sin que esto afecte a los dos elementos en cuestión, para ello se escriben las dos clases sin separación, esto también aplica para un ID y una clase, no para los selectores de tipo.

## Reglas
* combinador descendiente
Se utiliza cuando existe un elemento hijo o nieto al que se le quiere dar un estilo, a diferencia de los selectos de encadenamiento para aplicarlo debemos dejar un espacio en lugar de escribir todo junto, por ejemplo tenemos la clase fruta y dentro de la misma tenemos un elemento que recibe el nombre de frutos-rojos, y dentro del mismo hay un objeto fresa y a ese es el que queremos darle estilo, solo demos utilizar este tipo de combinador.
* Especificidad
Los cambios siempre afectarán según el grado de especificidad de selectores y combinaciones, siendo el orden ID, clase, selector de tipo, cuando se cuente con el mismo nivel de especificidad en dos declaraciones las dos serán tomadas como válidas y los estilos que no se declaren en uno pero en otro si, serán tomados.
* Herencia
Los elementos de una misma línea hereditaria serán afectados por esta regla, a menos que un elemento en dicha línea hereditaria sea llamado directamente.
* Orden de reglas
La última en ser aplicada será la ganadora.

