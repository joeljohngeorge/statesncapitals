# statesandcapitals
<html> <head> <title> Using Javascript </title>
<script language="Javascript">
function capital()
{var i,ans;
i=document.frm.States.selectedIndex;
switch(i)
{ case 0:ans="Amaravati";
  break;
 case 1:ans="Ittanagar";
  break;
case 2:ans="Dispur";
  break;
 case 3:ans="Patna";
  break;
case 4:ans="Raipur";
  break;
case 5:ans="Panaji";
break;
case 6:ans="Gandhinagar";
break;
case 7:ans="Chandigarh";
break;
case 8:ans="Shimla";
break;
case 9:ans="Ranchi";
break;
case 10:ans="Bengaluru";
break;
case 11:ans="Thiruvananthapuram";
break;
case 12:ans="Bhopal";
break;
case 13:ans="Mumbai";
break;
case 14:ans="Imphal";
break;
case 15:ans="Shillong";
break;
case 16:ans="Aizawl";
break;
case 17:ans="Kohima";
break;
case 18:ans="Bhuvaneshwar";
break;
case 19:ans="Chandigarh";
break;
case 20:ans="Jaipur";
break;
case 21:ans="Gangtok";
break;
case 22:ans="Chennai";
break;
case 23:ans="Hyderabad";
break;
case 24:ans="Agarthala";
break;
case 25:ans="Lucknow";
break;
case 26:ans="Dehradun";
break;
case 27:ans="Kolkata";
break;
 }
document.frm.t1.value=ans;
}
</script> </head>
<body bgcolor="gray"> <form name="frm">
<h2 align="center"> Indian states and their capitals </h2>
<select Name="States" size=1>
<option name="Andhra Pradesh" >Andhra Pradesh
 <option name="Arunachal Pradesh">Arunachal Pradesh
 <option name="Assam">Assam
  <option name="Bihar"> Bihar 
   <option name="Chhattisgarh"> Chhattisgarh 
     <option name="Goa"> Goa
      <option name="Gujarat"> Gujarat
        <option name="Haryana"> Haryana
          <option name="Himachal Pradesh"> Himachal Pradesh
              <option name="Jharkhand"> Jharkhand
                 <option name="Karnataka"> Karnataka
                   <option name="Kerala"> Kerala
                     <option name="Madhya Pradesh"> Madhya Pradesh
                      <option name="Maharashtra"> Maharashtra
                        <option name="Manipur"> Manipur  
                         <option name="Meghalaya"> Meghalaya
                          <option name="Mizoram"> Mizoram
                           <option name="Nagaland"> Nagaland
                            <option name="Odisha"> Odisha
                             <option name="Punjab"> Punjab
                              <option name="Rajasthan"> Rajasthan
                               <option name="Sikkim"> Sikkim
                                <option name="Tamil Nadu"> Tamil Nadu
                                  <option name="Telangana">  Telangana
                                    <option name="Tripura"> Tripura
                                      <option name="Uttar Pradesh"> Uttar Pradesh
                                        <option name="Uttarakhand"> Uttarakhand
                                          <option name="West Bengal"> West Bengal                     
  
</select><br><br>
<input type="text" Name="t1"> <br><br>
<Input type="button"  Value="show" onClick="capital()">

</form>  </body> </html>
