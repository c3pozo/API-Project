 <html>
     <head>
             
        <link rel="stylesheet" href="Api stylesheet.css">
        <title>API Project</title>
        
        
        <title>Map</title>
              <meta name="viewport" content="initial-scale=1.0">
              <meta charset="utf-8">

              <div class="header">
                <h1> API Project </h1>
                <p>
                  Application Programming Interface
                   </p>
                </p>
              
              </div>

              <div class="header">
                <h1> API Project </h1>
                <p>
                 Application Programming Interface
                   </p>
              </div>


              <style>
            
                #map {
                  height: 100%;
                }
               
                html, body {
                  height: 100%;
                  margin: 0;
                  padding: 0;
                }
              </style>

    <style>
         h1 {color:rgb(224, 122, 95);
          font-size: 50px;
         margin: 20px;
          text-align: center;}
        p {color: rgb(224, 122, 95);
        margin: 20px;}
        * {
       box-sizing: border-box;}
      body {
       margin: 0;
        font-family: Arial;}
      .header {
      text-align: center;
      padding: 60px;}
         </style>
  
     <// paragraph text>
              <link rel="preconnect" href="https://fonts.googleapis.com"> 
          <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
          <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300&family=Raleway:wght@100&display=swap" rel="stylesheet">
          
          
          <//Caroline Pozo font style>
          <link rel="preconnect" href="https://fonts.googleapis.com"> 
          <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin> 
          <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&display=swap" rel="stylesheet">
     </head>
            
     <body>
              <div id="map"></div>
           <script>
                var map;
                function initMap() {
                  map = new google.maps.Map(document.getElementById('map'), {
                    center: {lat: -34.397, lng: 150.644},
                    zoom: 8
                  });
                }
           </script>
              <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyA3DAJIaDz5xeJE5bvtqF40v7eJAg442k8&callback=initMap"
              async defer>
           </script>


       </body>
      </html>

