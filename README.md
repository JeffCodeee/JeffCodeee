<!DOCTYPE html>

<html>
    <head>
        <title>Aula 26/08/2024</title> 
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <h1>Praticar</h1>
        <script>
            function pularlinha() {
                document.write("<hr>");
    }
         var nome=prompt("Digte o nome e tecle enter");
         var n1=parseFloat(prompt("Digite a Nota1 e tecle enter"));
         var n2=parseFloat(prompt("Digite a Nota2 e tecle enter"));
         var n3=parseFloat(prompt("Digite a Nota3 e tecle enter"));
         var n4=parseFloat(prompt("Digite a Nota4 e tecle enter"));
         var faltas=parseInt(prompt("Digite as faltas e tecle enter"));
         var media=(n1+n2+n3+n4)/4;
         if(media>=7 && faltas<=5){
         document.write("Nome:"+nome);
         pularlinha();
document.write("Nome:"+nome);
         pularlinha();
         document.write("Média: "+media);
         pularlinha();
         document.write("Situação: Reprovado por faltas");   
         }else if(media<7 && faltas<=5){
         document.write("Nome:"+nome);
         pularlinha();
         document.write("Média: "+media);
         pularlinha();
         document.write("Situação: Reprovado por média");    
         }
         else{
         document.write("Nome:"+nome);
         pularlinha();
         document.write("Média: "+media);
         pularlinha();
         document.write("Situação: Reprovado por média e por faltas");
     }           
        </script>
    </body>
</html>


<!DOCTYPE html>

<html>
    <head>
        <title>For</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
    </head>
    <body>
        <div>Laço de Repetição</div>
        <script>
     var cont=0;
     while(cont<10){
         document.write("Repetição "+cont+"<br>");
         cont++;
     }
    
 
            
        </script>
    </body>
</html>
