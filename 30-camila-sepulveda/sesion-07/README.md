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
lo que queremos que pase cuando la condición sea verdadera
}

for( let x=0 ; x<=width; x=x+1){
ellipse(x,200,random(300))
}

## nested loop:  es un for dentro de otro for. 

Ejemplos:

for(iniciación variable; condición booleana; actualización){
lo que queremos que pase cuando la condición sea verdadera
for(iniciación variable; condición booleana; actualización){

for( let x=0 ; x <= width; x=x+25){
for( let y=0 ; y <= height; y=y+25){

fill(0,0,255);
ellipse(x,y,15);
}
}
