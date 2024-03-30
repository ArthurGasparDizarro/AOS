Exercicioa de PHP -atitudinal-

1) $numero=2;     
  function sinal($variavel){  
     if($variavel < 0){  
    echo " \n O numero " .$variavel." é Negativo";    
     }else{
     echo " \n O numero " .$variavel." é positivo";
     }
   }
  echo sinal($numero);

2)$numeros=[1,2,3,4,5,6,7,8,9,10];

for($i=0;$i<10;$i++){
    echo "$numeros[$i] é o numero $i \n";
    
}
