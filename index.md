<!doctype html>
<html lang="en">
<head>
  <title>Periodic Table</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>


  <style type="text/css">
    p
    {
      margin:0;
      padding:0;
      font-size:60px;
    }
    .hiddencells{
      visibility: hidden;
    }

    .serif {
      font-family: "Times New Roman", Times, serif;
    }

    .element{
      font-size: 5rem;

    }

    .atomicnumber{
      font-size: 3rem;      
    }

    .elementname, .elementweight{
     font-size: 1rem; 
     display: none;
    }

    .elementnamebox{
      font-size: 7rem;
    }

    .elementweightbox{
      font-size: 4rem;
    }

    .atomicnumberbox{
      font-size: 5rem;
    }
  </style>

  <body class="serif">
    <table id="maintable" class="table table-bordered">
      <thead>
        <tr>
    
          <th scope="col">1</th>
          <th scope="col">2</th>
          <th scope="col">3</th>
          <th scope="col">4</th>
          <th scope="col">5</th>
          <th scope="col">6</th>
          <th scope="col">7</th>
          <th scope="col">8</th>
          <th scope="col">9</th>
          <th scope="col">10</th>
          <th scope="col">11</th>
          <th scope="col">12</th>
          <th scope="col">13</th>
          <th scope="col">14</th>
          <th scope="col">15</th>
          <th scope="col">16</th>
          <th scope="col">17</th>
          <th scope="col">18</th>

        </tr>
      </thead>
      <tbody>
        <tr>
          <td id="tdH">
            <p class="atomicnumber">1</p>
            <p class="element">H</p>
            <p class="elementname">Hydrogen</p>
            <p class="elementweight">1.008</p>
          </td>
          <td class="" colspan="16" align="center">
            <span id="namebox" class="elementnamebox">Element Name</span>
          </td>
          <td id="tdHe">
            <!-- He -->
            <p class="atomicnumber">2</p>
            <p class="element">He</p>
            <p class="elementname">Helium</p>
            <p class="elementweight">4.0026</p>
          </td>
        </tr>
        <tr>
          <td id="tdLi">
          <!-- Li -->
            <p class="atomicnumber">3</p>
            <p class="element">Li</p>
            <p class="elementname">Lithium</p>
            <p class="elementweight">6.94</p>
          </td>
          <td id="tdBe">
            <!-- Be -->
            <p class="atomicnumber">4</p>
            <p class="element">Be</p>
            <p class="elementname">Beryllium</p>
            <p class="elementweight">9.0122</p>
          </td>
          <td class="" colspan="10" align="center">
              <span id="idatomicbox" class="atomicnumberbox">Atomic Number</span>
          </td>
          <td id="tdBo">
            <p class="atomicnumber">5</p>
            <p class="element">Bo</p>
            <p class="elementname">Boron</p>
            <p class="elementweight">10.81</p>
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>

          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
        </tr>
        <tr>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td colspan="9" align="center">
              <span id="idweightbox" class="elementweightbox">Element Weight</span>
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
        </tr>
        <tr>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
        </tr>
        <tr>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
        </tr>
        <tr>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
        </tr>
        <tr>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
          <td>
            <p class="atomicnumber">N</p>
            <p class="element">El</p>
            <p class="elementname">ElName</p>
            <p class="elementweight">ElWeight</p>            
          </td>
        </tr>
      </tbody>
    </table>

  </body>

<script type="text/javascript">
  
  $(document).ready(
    function(){
      // alert("pronto");
      $("td").hover(function(){
          $(this).css("background-color", "gray");
          $(this).css("color", "white");
        },
        function(){
          $(this).css("background-color","white");
          $(this).css("color","black");
        }
      );

      $("#tdH").hover(
        function(){
          $("#namebox").html("Hydrogen");
          $("#idatomicbox").html("1");
          $("#idweightbox").html("Hydrogen");
        },
        function(){
          $("#namebox").html("Element Name");
          $("#idatomicbox").html("Atomic Number");
          $("#idweightbox").html("Element Weight");
        }
      );

      $("#tdH").hover(
        function(){
          $("#namebox").html("Hydrogen");
          $("#idatomicbox").html("1");
          $("#idweightbox").html("1.008");
        },
        function(){
          $("#namebox").html("Element Name");
          $("#idatomicbox").html("Atomic Number");
          $("#idweightbox").html("Element Weight");
        }
      );

      $("#tdHe").hover(
        function(){
          $("#namebox").html("Helium");
          $("#idatomicbox").html("2");
          $("#idweightbox").html("4.0026");
        },
        function(){
          $("#namebox").html("Element Name");
          $("#idatomicbox").html("Atomic Number");
          $("#idweightbox").html("Element Weight");
        }
      );

      $("#tdLi").hover(
        function(){
          $("#namebox").html("Lithium");
          $("#idatomicbox").html("3");
          $("#idweightbox").html("6.94");
        },
        function(){
          $("#namebox").html("Element Name");
          $("#idatomicbox").html("Atomic Number");
          $("#idweightbox").html("Element Weight");
        }
      );

      $("#tdBe").hover(
        function(){
          $("#namebox").html("Beryllium");
          $("#idatomicbox").html("4");
          $("#idweightbox").html("9.0122");
        },
        function(){
          $("#namebox").html("Element Name");
          $("#idatomicbox").html("Atomic Number");
          $("#idweightbox").html("Element Weight");
        }
      );

      $("#tdBo").hover(
        function(){
          $("#namebox").html("Boron");
          $("#idatomicbox").html("5");
          $("#idweightbox").html("10.81");
        },
        function(){
          $("#namebox").html("Element Name");
          $("#idatomicbox").html("Atomic Number");
          $("#idweightbox").html("Element Weight");
        }
      );
    }
  );

</script>


</html>
