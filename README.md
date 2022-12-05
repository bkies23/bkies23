- 👋 Hello, my name is Brian Kies from San Antonio, Texas.
- 👀 I am interested in a remote part-time programming job. I graduated Magna Cum Laude 
     from St. Mary's University in San Antonio with a degree in Computer Science
     and a minor in Mathematics.
     
- 🌱 For the last couple of years I have worked with Java NetBeans and MySql. I have designed and coded four programs during this time which are now on this GitHub        site. Two of the programs use Swing pallette components and components are added manually for the other two. I have previously worked with C, C++, C Sharp, Basic,      Pascal, and some COBOL.

     Each project has a .JAR file which can be donwloaded to execute the program. The code for the project is in each repository. 

     Here is a synopsis of the projects with an item or two about the code.
     
     U.S. Flag Histories:
     
     This program looks at the history of the first four U.S. flags along with our present day flag.
     
     I have written a separate class for each flag (BetsyRoss, LewisAndClark, etc.) and each extends a Flag base class. The base class sets width, height, 
     colors, dimensions of stripes and cantons, and has methods for drawing both the stripes and cantons with stars. Only white stripes are drawn as a red                  background is used for the red stripes. The Lewis & Clark flag has its own method for drawing stripes since it was the only flag with more than thirteen stripes.      Each flag has its own method for drawing stars as the star pattern differs for each flag. For the BetsyRossFlag (the only flag with stars in a circle), I used          Math.Pi, Math.Sin, and Math.Cos functions to draw the stars in a circle.
     
     LightBeam: 
     
     This program looks at a math problem I thought of regarding a beam of light emitted from the top of a 10-foot pole. Since the ray of light forms the hypotenuse 
     of a right triangle with surfaces, at what distances does the ray strike a surface as it approaches 90 degrees. In particular, at what distance does it                strike just before it is at 90 degrees and perpendicular to the surface?
     
     I had to experiment with GridBag layout on this one to display panel components proportionately upon resizing of window. It uses Math.toRadians, Math.PI,
     and Math.tan functions to compute the various distances. It also uses ImageIcon to display images (baseball infield, Aususta 16th hole, Indy race track, etc.)          reflecting distances for various angles (75.0, 85.0, 89.0, 89.9, 89.9999. etc.)
     
     Ratios:
     
     This is one of two programs involving aspects of the Covid-19 pandemic. This one looks at the lack of U.S. leadership and analyzes a ratio to show how South            Korea's handling of the crisis led to far less loss of life.
     
     The program displays six sequential pages with each page being a class. Again, as in the Flag program, each extends a Page base class which has a common counter        and location variables for all pages. Three different timers are used: one for the scripts on the screen, one for a JLabel that counts the lives lost, and one for      a picture frame which displays chronological images of the pandemic. I designed this program where it cannot be moved or resized and manually added an X Close          button in the upper right corner. Since the script continually moves across and down the screen, it would have been too difficult to maintain if windows were          repainted. 
     
     The program retrieves data from a MySql database I created which stores pandemic numbers from March 1, 2020 to the present. The data has been taken from the
     New York Times and Washington Post websistes. 
     
     I learned about web scraping for this project and it extracts data from the Worldmeters website to obtain current South Korea case total and current populations        for South Korea and the U.S. This information displays as fractions on the cover page.
     
     I also added buttons to select Page Two through Page Six from the Control section at the bottom of the screen. This way I could check the script for various pages      instead of waiting for the program to circle around from Page One.
     
     Pandemic:
     
     This program uses the MySql database I created to store pandemic numbers since March 1, 2020. It uses ResultSets to retrieve the data and PreparedStatements to
     execute MySql commands on the data. The User can also draw charts by selecting a date range and category (Total Cases, Average Cases, Total Deaths, etc.) If you
     maintain a separate CSV spreadsheet of the data (I use Open Office), you can import the file into the program. You are able to export the table as well. 
     
- 💞️ I currently work for UPS as an Account Manager. I have been employed there for 15 years. I previoulsy worked several years for AT&T. 
- 
-    I am looking forward to hearing back on remote part-time programming postions. 
-    
- 📫 You can reach me by email or by mobile phone:  bkies@ymail.com   210-540-6273

<!---
bkies23/bkies23 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
