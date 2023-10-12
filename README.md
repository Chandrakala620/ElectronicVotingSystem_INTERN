# ElectronicVotingSystem_INTERN
WIPRO
IMPLEMENTAION Method:
Model Code: 
Registration page: <?php include('includes/config.php'); 
$collect=''; if($_POST){ 
$collect = insert($_POST); 
} 
 
?> 
 
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" 
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"> 
<html xmlns="http://www.w3.org/1999/xhtml"> 
 
<head> 
<meta http-equiv="content-type" content="text/html; charset=utf-8" /> 
<title>|| VOTING REGISTRATION SYSTEM||</title> 
<meta name="keywords" content="" /> 
<meta name="description" content="" /> 
<link href="default.css" rel="stylesheet" type="text/css" /> 
<style type="text/css"> 
<!-- 
.style11 {font-size: 18px; font-weight: bold; } 
.style13 {font-size: x-large; font-weight: bold; color: #000000; } 
.style2 { 	color: #FF00FF; 
font-weight: bold; 
} 
.style3 { 
 font-size: 18px;  color: #000000; 
} 
.style4 {font-size: 18px; color:#FFFFFF; } 
.style5 {font-size: 12px} 
--> 
</style> 
</head> 
<body> 
<div id="header"> 
  <table width="200" align="center"> 
    <tr> 
      <td height="212"><img src="images/header1.jpg" alt="" width="770" height="210" /></td> 
    </tr> 
  </table> 
</div> 
<div id="menu"> 
 	<ul> 
 	 	<li> <a href="index.php"> |  Home  |</a></li> 
 	 	<li> 
 	 	  <a href="login.php">|  Voting  |</a></li> 
 	 	<li> 
 	 	  <a href="result.php">|  Result  |</a></li> 
 	 	<li> 
 	 	  <a href="login.php" >|  Login  |</a></li> 
</ul> 
</div> 
<div id="content"> 
 	<div id="left"> 
    <p style="text-align: center; color:#00CCEEFF;"><strong><marquee  behavior="scroll"> 
</marquee></strong></p> 
</div> 
  <th height="41" colspan="2" scope="col"><h1><center> 
   </center> 
    
   </h1></th> 
 	</div> 
</div> 
<div id="footer"> 
  <table width="651" border="0" align="center"> 
    <tr> 
      <th width="645" height="783" scope="col"><table width="667" height="31" border="0" align="center" bgcolor="#00FF00"> 
          <tr> 
            <th 	width="607" 	scope="col"><div 	align="center"><span class="style4">REGISTRATION FORM </span></div></th> 
          </tr> 
          <tr> 
            <th 	scope="col"><div 	"align="center"  
style="background:#FF00OO"  > 
          <h1 	 	 	 	align="center"><strong><?php 	echo 	$collect; 
?></strong></h1> 
          </div>&nbsp;        </th> 
          </tr> 
        </table> 
          <form action="" method="post" enctype="multipart/form-data" id="form1"> 
            <table width="431" border="0" align="center" cellpadding="3" cellspacing="17"> 
              <tr> 
                <th 	width="122" 	scope="col"><div 
align="justify">FIRSTNAME</div></th> 
                <th width="246" scope="col"><div align="justify"> 
                    <input type="text" name="txtfirstname" /> 
                </div></th> 
              </tr> 
              <tr> 
                <td><div align="justify">LASTNAME</div></td> 
                <td><div align="justify"> 
                    <input type="text" name="txtlastname" /> 
                </div></td> 
              </tr> 
              <tr> 
                <td><div align="justify">SEX</div></td> 
                <td><div align="justify"> 
                  <label> 
                  <select name="txtsex"> 
                    <option value="Female">Female</option> 
                    <option value="Male">Male</option> 
                  </select> 
                  </label> 
                </div></td> 
              </tr> 
              <tr> 
                <td><div align="justify">AGE</div></td> 
                <td><div align="justify"> 
                    <input type="text" name="txtage" /> 
                </div></td> 
              </tr> 
              <tr> 
                <td><div align="justify">ADDRESS</div></td> 
                <td><div align="justify"> 
                    <input type="text" name="txtaddress" /> 
                </div></td> 
              </tr> 
              <tr> 
                <td><div align="justify">STATE</div></td> 
                <td><div align="justify"> 
                    <input type="text" name="txtstate" /> 
                </div></td> 
              </tr> 
              <tr> 
                <td><div 	align="justify">COUNTRY 	<span class="style5"></span></div></td> 
                <td><div align="justify"> 
                    <input type="text" name="txtcountry" /> 
                </div></td> 
              </tr> 
              <tr> 
                <td><div align="justify">PHONE</div></td> 
                <td><div align="justify"> 
                    <input type="text" name="txtphone" /> 
                </div></td> 	 
              </tr> 
              <tr> 
                <td><div align="justify">E-MAIL</div></td> 
                <td><div align="justify"> 
                    <input type="text" name="txtemail" /> 
                </div></td> 
              </tr> 
              <tr> 
                <td><div 	align="justify">PREFERED 	ELECTION 
DISTRICT </div></td> 
                <td><div align="justify"> 
                    <input type="text" name="txtelectiondist" /> 
                </div></td> 
              </tr> 
              <tr> 
                <td>OCCUPATION</td> 
                <td><div align="justify"> 
                    <input type="text" name="txtoccupation" /> 
                </div></td> 
              </tr> 
              <tr> 
                <td>USERNAME</td> 
                <td><input type="text" name="txtusername" /></td> 
              </tr> 
              <tr> 
                <td>VOTER'S ID </td> 
                <td><input 	type="text" 	name="txtelectionid" 	value=" 
"/></td> 
              </tr> 
              <tr> 
                <td><input 	type="submit" 	name="Submit" value="Registered" /></td> 
                <td>&nbsp;</td> 
              </tr> 
            </table> 
          </form></th> 
    </tr> 
  </table> 
</div> 
</body> 
</html> 
Presidential page: 
<?php 
 
$host="localhost"; // Host name 
$username="root"; // Mysql username 
$password=""; // Mysql password 
$db_name="evoting"; // Database name 
 
 
//anpp if(isset($_POST['Submit'])) { 
 
// Connect to server and select databse. 
mysql_connect("$host", "$username", "$password")or die("cannot connect"); mysql_select_db("$db_name")or die("cannot select DB"); 
 
 
 //$e_id ="inec/ 396" ; 
// 	$attempt  = "1"; 
//$pres_result = mysql_query("SELECT pres_attempts FROM attempts where election_id ='$e_id'"); 
 //while($pres_row = mysql_fetch_row($pres_result)){ 
 //$pres_attempt =  $pres_row ['pres_attempts']; 
  // if ($pres_ attempt >= 1){ 
//header("location: error.php"); 
  
$names = 0; 
$result = mysql_query("SELECT pres_count FROM presidential_votes where party ='ANPP'");  while($row = mysql_fetch_row($result)){ 
   $names =  $row [0]; 
   $names =  $names + 1; 
    
   mysql_query("UPDATE presidential_votes SET pres_count=$names WHERE party ='ANPP' "); 
 mysql_query("UPDATE attempts SET pres_attempts = '$attempt' 
WHERE election_id ='$e_id' "); 
  } 
 }  
//pdp if(isset($_POST['Submit2'])) { // Connect to server and select databse. 
mysql_connect("$host", "$username", "$password")or die("cannot connect"); mysql_select_db("$db_name")or die("cannot select DB"); 
 
$names2 =  0; 
//$regnum = $_POST['txtnumber']; 
$result = mysql_query("SELECT pres_count FROM presidential_votes where party ='pdp'");  while($row = mysql_fetch_row($result)){ 
   // $names = $row[1]; 
 $names2 =  $row [0]; 
   $names2 =  $names2 + 1; 
    
   mysql_query("UPDATE presidential_votes SET pres_count=$names2 
WHERE party ='pdp' "); 
  }  
} 
 
//acn if(isset($_POST['Submit3'])) { // Connect to server and select databse. 
mysql_connect("$host", "$username", "$password")or die("cannot connect"); mysql_select_db("$db_name")or die("cannot select DB"); 
 
$names3 =  0; 
//$regnum = $_POST['txtnumber']; 
$result = mysql_query("SELECT pres_count FROM presidential_votes where party ='acn'");  while($row = mysql_fetch_row($result)){ 
   // $names = $row[1]; 
 $names3 =  $row [0]; 
   $names3 =  $names3 + 1; 
    
   mysql_query("UPDATE presidential_votes SET pres_count=$names3 
WHERE party ='acn' "); 
  }  
} 
 
?> 
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" 
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"> 
<html xmlns="http://www.w3.org/1999/xhtml"> 
 
<head> 
<meta http-equiv="content-type" content="text/html; charset=utf-8" /> 
<title>|| VOTING REGISTRATION SYSTEM||</title> 
<script type="text/javascript"> function confirm_vote(textfield){ 
if(confirm("ARE U SURE YOU WISH TO VOTE FOR "+textfield+" 
?")) 
{ return  true; 
} else {return false; 
} 
 	  
} 
 
function error($msg){ if(confirm("double voting "+$msg+" ?")) 
{ return  true; 
} else {return false; 
} 
 	  
} 
</script> 
 
<meta name="keywords" content="" /> 
<meta name="description" content="" /> 
<link href="default.css" rel="stylesheet" type="text/css" /> 
<style type="text/css"> 
<!-- 
.style11 {font-size: 18px; font-weight: bold; } 
.style13 {font-size: x-large; font-weight: bold; color: #000000; } 
.style2 { 	color: #FF00FF;  	font-weight: bold; 
} 
.style3 { 
 font-size: 18px;  color: #000000; 
} 
.style4 {font-size: 18px; color: #FFFFFF; } 
.style5 {font-size: 12px} .style8 {color: #990000} 
--> 
</style> 
</head> 
<body> 
<div id="header"> 
  <table width="200" align="center"> 
    <tr> 
      <td height="212"><img src="images/header1.jpg" alt="" width="770" height="210" /></td> 
    </tr> 
  </table> 
</div> 
<div id="menu"> 
 	<ul> 
 	 	<li> <a href="index.php"> |  Home  |</a></li> 
 	 	<li> 
 	 	  <a href="login.php">|  Voting  |</a></li> 
 	 	<li> 
 	 	  <a href="result.php">|  Result  |</a></li> 
 	 	<li> 
 	 	  <a href="login.php" >|  Login  |</a></li> 
 	</ul> 
</div> 
<div id="content"> 
 	<div id="left"> 
    <p 	style="text-align:center; 	color:#FF0000;"><strong><marquee  behavior="scroll"> 
    </marquee></strong></p> 
</div> 
  <th height="41" colspan="2" scope="col"><h1><center> 
   </center> 
    
   </h1> 
  </th> 
</div> 
<div id="footer"> 
  <p><a href="logout.php">LOGOUT</a></p> 
  <table width="719" border="0" align="center"> 
    <tr> 
      <th width="713" height="661" scope="col"><form id="form1" method="post" action=""> 
          <table width="671" border="0" align="center"> 
            <tr> 
              <th 	width="233" 	bgcolor="#00FF66" 	scope="col"><span class="style8">CANDIDATE</span></th> 
              <th 	width="197" 	scope="col"><span 
class="style8">NAME</span></th> 
              <th 	width="149" 	bgcolor="#00FF66" 	scope="col"><span class="style8">PARTY</span></th> 
              <th width="74" bgcolor="#993300" scope="col">UPDATED 
RESULT </th> 
            </tr> 
            <tr> 
              <td 	height="151"><img src="images/contact1.jpg" alt="" width="177" height="218" /></td>               <td>MRS CYNTHIA ALABA </td> 
              <td><input type="submit" name="Submit" value="ANPP"  onclick="return confirm_vote(")/></td>               <td><?php echo $names;  ?>&nbsp;</td> 
            </tr> 
            <tr> 
              <td 	height="150"><img 	src="images/1.jpg" 	alt="" width="180" height="182" /></td>               <td>PROF. ELIJAH AMINU </td> 
              <td><input type="submit" name="Submit2" value="PDP" onclick="return confirm_vote(")/></td> 
              <td><?php echo $names2;  ?></td> 
            </tr> 
            <tr> 
              <td 	height="105"><img src="images/contact3.jpg" alt="" width="178" height="183" /></td> 
              <td>DECONESS SALOME SEUN (JP.) </td> 
              <td><input type="submit" name="Submit3" value="ACN" onclick="(")return confirm_vote(")/></td> 
              <td><?php echo $names3; ?></td> 
            </tr> 
            <tr> 
              <td height="105">&nbsp;</td> 
              <td>&nbsp;</td> 
              <td><a href="pres_result.php">click here to view all parties result </a></td> 
              <td>&nbsp;</td> 
            </tr> 
          </table> 
      </form></th> 
    </tr> 
    <tr> 
      <th height="17" scope="col">&nbsp;</th> 
    </tr> 
  </table> 
  <p>&nbsp;</p> 
 	<p>&nbsp;</p> 
</div> 
</body> 
</html> 
Login page: <?php  include('includes/config.php'); 
$collect=''; if($_POST){ 
$collect = login($_POST); if($collect == 'you have successfully login'){ header("location: choose_election.php"); exit;} } 
 ?> 
 
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN" 
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd"> 
<html xmlns="http://www.w3.org/1999/xhtml"> 
 
<head> 
<meta http-equiv="content-type" content="text/html; charset=utf-8" /> 
<title>|| VOTING REGISTRATION SYSTEM||</title> 
<meta name="keywords" content="" /> 
<meta name="description" content="" /> 
<link href="default.css" rel="stylesheet" type="text/css" /> 
<style type="text/css"> 
<!-- 
.style1 { 
 	color: #000000;  	font-weight: bold;  	font-size: 16px; 
} 
.style7 {font-size: 16px; font-weight: bold; } 
.style8 {color: #000000; font-weight: bold; font-size: 18px; } 
.style3 { 	color: #FF0000;  	font-weight: bold; 
} 
--> 
</style> 
</head> 
<body> 
<div id="header"> 
  <table width="200" align="center"> 
    <tr> 
      <td height="212"><img src="images/header1.jpg" alt="" width="770" height="210" /></td> 
    </tr> 
  </table> 
</div> 
<div id="menu"> 
 	<ul> 
 	 	<li> <a href="index.php"> |  Home  |</a></li> 
 	 	<li> 
 	 	  <a href="login.php">|  Voting  |</a></li> 
 	 	<li> 
 	 	  <a href="pres_result.php">|  Result  |</a></li> 
 	 	<li> 
 	 	  <a href="login.php" >|  Login  |</a></li> 
 	</ul> 
</div> 
<div id="content"> 
 	<div id="left"> 
</div> 
  <th height="41" colspan="2" scope="col"><h1><center> 
   </center> 
    
   </h1></th> 
</div> 
</div> 
<div id="footer"> 
  <p class="style8">LOGIN CONSOLE </p> 
 	<table width="371" height="177" border="1" align="center" bgcolor="#99CCFF"> 
      <tr> 
        <td width="361" height="32"><table width="200" align="center" bgcolor="#CCCCCC"> 
            <tr> 
              <td 	height="29"><div 	align="center"><span class="style3">LOGIN CONSOLE </span></div></td> 
            </tr> 
        </table></td> 
      </tr> 
      <tr> 
        <td height="130"><form id="form1" method="post" action=""> 
            <table width="313" align="center"> 
              <tr> 
                <td 	width="96"><span 
class="style3">USERNAME</span></td> 
                <td width="205"><label> 
                  <input type="text" name="txtusername" /> 
                </label></td> 
              </tr> 
              <tr> 
                <td 	height="30"><span 
class="style3">PASSWORD</span></td> 
                <td><input type="password" name="txtelectionid" /></td> 
              </tr> 
              <tr> 
                <td height="41"><label> 
                  <input type="submit" name="Submit" value="Submit" /> 
                </label></td> 
                <td><input type="reset" name="Submit2" value="Reset" 
/></td> 
              </tr> 
            </table> 
        </form></td> 
      </tr> 
    </table> 
 	<p>&nbsp;</p> 
</div> 
</body> 
</html> 
Index page: 
<html xmlns="http://www.w3.org/1999/xhtml"> 
 
<head> 
<meta http-equiv="content-type" content="text/html; charset=utf-8" /> 
<title>|| VOTING SYSTEM ||</title> 
<meta name="keywords" content="" /> 
<meta name="description" content="" /> 
<link href="default.css" rel="stylesheet" type="text/css" /> 
<style type="text/css"> 
<!-- 
.style1 { 
 	color: #000000;  	font-weight: bold;  	font-size: 18px; 
} 
--> 
</style> 
</head> 
<body> 
<div id="header"> 
  <table width="200" align="center"> 
    <tr> 
      <td height="212"><img src="images/header1.jpg" alt="" width="770" height="210" /></td> 
    </tr> 
  </table> 
</div> 
<div id="menu"> 
 	<ul> 
 	 	<li> <a href="index.php"> |  Home  |</a></li> 
 	 	<li> 
 	 	  <a href="choose_election.php">|  Voting  |</a></li> 
 	 	<li> 
 	 	  <a href="registration.php">|  Registration  |</a></li> 
 	 	<li> 
 	 	  <a href="pres_result.php">|  Result  |</a></li> 
 	 	<li> 
 	 	  <a href="login.php" >|  Login  |</a></li> 
 	</ul> 
</div> 
<div id="content"> 
  <table width="200" align="center"> 
      <tr> 
        <td height="170"><img src="images/votingimages.jpg" alt="" width="400" height="400" /></td> 
      </tr> 
    </table> 
 	<p>&nbsp;</p> 
</div> 
</div> 
 
</div> 
</body> 
</html> 
 
 
 
 
 
5.4 OUTPUT  SCREENS AND RESULT ANALYSIS 
LOGIN 
 
