# sesión 07 - 15/05


# Loops, while & for. 

## que es un loop (bucle): es una repetición o proceso infinito. Estructura de control que permite ejecutar un bloque de instrucciones de maneraa repetida mientras se cumpla una condición específica.
def. rae: informatica. serie de instrucciones que se repiten indefinidamente mientras no se cumpla una condición previamente establecida. 

## while: utililes para repetir condiciones instrucciuones mientras una condición sea verdadera. 
while(condición booleana) {
}

Ejemplos: 

mientras (x sea menor o igual que el alto de mi lienzo){  x incrementara a 1 cada vez } 
while(x<= heigth){
x = x+1} 

## for: forma de repetir un bloque de código cuando se conoce el número deinteracciones. Utiles para repetir instrucciones un numero determinado de cosas. 

Ejemplos: 

for( inicialización variable; condición booleana; actualización){ 
lo quenquremos que pase cuabdo la condición sea verdadera
}

for( let x=0 ; x<=width; x=x+1){
ellipse(x,200,random(300))
}

