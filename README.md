# Calculo-das-medias
Como calcular média do aluno
Atividade da disciplina Lógica de Programação Algoritimica





    <html>
     <body>
      <script type="text/javascript">
        var media, n1, n2, n3, n4, n5 ;

    n1= prompt ("Informe a primeira nota: ");
    n1= eval (n1) ;

    n2= prompt ("Informe a segunda nota: ");
    n2= eval (n2) ; 

    n3= prompt ("Informe a terceira nota: "); 
    n3= eval (n3) ;
    
    n4= prompt ("Informe a quarta nota: ");
    n4= eval (n4) ;
    
    n5= prompt ("Informe a quinta nota: ");
    media = ((n1 + n2 + n3 + n4)/5*0.4) + n5 ; 
        if ( media >= 7 )  {            
        console.log ("Aprovado");
        } 
     else 
    { 
      if ( media < 4 ){
       console.log("Reprovado");
    }
    else {
     if ( media > 4 < 7 ) 
    {console.log ("Recuperação");
    } //Quero dizer que a média é maior que 4 e menor que 7
    }
          
          </script>
          </body>
         </html>
