#lab3

Link to Video: https://drive.google.com/file/d/1n2SrXnw7bw-0VoX9wKnUg1qPHD5F1qeV/view?usp=sharing



Explanations of Cubes: 

First Cube: Based off of the cube that we were given at the top of the lab. I changed the color to be more like clay but made the specular green for the assignment requirements.

Second Cube: I viewed the source code of the material examples from the Three.js website and found one that I really liked. I used meshBasicMaterial, changed the color, and made it so that it was transparent. 

Third Cube: The interpolated cube that the lab walks us through creating by using our own shaders rather than the built in ones. I decided to change the colors to something that I liked more.

Fourth Cube: After 4 hours of trying to get the solution below to work I decided to try something else so I took the fragment shader that we were given and rather than using mix to create interpolation I wanted to see what putting vUv.z straight into a value looked like. It looked cool so I did the same by putting vUv.x into the red value, vUv.y into the green, and vUv.z into the red value, which created a super cool looking cube.

Original attempt: (For the fragment shader I looked up interesting effects that can be applied and decided on taking the absolute value of a sin wave to go from blue to black over and over again.)