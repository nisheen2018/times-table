times-table
===========
<html>
<head />
<body> 

<script type="text/javascript">
document.write("<h1>Multiplication table</h1>");
document.write("<table border=2 width=50%");

for (var i = 1; i <= 10; i++ ) {
  document.write("<tr>");
  document.write("<td>" + i + "</td>");
 
   for ( var x = 2; x <= 10; x++ ) {
        document.write("<td>" + i * x + "</td>");
    }

   document.write("</tr>");
}

document.write("</table>");
</script>

</body>
</html>
