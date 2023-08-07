# Shoe_Page
## Hosted Link : https://mayankkatheriya.github.io/Shoe_Page/
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/e120351b-9810-4954-bce3-fe25c7f72a01)
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/dd1221e0-0599-43a3-be9e-712c32584138)

In HTML pert first we make a div named as "container"\
and in CSS part we defines some of the properies of the "container"\
position: relative;: The element is positioned relative to its normal position.\
z-index: 1;: The stacking order of the element. Elements with a higher z-index value will be displayed above elements with a lower value.\
width: 100%;: The element's width is set to 100% of its parent's width.\
height: 100vh;: The element's height is set to 100% of the viewport height (the visible area of the browser window).\
background-color: rgb(211,211,211);: The background color of the element is set to a shade of gray using the RGB color model.\
overflow: hidden;: Any content that exceeds the element's dimensions will be hidden.\
so our container is ready now\
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/2153e80d-2977-4413-a06c-da0014c6acfe)

<br>

![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/25c9e379-d589-48bf-a0b4-aa9ddb87ffbb)
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/09540f02-dfc5-49cc-8f6e-14993b957581)

now we have to make another div inside our "container" and named it as "main"\
in CSS part define its property\
width: 85%; - The element's width is set to 85% of its parent's width.\
height: 75%; - The element's height is set to 75% of its parent's height.\
margin: auto; - The element is horizontally centered within its parent.\
margin-top: 7.5%; - The element is pushed down from the top by 7.5% of its parent's height.\
box-shadow: 0px 0px 10px black; - The element will have a black box shadow with a blur radius of 10px, creating a shadow effect.\
background: linear-gradient(to right, #8a2387, #e94057, #f27121); - The element's background is set to a linear gradient that transitions from #8a2387 to #e94057 to #f27121 from left to right\
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/0502e087-a58b-4a86-96be-2029921c5dd5)

<br>

![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/d5731a25-7b9d-44bf-9c69-8596e7b0e6b1)
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/9d11c914-1612-4db5-bfec-64ae99d81f56)

now in our "main" box we have our content of web page\
we first we give a nested div of class "text" and defines its property in CSS\
width: 43%; - The element's width is set to 43% of its parent's width.\
height: 100%; - The element's height is set to 100% of its parent's height.\
font-family: 'Times New Roman', Times, serif; - The text inside the element will be displayed using the 'Times New Roman' font family. If not available, it will try 'Times' and then a generic serif font.\
color: white; - The text color inside the element will be set to white.\
padding: 2.5%; - The content inside the element will have a padding of 2.5% of its own width on all sides.\
display: inline-block; - The element will be displayed as an inline-block, allowing other elements to be displayed on the same line if they fit.\
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/0378681c-b1f9-401c-8e63-7e5ef43099f4)

<br>

![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/eddba46a-5461-4fc7-ad1e-750772229dd0)
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/fb4d3818-f677-43f6-87b3-a29b1d440dfe)

after giving properties of "text" we didn't see any changes to our web pages\
this is because we didn't any content to our box\
so lets give content to the "text" div.\
give 'h2' and 'p' tag to the text container as shown in the code and give its CSS property\
font-size: 18px; - The text inside the element will have a font size of 18 pixels.\
margin: 30px 0; - The element will have a margin of 30 pixels at the top and bottom, and no margin on the left and right sides.\
margin-top: 50px; - The element's top margin will be overwritten to 50 pixels, changing the top margin from the previous value (30 pixels) to 50 pixels. The other margins (bottom, left, and right) will remain unchanged at 30 pixels.\
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/45ef69e8-3101-4880-a099-0c1e284093a2)

<br>

![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/7b114a31-3755-4e31-b152-09aa59870183)
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/e5317fe5-43f5-42b0-859b-07d7e35f20c5)

now we have to add one image and give it a hover effect\
in "image" class selector\
display: inline-block; - The elements with the class "image" will be displayed as inline blocks, allowing other elements to be displayed on the same line if they fit.\
position: absolute; - The elements with the class "image" will be taken out of the normal flow of the document and positioned based on their nearest positioned ancestor.\
right: 0; - The elements with the class "image" will be positioned with their right edge aligned to the right edge of their nearest positioned ancestor.\
top: 10%; - The elements with the class "image" will be positioned with their top edge 10% down from the top edge of their nearest positioned ancestor.\
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/b7e4e59e-f73f-452d-9bc8-e2cb95d1e7d2)

for hover effect of the image we used psuedo class "img:hover"\
width: 900px; - When hovering over an "img" element, its width will be set to 900 pixels.\
height: 550px; - When hovering over an "img" element, its height will be set to 550 pixels.\
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/f679bcf9-f87d-4e85-b95f-dc8ed1448362)

<br>

![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/de2fbeaf-dbc0-4316-942c-19409ec8708c)
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/20cc830d-3983-421f-be7c-3e6d10366596)

Now for the last part we have to give background effect\
so make a another nested div of class "backgrounf" and give its CSS properties\
background: linear-gradient(to right, #b92b27, #1565c0); - The background of the element will have a linear gradient that transitions from #b92b27 to #1565c0 from left to right.\
width: 100%; - The element's width will be set to 100% of its parent's width.\
height: 100%; - The element's height will be set to 100% of its parent's height.\
transform: skewY(10deg); - The element will be skewed by 10 degrees along the Y-axis, creating a slanted effect.\
position: absolute; - The element will be taken out of the normal flow of the document and positioned based on its nearest positioned ancestor.\
top: 0; - The element will be positioned with its top edge aligned to the top edge of its nearest positioned ancestor.\
right: 0; - The element will be positioned with its right edge aligned to the right edge of its nearest positioned ancestor.\
z-index: -1; - The element will be positioned behind other elements with higher z-index values.\
box-shadow: 0px 0px 10px black; - The element will have a black box shadow with a blur radius of 10px, creating a shadow effect.\
Please note that the transform: skewY(10deg); property will slant the element along the Y-axis, and the z-index: -1; property will position it behind other elements on the page. The box shadow will add a shadow effect to the element.\
![image](https://github.com/Mayankkatheriya/Shoe_Page/assets/128832286/b943748c-b941-4243-a57a-905ccdb5b7e7)

## our final web page is ready now
# Thankyou ☺

