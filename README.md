# FoodApplication.vb
Simple demo of food application using (vb.net,firebase)<br>
'---------------------------fire base connection -------------------------------

Imports FireSharp.Config
Imports FireSharp.Interfaces
Imports FireSharp.Response
Public Class Form2
<br>
 <br>   Private facon As New FirebaseConfig() With
   <br>            {
 <br>              .AuthSecret = "Sh0fpeLNcJZMbrLKkuvos8BQQVFqpwh0SEikqarx",
  <br>             .BasePath = "https://vbnet-9d25a-default-rtdb.firebaseio.com/"
   <br> }

   

  '----------------to check succesfull connection -----------------
   <br>     Try
   <br>         client = New FireSharp.FirebaseClient(facon)

   <br>     Catch
   <br>         MessageBox.Show("there is problem with your internet ")
   <br>     End Try

  
![image](https://user-images.githubusercontent.com/91798995/171521630-4a39e7d3-51e9-4829-8afa-4f06b1e7fab9.png)
<br>
<br>
-----------------------------for crazy effect on buttons ,labels etc install gunna package-----------------

