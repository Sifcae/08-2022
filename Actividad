# 08-2022
// Los Codigos se ejecutan bajo consola Visual Studio Code //.

//////////////////////////////////////////////////////////////////////////////
// Elaboro Wilmer Stiven Rueda //

// Area y Perimetro del triangulo//
const ladoa = 8
let ladob = 6
let ladoc = 5
let altura = 2

var per_trian = ladoa + ladob + ladoc;
var are_trian = ladob*altura/2;

console.log("El perimetro del triangulo es: " + per_trian);
console.log("El area del triangulo es: " + are_trian);

// Area y Perimetro del Rectangulo//

let base1 = 5
let altura1 = 6

var per_rectan = (base1+altura1)*2;
var are_rectan = base1*altura1;

console.log("El perimetro del Rectangulo es: " + per_rectan );
console.log("El area del Rectangulo es: " + are_rectan);

// Area y perimetro del Cuadrado //

let lado = 5

var per_cuadr = lado*4;
var are_cuadr = (Math.pow(lado, 2));

console.log("El perimetro del Cuadrado es: " + per_cuadr);
console.log("El area del cuadrado es: " + are_cuadr);

// Area y Perimetro del Circulo //

let r = 8;

var per_circ = Math.PI*2*r;
var are_circ = Math.PI*Math.pow(r, 2);

console.log("El Perimetro del Circulo es: " + per_circ);
console.log("El area del Circulo es: " + are_circ);

//////////////////////////////////////////////////////////////////////////////

//////////////////////////////////////////////////////////////////////////////


// Elaboro Wilmer Stiven Rueda//

var edades = [58,7,20,21,43,9,62,78,90,5]; //Vector//

 console.log ("las edades ingresadas son: " + edades);

 let i;
 let men = 0;
 let may = 0;
 let adul = 0;

edades.sort(function(a,b){
return a-b;
})
for(i=0;i<9;i++){
   if(edades[i]<18) 
    men=men+1
 else
      if(edades[i]>=18 && edades[i]<60) 
       may=may+1
  else
if(edades[i]>=60 && edades[i]<120)
   adul=adul+1

}
 let baj = 0;
 let alt = 0;

 for(i=0;i<=9;i++)
     if(i==0){
        baj= edades[i]
        alt = edades[i]
      }else{
        if (edades[i]>alt){
        alt=edades[i]
     }  else
            if(edades[i]<baj){
            baj=edades[i]
            }
}
      console.log ("La cantidad de menores de edad son: " + men);
      console.log ("La cantidad de mayores de edad son: " + may);
      console.log ("La cantidad de adultos mayores son: " + adul);
      console.log ("La edad mas alta es: " + alt);
      console.log ("La edad mas baja es: " + baj);

//////////////////////////////////////////////////////////////////////////////

//////////////////////////////////////////////////////////////////////////////

// Elaboro Wilmer Stiven Rueda //

let array1 = [1,3,6,9,17];
let array2 = [2,4,10,17];
let array3 = array1.concat(array2);

array3.sort( function(a,b){
     return a-b;

});
console.log (array3.join(", "));

//////////////////////////////////////////////////////////////////////////////

//////////////////////////////////////////////////////////////////////////////

// Elaboro Wilmer Stiven Rueda //
let encuesta = 
[
  ["Juan",1127076043,"3/8/1994","juan@gmail.com","Bogota","Medellin","Artista: Juanes","A Dios le pido","Juntos","La Plata"],
  ["Maria",1127076054,"6/11/2001","maria@gmail.com","Cartagena","Cali","Artista: Joe Arroyo","El Preso","Rebelion","Los Charcos"],
  ["Pedro",1127076089,"5/9/2000","pedro@gmail.com","Ibague","Barranquilla","Artista: Joe Arroyo","Rebelion","El Preso",""],
  ["Carlos",1127076041,"1/1/1996","carlos@gmail.com","Mocoa","Pitalito","Artista: Juanes","A Dios le pido","La Plata",""],
  ["Juana",1127076070,"2/11/1998","juana@gmail.com","Pasto","Tumaco","Artista: Vicente Fernandez","Aca Entre Nos","Mujeres Divinas","Volver, volver"],
  ["Adriana",1127076090,"8/8/1990","adriana@gmail.com","Cali","Buga","Artista: Vicente Fernandez","Vover, volver","Aca Entre Nos",""]
];
var total = 0;

for(let i=0; i< encuesta.length; i++){
    var total = total+1;
    console.log("Registro # " + (i+1) );
    for(let j=0; j< encuesta[i].length; j++){
        console.log( "    " + encuesta[i][j] );

    }
}


