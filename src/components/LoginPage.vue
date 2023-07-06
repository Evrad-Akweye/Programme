<template>
  <div class="login">
        <div class="Connexion"><i><b>CONNEXION</b></i></div>
        <div class="login1">
            <p>Login<span>*</span></p>
            <input type="text" class="input1" placeholder="NOM">
        </div>
        <a href="#" >Mot de passe oublié ?</a> 
        <div class="motdepasse">
          <p>Mot de passe<span>*</span></p>
            <input type="password" class="input2" placeholder="PASSWORD" >
        </div>
        <div class=btn>
            <input type="submit" class="input3" value="VALIDER">
        </div>
    </div>
</template>
<script>
export default {
  name: 'LoginPageComponent',
  props: {
    
  }
}
</script>
<style scoped>
      .login
      {
          background-color: antiquewhite;
          margin: 150px;
          height: 400px;
          width: 450px;
          border-radius:30px ;
          box-shadow: 0px 0px 10px 10px black;
          margin-left: 450px;
          margin-bottom: 50px;
      }
      .input1,.input2
      {
          width:420px;
          height: 50px;
          margin-left: 10px;
          margin-right: 10px;
          background-color: burlywood;
          font-size: 25px;
        }
        .Connexion
        {
            text-align: center;
            font-size: 3em;
            color: green;
        }
        a
        {
            text-align:end;
            margin-top: 5px;
            margin-right: 10px;
            margin-left: 280px;
        }
        .input3
        {
            width: 150px;
            height: 40px;
            background-color: yellowgreen;
            margin-inline-start: 150px;
            border-radius: 10px;
            margin-top: 40px;
        }
        span
        {
          color: red;
        }
        p
        {
            font-size: 1.5em;
            margin-left: 10px;
            margin-bottom: 5px;
        }
        .login1
        {
            margin-top:10px ;
        }
        .motdepasse
        {
            margin-top: 10px;
        }
        
        
</style>