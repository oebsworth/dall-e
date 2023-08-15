# Project Overview
This project intricately emulates the capabilities of DALL·E, utilizing the MERN stack with Cloudinary and Tailwind CSS. The DALL·E API is harnessed to retrieve and generate images, subsequently saved to Cloudinary along with corresponding prompts and authors stored in MongoDB. The resultant showcase allows users to view, download, and search for images.

## Showcase Page
![image](https://user-images.githubusercontent.com/45319805/223141085-9d143abb-3ad2-4d3d-81ab-01aa4408dea5.png)
The Showcase Page introduces an "Search Posts" input field to facilitate searches based on author names or prompts. The showcase grid visually presents all stored images. Hovering over an image displays the prompt, author, and a download button, permitting users to download images in JPG format. The "Create" button, located at the top-right, navigates users to another page.

![image](https://user-images.githubusercontent.com/45319805/223142655-e90cf81b-7c88-4a17-9150-a9753afc0e34.png)

Upon hovering, an overlay appears showcasing the prompt, author, and download button.

## Generator Page
![image](https://user-images.githubusercontent.com/45319805/223137219-74aedd55-4b1e-41b3-be79-fe3a374658db.png)
The Generator Page encompasses various inputs: "Your name" for the author's name, "Prompt" for generating images, and a "Surprise Me" button for random prompts. The image field displays generated images from the DALL·E API. The "Generate" button triggers image generation. A "Share with the community" button posts author, prompt, and image data to databases for display on the showcase screen.

Through the strategic integration of the MERN stack, Cloudinary, and Tailwind CSS, this project mirrors the core capabilities of DALL·E while providing a user-friendly interface for image generation, display, and sharing.
