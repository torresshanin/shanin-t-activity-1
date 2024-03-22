 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
    <title>Activity Bootstrap</title>
    <style>
         .col {
            background-color: #47a7f5; /* Blue */
            color: white;
            text-align: center;
            padding: 20px;
            border: 2px solid #47a7f5; /* Blue */
            border-radius: 10px;
            margin-bottom: 10px;
         }

         .col-8 {
            background-color: #f55e47; /* Red */
            color: white;
            text-align: center;
            padding: 20px;
            border: 2px solid #f55e47; /* Red */
            border-radius: 10px;
            margin-bottom: 10px;
         }

         .col-5 {
             background-color: #47f579; /* Purple */
             color: white;
             text-align: center;
             padding: 20px;
             border: 2px solid #47f579; /* Purple */
             border-radius: 10px;
             margin-bottom: 10px;  
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="row">
            <div class="col">1</div>
            <div class="col">2</div>
            <div class="col">3</div>
            <div class="col">4</div>
            <div class="col">5</div>
            <div class="col">6</div>
            <div class="col">7</div>
            <div class="col">8</div>
            <div class="col">9</div>
            <div class="col">10</div>
            <div class="col">11</div>
            <div class="col">12</div>
         </div>
     </div>
     <div class="container">
         <div class="row">
            <div class="col-8">8</div>
            <div class="col-5">5</div>
         </div>    
     </div>
     <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
