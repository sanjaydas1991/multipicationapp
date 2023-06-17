# multipicationapp

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>multipication app</title>
    <link rel="stylesheet" href="style.css">

    </head>
    <body>
        <form class="form" id="form">
            <h4 class="score" id="score">Score: 0</h4>
            <h1 id="question">what is the answer if multiply 1 by 1 ?</h1>
            <input type="text" class="input" id="input" placeholder="Enter your answer" autofocus autocomplete="off"/>
            <button type="submit" class="btn">Submit</button>
        </form>
        <script src="index.js"></script>
    </body>
</html>

FOR CSS
body{
    margin: 0;
    display: flex;
    justify-content: center;
    height: 100vh;
    align-items: center;
    text-align: center;
    background: url("https://images.unsplash.com/photo-1682018092446-2fe62350cfad?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80");
    background-position: center;
    font-family: cursive;


}
.form{
    background-color: white;
    padding: 20px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    border-radius: 10px;
    margin: 10px;

}
.input{
    display: block;
    width: 100%;
    box-sizing: border-box;
    font-size: 30px;
    padding: 10px;
    border: solid 4px green ;
    color: blue;
    text-align: center;



}
.input ::placeholder{
    color: lightgreen;
    font-family: inherit;

}
.btn{
    background-color:green;
    color: white;
    cursor: pointer;
    border: none;
    display: block;
    padding-left: 10px;
    font-family: cursive;
    font-size: 20px;
    width: 100%;
    margin: 20px 0;
    border-radius: 5px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.3);

}
.btn:hover{
    filter: brightness(0.9);

}
.h4{
    color: green;
    text-align: right;
}
