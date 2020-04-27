#lab4

Link to video of cubes: https://drive.google.com/file/d/16qhlvUwd66I2rSMAgDps3FapTX_0bGX0/view?usp=sharing

Answers to Questions:
a. x = ⌊7u⌋ (the floor of 7u)
b. y = ⌊7 - 7v⌋ (7 minus the floor of 7v)
c. gray

How I made each cube:

Cube 1 (top left): Followed along with the lab by choosing one of the textures from the google drive and creating a cube using that texture.

Cube 2 (top middle): Chose the same texture that I used for cube 1, but this time I was directed to use a normal map to make it have more realistic shading.

Cube 3 (top right): I used a different texture and normal map for the third cube. I used the same methods of creating the cube that I did with cube 2.

Cube 4 (bottom left): This cube was the first one made manually by creating fragment and vertex shaders. I followed what I was told in the lab to execute the product for this cube.

Cube 5 (bottom middle): The 2x2 cube was pretty difficult. I ended up getting a scaled down version of my texture by multiplying the uv position by a float. I found that using 2.0 as the float made me get the leftmost image on step 28 of the lab, so now I had to find how to replicate the image to fit the other 3 quarters. After searching for a while I got a hint in the form of a link to possible functions inside of GLSL, which ended up helping me find the answer. By using mod() I was able to replicate the image to make the 2x2. Using modulus allows the code to access the same scaled down texture multiple times and because of this it is able to replicate the image rather than just displayting it once and having the rest of the cube be distorted.