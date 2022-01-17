<!DOCTYPE html>
<html>
    <head>
       <title>Tip Calculator</title>
       <meta name="viewport" content="width=device-width, initial-scale=1.0">
       <link rel="stylesheet" href="tip.css">
    </head>
    <body>


        <main>
            <h2 id="heading">Tip Calculator</h2>
            <div>
              
              <label>Bill amount:</label>
              <input  type="number" name="" id="bill-amount">
              <span style = display:none;>Type The bill-amount</span>
              <br>
              <label>Tip-percentage:</label>
              <input type="number" name="" id="tip-percentage" >
              <span  id="span1" >Type Percentage</span>
              <br>
              <label>Tip amount:</label>
              <input type="number" name="" id="tip-amount" disabled>
              <br>
              <label>Total amount:</label>
              <input type="number" name="" id="total-amount" disabled>
              <br>
              <button onclick="onclickme()">Calculate</button>
            </div>
        </main>
        <script src="tip.js"></script>
    
    </body>
</html>
