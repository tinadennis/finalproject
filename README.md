<!DOCTYPE html>

<html lang="en">
    <head>
    <meta charset=="UTF-8" />
    <title>SeniorSortor.com </title>
     <script>
            function greet()
            {
              let name = document.querySelector('#name').value;
              if (name == '')
               {
                  name = 'Welcome to Senior Sorter, this will help seniors save files and access them easier.';
                   
               }
                document.querySelector('#result').innerHTML =  'Hello, ' + name + '!'              
            } 
        </script>
    <link rel="stylesheet" href="https://volodymyrkushnir.com/assets/stylesheets/base.css">
   </head>
    <body style="font-family:cursive">
       
         <form onsubmit="greet(); return false;">
            <input type="text" id="name">
            <input type="submit">
        </form>
        <div id= "result">
        Hello!
        </div>
    <script>
        </script>    
      <main>
      <article>
        <div class="page" style="border-color: red;">
          <div class="stackable grid">
            <div class="row">
              <div class="three wide center aligned column">
                <!-- Avatar -->
              </div>
              <div class="thirteen wide column">
                <div class="stackable grid">
                  <div class="sixteen wide column">
    
        <h1>Why was senior sortor created?</h1>
                     
        <p>
        Senior Sortor was created by Tina Dennis because not only her mother but her grandmother has alot of issue accessing files they have stored. This is a easier way for people who are not so great with technology or just in general saving information to a file better.
        </p>
        <p>
            <link href="http://fonts.googleapis.com/css?family=Corben:bold" rel="stylesheet" type="text/css">       
         </p>          
       
          <style>
            table
            {
                border: 20px solid red;
                border-collapse: collapse;
            }
            td
            {
                border: 9px solid yellow;
                padding: 60px;
            
            }
        
            .header
            {
                background-color:indianred;
            }
        
        </style>
    </head>
    <body>  
        
  <form action="/submit_data.php" method="get">
  <label>Name:</label>
  <input type="text" id="uname" name="uname"><br><br>
  <label> Hobbies:</label>
  <input types="text" id="uhobbies" name="uhobbies"><br><br>
  <label>Age:</label>
  <input type="text" id="uage" name="uage"><br><br>
  <label>Music Genre:</label>
  <input type="text" id="umusicgenre" name="umusicgenre"><br><br>
  <button type="submit">Submit</button>
    </form> 
        <script>
        <script>
function SubForm (){
    $.ajax({
        url:'https://docs.google.com/spreadsheets/d/1TZfIWVVmgeCf7mYQ_3FG5Xw-cSqrNIZO_44UP9QeFAg/edit#gid=0/',
        type:'post',
        data:$("#myForm").serializeArray(),
        success: function(){
          alert("Form Data Submitted :)")
        },
        error: function(){
          alert("There was an error :(")
        }
    });
} 
        </script>
    </body>
</html>
