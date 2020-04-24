I.	Responde las siguientes preguntas:

A.	¿Cuál es la ventaja de que JavaScript sea un lenguaje interpretado-compilado?
Que es ejecutado leyéndolo directamente del código fuente por una maquina virtual.
B.  ¿Cuál es la diferencia entre null y undefined?
Undefined, es el valor que tiene una variable a la cual no se le ha asignado ningún valor, es la forma en que JS dice que no sabe que es esa variable. 
Null, significa que la variable no tiene ningún valor

C.	Explica el concepto de type coerción
Es la acción de forzar a que un objeto se comporte como si fuera de otro tipo

II.	Calcula el valor booleano de las siguientes expresiones lógicas:
1.	False
2.	Falso.

III.	Implementa una función llamada isFalsy  que dado cualquier valor como parámetro indica si es falso.

Function isFalsy( valor ){

If(valor=== 0 || valor ===  ‘ ‘ ||  valor === null || valor === undefined || valor === false || valor === NaN  ){
Console.log( ‘El valor es Falso’)
}
Else{

Console.log(‘El valor es Verdadero’)
}
}





