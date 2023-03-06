# Introduction
This project is a DALL·E clone. It uses the MERN stack with cloudinary and tailwind css. I have used the DALL·E API to fetch and generate images to be saved to cloudinary with the prompt and author being saved to mongoDB. You can then view the images stored in cloudinary with the information for that post and if you want to you can download the images from the showcase screen. The showcase screen also has a search function that you can use to find images using the prompt or author name.

# Generating an image
![image](https://user-images.githubusercontent.com/45319805/223137219-74aedd55-4b1e-41b3-be79-fe3a374658db.png)
# 'Your name'
The "Your name" input field allows you to input an author name that will be linked to your image.
### 'Prompt'
The "Prompt" input field allows you to enter the prompt that you would like to generate an image for.
### 'Surprise Me'
There is also a "Surprise Me" button that allows you to generate a random prompt.
### 'Image'
Below this there is an image field that will show your image when it has finished generating using the DALL·E API.
### 'Generate'
Underneath this there is a "Generate" button that you can use to generate the image.
### 'Share with the community'
Finally there is a "Share with the community" button that you can use to post the author, prompt and image to the necessary databases for use on the showcase screen.
