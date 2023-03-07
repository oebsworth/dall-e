# Introduction
This project is a DALL·E clone that was made using the MERN stack with Cloudinary and Tailwind css. I have used the DALL·E API to fetch and generate images to be saved to cloudinary with the prompt and author being saved to mongoDB. You can then view the images stored in cloudinary with the information for that post and if you want to you can download the images from the showcase screen. The showcase screen also has a search function that you can use to find images using the prompt or author name.

# Showcase Page
![image](https://user-images.githubusercontent.com/45319805/223141085-9d143abb-3ad2-4d3d-81ab-01aa4408dea5.png)
The "Search Posts" input field is used to search through the showcase using the author name or prompt.
Next you can see the showcase grid where all of the images stored in the memory are shown.
Finally at the top right you can see the "Create" button which will take you to the other page.

![image](https://user-images.githubusercontent.com/45319805/223142655-e90cf81b-7c88-4a17-9150-a9753afc0e34.png)

This image shows the prompt, author and download button. 
This shows up when you hover over the image.
The download button will download the image in the .jpg format.

# Generator Page
![image](https://user-images.githubusercontent.com/45319805/223137219-74aedd55-4b1e-41b3-be79-fe3a374658db.png)
The "Your name" input field allows you to input an author name that will be linked to your image.
The "Prompt" input field allows you to enter the prompt that you would like to generate an image for.
There is also a "Surprise Me" button that allows you to generate a random prompt.
Below this there is an image field that will show your image when it has finished generating using the DALL·E API.
Underneath this there is a "Generate" button that you can use to generate the image.
Finally there is a "Share with the community" button that you can use to post the author, prompt and image to the necessary databases for use on the showcase screen.
