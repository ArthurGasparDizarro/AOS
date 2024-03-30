Exercicioa de PHP -atitudinal-

1)                                                 |                                            
 $numero=2;                                         |                     OUTPUT:
                                                    |                     O numero 2 é positivo
 function sinal($variavel){                         |
    if($variavel < 0){                              |
   echo " \n O numero " .$variavel." é Negativo";    |
   ;
    }else{
    echo " \n O numero " .$variavel." é positivo";
    ;
    }
}
     echo sinal($numero);
