<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>#text{
        display: block;
        position: relative;
        left: 120px;
        bottom: 35px;
    }
    #text_pre{
        display: block;
        position: relative;
        left: 135px;
        top: 40px;
        bottom: 20px;
    }
    #text_age{
        display: block;
        position: relative;
        bottom: 35px;
        left: 120px;
    }
    #text_num{
        display: block;
        position: relative;
        bottom: 35px;
        left: 130px;
    }
    #text_email{
        display: block;
        position: relative;
        top: 10px;
        left: 125px;
    }
    </style>
</head>
<body>
    <div>
        <form action="" id="formulaire">
            <div class="boite">
                <label for="nom_u">saisir votre nom :</label>
                <input type="text" id="nom_u" placeholder="entrer votre nom"><br><br><br>
                <span id="text"></span>
                <span id="text_pre"></span>
                <label for="pre_u">saisir votre prenom :</label>
                <input type="text" id="pre_u" placeholder="entrer votre prénom"><br><br><br>
                <label for="age_u">saisir votre age :</label>
                <input type="text" id="age_u" placeholder="entrer votre age"><br><br><br>
                <span id="text_age"></span>
                <label for="num_u">saisir votre numéro :</label>
                <input type="text" id="num_u" placeholder="entrer votre numéro"><br><br><br>
                <span id="text_num"></span>
                <label for="email_u">saisir votre email :</label>
                <input type="text" id="email_u" placeholder="entrer votre email">
                <span id="text_email"></span>
            </div>
        </form>
    </div>
    <script>
        document.getElementById("nom_u").addEventListener('input',function(){
            var nom = document.getElementById("nom_u").value;
            var text = document.getElementById("text");
            function alpha(ch)
        {ch=ch.toUpperCase();
        i=0;
    while((ch.charCodeAt(i)>=65)&&(ch.charCodeAt(i)<=90)&&(i<ch.length))
        i=i+1;
    if(i==ch.length)  return true;
    return false
    
    }
    if(alpha(nom)){
        text.innerHTML = "votre nom est valider";
        text.style.color="#00ff00";
    }
    else{
        text.innerHTML = "votre nom est invalide";
        text.style.color = "red";
    }


        })
        document.getElementById("pre_u").addEventListener('input',function(){
            var prenom = document.getElementById("pre_u").value;
            var textpre = document.getElementById("text_pre");
            function alpha(ch)
        {ch=ch.toUpperCase();
        i=0;
    while((ch.charCodeAt(i)>=65)&&(ch.charCodeAt(i)<=90)&&(i<ch.length))
        i=i+1;
    if(i==ch.length)  return true;
    return false
    
    }
    if(alpha(prenom)){
        textpre.innerHTML = "votre prenom est valider";
        textpre.style.color="#00ff00";
    }
    else{
        textpre.innerHTML = "votre prenom est invalide";
        textpre.style.color = "red";
    }
})
document.getElementById("age_u").addEventListener('input',function(){
            var age = document.getElementById("age_u").value;
            var textage = document.getElementById("text_age");
            function agee(ch)
        {ch=ch.toUpperCase();
        i=0;
    while((ch.charCodeAt(i)>=48)&&(ch.charCodeAt(i)<=57))
        i=i+1;
    if(i==ch.length)  return true;
    return false
    
    }
    if(agee(age)){
        textage.innerHTML = "votre age est valider";
        textage.style.color="#00ff00";
    }
    else{
        textage.innerHTML = "votre age est invalide";
        textage.style.color = "red";
    }


        })
        document.getElementById("num_u").addEventListener('input',function(){
            var num = document.getElementById("num_u").value;
            var textnum = document.getElementById("text_num");
            function numero(ch)
        {ch=ch.toUpperCase();
        i=0;
    while((ch.charCodeAt(i)>=48)&&(ch.charCodeAt(i)<=57))
        i=i+1;
    if(i==ch.length)  return true;
    return false
    
    }
    if(numero(num)){
        textnum.innerHTML = "votre votre numéro est valider";
        textnum.style.color="#00ff00";
    }
    else{
        textnum.innerHTML = "votre numéro est invalide";
        textnum.style.color = "red";
    }


        })
        function alphas(ch)
    {
    ch=ch.toUpperCase();
    i=0;
    while((ch.charCodeAt(i)>=65)&&(ch.charCodeAt(i)<=90)&&(i<ch.length))
    i=i+1;
    if(i==ch.length) return true;
      return false;
    }
    function alphanum(ch){
    ch=ch.toUpperCase();
    i=0;
    while((ch.charCodeAt(i)>=65)&&(ch.charCodeAt(i)<=90)&&(i<ch.length)||(ch.charCodeAt(i)>=48)&&(ch.charCodeAt(i)<=57)&&(i<ch.length))
    i=i+1;
    if(i==ch.length) return true;
      return false;

    }
    document.getElementById("email_u").addEventListener('input',function(){
        var email = document.getElementById("email_u").value;
        var textemail = document.getElementById("text_email");
        function estmail(ch)
    {
      a= ch.indexOf("@");
      b= ch.lastIndexOf(".");
      x= ch.slice(0,a);
      y= ch.slice(a+1,b);
      z= ch.slice(b+1);
      if ((a ==-1)||(b == -1)||(! alphanum(x))|| (!alphanum(y))||(!alphas(z))||(z.length !=2 && z.length !=3)||(a >= b))
      return false;
      return true;
      
    }
    if(estmail(email)){
        textemail.innerHTML = "votre email est valider";
        textemail.style.color="#00ff00";
    }
    else{
        textemail.innerHTML = "votre email est non valider";
        textemail.style.color="red";

    }
})
    </script>
    
</body>
</html>
