# Ex.04 Images as Hyperlinks
## DATE 15/04/2024
## AIM
  Insert five different images ( 2 on Crops and 2 on Machines and 1 on Fertilizer required ). 
  Skip two lines between each image. Each image should have a title. 
  Display the images with a border of size 2, a width of 200, and a height of 200, 
  it should be linked to a search engine of your choice and when each image is clicked, 
  the respective search engine should be opened in a new window.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the required images using ```<img>``` tag.

### STEP-3
  Set the image border size as 2, image width as 200 and height as 200.

### STEP-4
  Use the ```<a>``` anchor tag to link the corresponding search engines.  

### STEP-5
  Give double line spacing between the images using ```<br>``` tags.
  
### STEP-6
  Open the file in a browser and verify the output.
  
## CODE
```
<html
     <head>
        <title>RAJAPRIYA Ex04 Agri..</title>
    </head>
        <body bgcolor="#d5eed3">
<h1 style ="font-family:elephant;color:#43086b;text-decoration-line:underline ;
 text-align:center;";>Ex.04 Images as Hyperlinks</h1>

<h2 style="font-family:elephant;color:rgb(230, 37, 117);">seed</h2>
<a href=" https://www.bing.com/ck/a?!&&p=b18fe348f5b020f4JmltdHM9MTcxMzEzOT
IwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0wNGIxNmRjYjY2NzUmaW5
zaWQ9NTUwOA&ptn=3&ver=2&hsh=3&fclid=0e3410ad-6c19-67e2-36ba-04b16dc
b6675&psq=sugarcane&u=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3
dpa2kvU3VnYXJjYW5l&ntb=1">
<img src="c:\Users\Raj Infotech\Downloads\seed.jpg" width="200"  border size="2"
 height="200"></a><br>

<h2 style="font-family:elephant;color:rgb(17, 140, 58);">
Seedling</h2>
<A HREF="https://www.bing.com/ck/a?!&&p=11e2244b4d4d4304JmltdHM9MTcx
MzEzOTIwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0wNGIxNmRjYjY2Nz
UmaW5zaWQ9NTU2MA&ptn=3&ver=2&hsh=3&fclid=0e3410ad-6c19-67e2-36ba-04
b16dcb6675&psq=SESAME&u=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3J
nL3dpa2kvU2VzYW1l&ntb=1">
 <IMG SRC="c:\Users\Raj Infotech\Downloads\seedling.jpg"  width="200" border size="2"
 height="200"></A><br><br>

<h2 style="font-family:elephant;color:#dc6013;">
plant</h2>
<a href="https://www.bing.com/ck/a?!&&p=47a0648a3de2f96aJm
ltdHM9MTcxMzEzOTIwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItM
zZiYS0wNGIxNmRjYjY2NzUmaW5zaWQ9NTU0MA&ptn=3&ver=2&hsh=
3&fclid=0e3410ad-6c19-67e2-36ba-04b16dcb6675&psq=harvester&u
=a1aHR0cHM6Ly9lbi53aWtpcGVkaWEub3JnL3dpa2kvQ29tYmluZV9oYXJ2ZXN0ZXI&ntb=1">
<img src="c:\Users\Raj Infotech\Downloads\plant.jpg" width="200"  border size="2"
height="200"><br><br></a>

<h2 style="font-family:elephant;color:#aa1a1a;">
Tree</h2>
<a href="https://www.bing.com/ck/a?!&&p=620fc089
18dd8928JmltdHM9MTcxMzEzOTIwMCZpZ3VpZD0wZTM0MTBhZC02YzE5L
TY3ZTItMzZiYS0wNGIxNmRjYjY2NzUmaW5zaWQ9NTQ5NA&ptn=3&ver=2&
hsh=3&fclid=0e3410ad-6c19-67e2-36ba-04b16dcb6675&psq=tractor&
u=a1aHR0cHM6Ly93d3cuY3JvcHNyZXZpZXcuY29tL3doYXQtYXJlLXRyYWN0b3J
zLXVzZWQtZm9yLw&ntb=1">
    <img src="c:\Users\Raj Infotech\Downloads\tree.jpg" width="200"  border size="2"
 height="200"><br></a>

<h2 style="font-family:elephant;color:rgb(174, 23, 201);">
orchard</h2> 
<a href="https://www.bing.com/ck/a?!&&p=f6c7e2f4552af867Jmltd
HM9MTcxMzEzOTIwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0
wNGIxNmRjYjY2NzUmaW5zaWQ9NTMwNQ&ptn=3&ver=2&hsh=3&fclid=0e341
0ad-6c19-67e2-36ba-04b16dcb6675&psq=fertilizer&u=a1aHR0cHM6Ly9i
eWp1cy5jb20vYmlvbG9neS9mZXJ0aWxpemVycy8&ntb=1">
 <img src="c:\Users\Raj Infotech\Downloads\orchard.jpg"width="200" height="200"
 border size="2"><br></a>

<h2 style="font-family:elephant;color:#107218;">
fertilizer</h2> 
<a href="https://www.bing.com/ck/a?!&&p=d489aac698460702Jmltd
HM9MTcxMzIyNTYwMCZpZ3VpZD0wZTM0MTBhZC02YzE5LTY3ZTItMzZiYS0
wNGIxNmRjYjY2NzUmaW5zaWQ9NTI1Ng&ptn=3&ver=2&hsh=3&fclid=0e34
10ad-6c19-67e2-36ba-04b16dcb6675&psq=organic+fertilizer+for+
plants&u=a1aHR0cHM6Ly93d3cuZXBpY2dhcmRlbmluZy5jb20vb3JnYW5pYy
1mZXJ0aWxpemVycy8&ntb=1">
  <img src="c:\Users\Raj Infotech\Downloads\fertilizer.jpg"width="200" height="200"
border size="2"><br><br></a>

</body>
    
</html>
```


## OUTPUT
![Screenshot (7)](https://github.com/rajapriya1111/Ex04/assets/166101070/4391c990-5564-402e-804c-ad5187ca6a8d)
![Screenshot (8)](https://github.com/rajapriya1111/Ex04/assets/166101070/f20c120f-fba4-4a01-bd04-8a12c086734c)
![Screenshot (9)](https://github.com/rajapriya1111/Ex04/assets/166101070/e390864a-2c92-4476-95f5-cca45692b02b)




## RESULT
 Images as hyperlinks is implemented successfully.
