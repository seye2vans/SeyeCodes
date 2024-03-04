# Valentines-Day

<!DOCTYPE html>
    <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-wedith,initial-scale=1.0">
            <title>Envelope Styling</title>
 <style>
    #envelope{
        margin: 150px;
        position: relative;
        width: 200px;
        height: 160px;
        margin-left: auto;
        margin-right: auto;
        top: 150px;
        background-color: #f97Dc4;
        box-shadow: 0 4px 20px rgb(0, 0,0,0.2);
        text-align: center;
        text-decoration: dotted;
    }
    #message{
        
        margin-top: 10px;
        margin-bottom: 20px;
    }
    #buttons{
        display: flex;
        gap: 10px
    }
    .button{
        padding: 10px;
        cursor: pointer;
        border: none;
        background-color: #fff;
        color: #333;
        border-radius: 5px;
    }
</style>
        </head>
<body>
    <div id="envelope">
            <p id= "message">    Click "Open"  to reveal the message.</p>
            <div class="button-container">
                <button
                 onclick="openEnvelope()">Open</button>
                 
                <button
                 onclick="resetEnvelope()">Reset</button>
        </div>
        <script>
            function openEnvelope(){
                document.getElementById("message").innerText =   "Will you be my VAL?";
            }
            function resetEnvelope(){
                document.getElementById("message").innerText= "Click \"Open\" to reveal the message.";
            }
        </script>
</body>
    </html>   
