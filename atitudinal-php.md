## Exercicioa de PHP -atitudinal-

## <?php
    1) $numero=2;     
        function sinal($variavel){  
     if($variavel < 0){  
    echo " \n O numero " .$variavel." é Negativo";    
     }else{
     echo " \n O numero " .$variavel." é positivo";
     }
   }
      echo sinal($numero);
      
      ?>
      
      ```



## 2)<?php
 $numeros=[1,2,3,4,5,6,7,8,9,10];                                                                                                                                                                                                                       

  for($i=0;$i<10;$i++)  {
      echo "$numeros[$i] é o numero $i \n";
}
<?php


3)  <?php
$frutas=['puleium','Granadilha','Lichia','Longan','Mangostao','Cherimoia'];


   for($i=1;$i<6;$i++){
   \n
      echo  " $i.  $frutas[$i] \n";
}
<?php


<?php
5) $dados = [
        0 => "Arthur Gaspar Dizarro",
        1 => "Campinas",
        2 => 17
      
        ];
        
        $dados1 = [
        0 => "João Pedro de Souza Figueiredo",
        1 => "Campinas",
        2 =>18
      
        ];
        
        $dados2 = [
        0 => "Jorge Lisboa",
        1 => "Sumaré",
        2 =>67
      
        ];
        
        if($dados[2] < 18){

            echo "-{$dados[0]} é de {$dados[1]} e tem {$dados[2]} anos ,logo, não pode dirigir \n";
        }else{
            echo "-{$dados[0]} é de {$dados[1]} e tem {$dados[2]}anos ,logo, pode dirigir";
        }
        
        if($dados1[2] < 18){

            echo "-{$dados1[0]} é de {$dados1[1]} e tem {$dados1[2]} anos ,logo, não pode dirigir";
        }else{
            echo "-{$dados1[0]} é de {$dados1[1]} e tem {$dados1[2]} anos ,logo, pode dirigir \n";
        }
        
        if($dados2[2] < 18){

            echo "-{$dados2[0]} é de {$dados2[1]} e tem {$dados2[2]} anos ,logo, não pode dirigir";
        }else{
            echo "-{$dados2[0]} é de {$dados2[1]} e tem {$dados2[2]} anos ,logo, pode dirigir";
        }
    
    
?>

