# EXPERIMENT-1  PORTFOLIO-HTML-CSS

## AIM:
To create a portfolio using HTML and CSS.

## ALGORITHM: 
1. Set up the basic structure of your HTML document.

2. Create a CSS file named "styles.css" and link it to your HTML document. This file will contain the CSS rules for styling your portfolio.

3. Design the layout of your portfolio using HTML elements such as < header >, < nav >, < section >, < article >, and < footer >. Use appropriate classes or IDs to style these elements later with CSS.

4. Add a header section to display your name or the title of your portfolio.

5. Add images or media to enhance your portfolio. You can use the  tag to display images and embed videos or other media using appropriate HTML tags.

6. Apply responsive design techniques to ensure your portfolio looks good on different devices and screen sizes. Use CSS media queries to adjust the layout and styling as needed.

7. Apply CSS styling to your portfolio elements by targeting their respective classes or IDs in the "styles.css" file. Customize the colors, fonts, spacing, and other visual properties to match your desired design.

## CODE:

<!DOCTYPE html><br>
<html lang="en"><br>
<head><br>
	<meta charset="UTF-8"><br>
	<meta name="viewport" content="width=device-width, initial-scale=1.0"><br>
	<title>Portfolio Website</title><br>
  </head><br>
<body><br>
	<!--Header(start)--><br>
	<table id="header" border="0" width="100%" cellpadding="0" cellspacing="0" bgcolor="#DC143C"><br>
		<tr><td><br>
				<table border="0" cellpadding="15" cellspacing="0" width="90%" align="center"><br>
					<tr><td><br>
            </td><br>
						<td><br>
							<font face="Verdana" size="5"><br>
								<b>PORTFOLIO</b><br>
							</font></td><br>
						<td width="15%"></td><br>
						<td><br>
							<a href="#home" style="text-decoration:none"><br>
								<font face="Verdana" size="4" color=black><br>
									<b>Home</b><br>
								</font></a></td><br>
						<td><br>
							|<br>
						</td><br>
						<td><br>
							<a href="#about" style="text-decoration:none"><br>
								<font face="Verdana" size="4" color=black><br>
									<b>About</b><br>
								</font></a></td><br>
						<td><br>
							|<br>
						</td><br>
						<td>
							<a href="#skills" style="text-decoration:none">
								<font face="Verdana" size="4" color=black>
									<b>Skills</b>
								</font></a>
						</td>
						<td>
							|
						</td>
						<td>
							<a href="#achievements" style="text-decoration:none">
								<font face="Verdana" size="4" color=black>
									<b>Achievements</b>
								</font></a>
						</td>
						<td>
							|
						</td>
						<td>
							<a href="#projects" style="text-decoration:none">
								<font face="Verdana" size="4" color=black>
									<b>Projects</b>
								</font></a>
						</td>
						<td>
							|
						</td>
						<td>
							<a href="#projects" style="text-decoration:none">
								<font face="Verdana" size="4" color=black>
									<b>Language</b>
								</font></a>
						</td>
						<td>
							|
						</td>
						<td>
							<a href="#contact" style="text-decoration:none">
								<font face="Verdana" size="4" color=black>
									<b>Contact</b>
								</font></a>
						</td>
					</tr></table>
			</td></tr>
	</table>
	<!--Header(end)-->

	<!--Home(start)-->
	<table id="home" border="1" width="100%"
		cellpadding="20" cellspacing="0" bgcolor="black">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="90%" align="center">
					<tr>
						<td align="center" valign="middle">
							<h3>
								<font face="Times New Roman"
									size="6" color="#DC143C">
									Hello I'm Divyashree!
								</font></h3>

							<h2>
								<font face="Verdana" size="6"
									color="#FA8072">
									<!-- Freelance Programmer -->
								</font></h2>
						</td></tr>
				</table></td>
		</tr></table>
	<!--Home(end)-->


	<!--About(start)-->
	<table id="about" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="#DC143C">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center"
							valign="middle" colspan="2">
							<font face="Verdana" size="7"
								color="pink">
								ABOUT ME
							</font>
							<hr color="pink" width="140">
						</td></tr>

					<tr>
						<td width="40%">
							<img src="pexels-kristina-paukshtite-704752.jpg" height="400" width="350">
						</td>

						<td width="60%">
							<font face="Verdana" size="4"
								color="black">
								Thanks for your interest, here
								is a quick story of me.<br>
								I am Divyashree B S.<br>
								I do my work mainly in C-Language,
								C++ and JAVA. C++ and Data Structure
								& Algorithm are my stronger section.
								Besides these I know Web Development,
								LINUX and database as well.
								I ensure you that I do my work effectively and passionately. 
								Thanks again for reading this,
								because of people like you, it
								exists and prospers!<br>
								Cheers,
								<br>
								<b>Divyashree</b>
							</font></td>
					</tr></table>
			</td></tr>
	</table>
	<!--About(end)-->
	
	<!--Skills(start)-->
	<table id="projects" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="black">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center"
							valign="middle" colspan="2">
							<font face="Verdana" size="7"
								color="pink">
							    SKILLS
							</font>
							<hr color="pink" width="120">
						</td></tr>

					<tr>
						<td height="10">
							<font face="Times New Roman"
								size="5" color="#DC143C">
								<ul ><li>
										C
										<a href="#" style="text-decoration:none"></a>
									</li>
									<li>
										C++
										<a href="#" style="text-decoration:none"></a>
									</li>
									<li>
										Java
										<a href="#" style="text-decoration:none"></a>
                  </li>
									<li>
										Web development
										<a href="#" style="text-decoration:none"></a>
									</li>
									<li>
										Python
										<a href="#" style="text-decoration:none"></a>
									</li>
									<li>
										Creative writing
										<a href="#" style="text-decoration:none"></a>
									</li>
								</ul></font>
						</td>
						<td width="45%">
							<img src="download.jpg" height="200" width="200">
							<img src="creatwrite.jpg" height="200" width="200">
						</td></tr>
				</table>
			</td></tr>
	</table>
	<!--Skills(end)-->

	<!--Achievement(start)-->
	<table id="achievements" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="#DC143C">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center" valign="middle">
							<font face="Verdana" size="7" color="pink">
								ACHIEVEMENTS
							</font>
							<hr color="pink" width="190">
						</td></tr>
					<tr><td>
							<font face="Verdana" size="4" color="black">
								<ul><li>
										<b>Intern at Connect Infosystem.</b>
										<ul><li>
												January, 2023 - April, 2023.</li>
											<li>
												Write technical articles
												on programming related topics.</li>
										</ul></li>
									<li>
										<b>Won an Award for Punctuality.</b></li>
									<li>
										<b>Won Second prize in Hackathon.</b>
										<ul><li>
												October,2022.
											</li></ul>
									</li></ul>
							</font></td>
					</tr></table>
			</td></tr>
	</table>
	<!--Achievement(end)-->

	<!--Projects(start)-->
	<table id="projects" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="black">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center"
							valign="middle" colspan="2">
							<font face="Verdana" size="7"
								color="pink">
							    PROJECTS
							</font>
							<hr color="pink" width="120">
						</td></tr>
					<tr>
						<td height="10">
							<font face="Times New Roman"
								size="5" color="#DC143C">
								<ol ><li>
										Chat application
										<a href="#" style="text-decoration:none"></a>
									</li>
									<li>
										Website design
										<a href="#" style="text-decoration:none"></a>
									</li>
									<li>
										Face recognising
										<a href="#" style="text-decoration:none"></a>
									</li>		
								</ol></font>
						</td></tr>
				</table></td>
		</tr></table>
	Projects(end)-->

	<!--Languages(start)-->
	<table id="projects" border="0" width="100%"
	cellpadding="0" cellspacing="0" bgcolor="#DC143C">
	<tr><td>
			<table border="0" cellpadding="15"
				cellspacing="0" width="80%" align="center">
				<tr>
					<td height="180" align="center"
						valign="middle" colspan="2">
						<font face="Verdana" size="7"
							color="pink">
							LANGUAGE
						</font>
						<hr color="pink" width="120">
					</td></tr>
				<tr>
					<td height="10">
						<font face="Times New Roman"
							size="5" color="black">
							<ul ><li>
									English
									<a href="#" style="text-decoration:none"></a>
								</li>
								<li>
									Tamil
									<a href="#" style="text-decoration:none"></a>
								</li>
								<li>
									Telugu
									<a href="#" style="text-decoration:none"></a>
								</li>
								</ul></font>
						</td></tr>
				</table></td>
		</tr></table>
<!--Language(end)-->

	<!--Contact(start)-->
	 <table id="contact" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="black">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="80%" align="center">
					<tr>
						<td height="180" align="center"
							valign="middle" colspan="2">
							<font face="Verdana" size="7"
								color="pink">
								CONTACT
							</font>
							<hr color="pink" width="120">	
						</td></tr>
					<tr>
						<td align="center" valign="top">
							<table border="0" width="50%" cellpadding="15"
								cellspacing="0" align="center" bgcolor="#DC143C">
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="white">
											Name
										</font>
									</td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="black">
											<input type="text" size="40">
										</font></td>
								</tr>
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="white">
											Email
										</font></td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="black">
											<input type="email" size="40">
										</font>
									</td></tr>
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="white">
											Number
										</font></td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<input type="number" size="12">
										</font>
									</td></tr>
								<tr>
									<td width="30%">
										<font face="Verdana" size="4"
											color="white">
											Message
										</font></td>
									<td width="70%">
										<font face="Verdana" size="4"
											color="#ffffff">
											<textarea rows="5"
												cols="37">
											</textarea>
										</font>
									</td></tr>
								<tr>
									<td width="30%"></td>
									<td width="70%">
										<button type="Submit">
											<font face="Verdana"
												size="4" color="black">
												<b>Submit</b>
											</font></button>
									</td></tr>
              </table></td>
					</tr>
					<tr>
						<td colspan="2">
						</td>
					</tr></table>
			</td></tr>
	</table>
	<!--Contact(end)-->

	<!--Footer1(start)-->
	<table id="footer" border="0" width="100%"
		cellpadding="0" cellspacing="0" bgcolor="#DC143C">
		<tr><td>
				<table border="0" cellpadding="15"
					cellspacing="0" width="90%" align="center">
					<tr>
						<td width="13%" valign="top">
							<b>LinkedIn</b>
							<a href="#" style="text-decoration:none"></a>
						</td>
						<td>
							|
						</td>
						<td width="13%" valign="top">
							<b>GitHub</b>
							<a href="#" style="text-decoration:none"></a>
						</td>
						<td>
							|
						</td>
						<td width="13%" valign="top">
							<b>HackerRank</b>
							<a href="#" style="text-decoration:none"></a>
						</td>
						<td>
							|
						</td>
						<td width="13%" valign="top">
							<b>Instagram</b>
							<a href="#" style="text-decoration:none"></a>
						</td>
						<td>
							|
						</td>
						<td width="13%" valign="top">
							<b>Twitter</b>
							<a href="#" style="text-decoration:none"></a>
						</td>
						<td>
							|
						</td>
						<td width="13%" valign="top">
							<b>Facebook</b>
							<a href="#" style="text-decoration:none"></a>
						</td>
						<td>
							|
						</td>
						<td width="13%" valign="top">
							<b>Email</b>
							<a href="#" style="text-decoration:none"></a>
						</td>
						<td>
							|
						</td>
						<td width="13%" valign="top">
							<b>Website</b>
							<a href="#" style="text-decoration:none"></a>
						</td></tr>
				</table></td>
		</tr></table> 
	<!--Footer1(end)-->
</body>
</html> 

## OUTPUT:
<img width="933" alt="port head" src="https://github.com/divvisha/PORTFOLIO-HTML-CSS/assets/127508123/84d1fc29-3210-4621-8b6a-a475750e144c">
<img width="931" alt="port about" src="https://github.com/divvisha/PORTFOLIO-HTML-CSS/assets/127508123/2041a480-2140-42e7-ac85-cecc015aa627">
<img width="932" alt="port skill" src="https://github.com/divvisha/PORTFOLIO-HTML-CSS/assets/127508123/0d302689-b6fb-40b8-abbc-9f1f3b3e0856">
<img width="927" alt="port achvmt" src="https://github.com/divvisha/PORTFOLIO-HTML-CSS/assets/127508123/a8e03005-4170-4310-bfa5-bfb85e7f6e44">
<img width="925" alt="port project" src="https://github.com/divvisha/PORTFOLIO-HTML-CSS/assets/127508123/709cf82e-db58-4535-918f-2721cab683e1">
<img width="927" alt="port lang" src="https://github.com/divvisha/PORTFOLIO-HTML-CSS/assets/127508123/656e7630-30a9-4706-8095-d438325c579b">
<img width="926" alt="port contact" src="https://github.com/divvisha/PORTFOLIO-HTML-CSS/assets/127508123/6123a97a-2505-40ad-b354-4ac610954f1e">
<img width="928" alt="port footer" src="https://github.com/divvisha/PORTFOLIO-HTML-CSS/assets/127508123/25c59d0d-cd19-4633-bd9e-1b3b5892c314">

## RESULT:
Thus, a Portfolio is created successfully using HTML and CSS.
