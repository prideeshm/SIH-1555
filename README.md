# Smart India Hackathon Workshop
# Date:30/04/2025
## Register Number: 212223040154
## Name: PRIDEESH M
## Problem Title
SIH 1555: Create a Virtual Herbal Garden that provides an interactive, educational, and immersive experience to users, showcasing the diverse range of medicinal plants used in AYUSH (Ayurveda, Yoga & Naturopathy, Unani, Siddha, and Homeopathy).
## Problem Description
Background: The AYUSH sector relies heavily on medicinal plants and herbs, which form the backbone of traditional healing practices. However, physical gardens that are not accessible to everyone. A Virtual Herbal Garden will bridge this gap by offering a digital platform where users can explore, learn, and understand the significance of various medicinal plants from the comfort of their homes. Description: Participants are tasked with developing a Virtual Herbal Garden that is engaging, informative, and user-friendly. This virtual garden should include: Interactive 3D Models: Realistic 3D models of medicinal plants that users can rotate, zoom, and explore from different angles. Detailed Information: Comprehensive details about each plant, including its botanical name, common names, habitat, medicinal uses, and methods of cultivation. Multimedia Integration: High-quality images, videos, and audio descriptions to enhance the learning experience. Search and Filter Options: Advanced search functionality to easily locate specific plants and filter them based on various criteria like medicinal uses, region, and type. Virtual Tours: Guided virtual tours highlighting specific themes, such as plants for digestive health, immunity, skin care, etc. User Interaction: Features that allow users to bookmark favourite plants, take notes, and share information on social media. Expected Outcome: The expected outcome is a comprehensive Virtual Herbal Garden that serves as a valuable educational tool for students, practitioners, and enthusiasts of the AYUSH sector. This platform should make the knowledge of medicinal plants accessible to a wider audience, promoting awareness and understanding of traditional herbal practices. It should be visually appealing, informative, and interactive, providing users with an immersive experience that combines technology with traditional knowledge.

## Problem Creater's Organization
Ministry of Ayush

## Idea
Title: Virtual Herbal Garden – Experience AYUSH Medicinal Plants Digitally


A web-based platform that provides an interactive and immersive experience of a digital herbal garden showcasing medicinal plants used in AYUSH systems. Users can explore 3D plant models, learn their uses, take guided virtual tours, and interact with multimedia content—making ancient traditional knowledge accessible and engaging for everyone.

## Proposed Solution / Architecture Diagram

![img](https://github.com/user-attachments/assets/2f084a16-09c4-4b69-afb4-b66d17b658dd)

## Use Cases

| Use Case ID | Title                           | Description                                                                 |
|-------------|---------------------------------|-----------------------------------------------------------------------------|
| UC1         | View Plant Information          | Users browse plants and view their medicinal properties and usage.         |
| UC2         | Explore 3D Model                | Users interact with plant models (zoom, rotate, pan).                      |
| UC3         | Guided Tour                     | Users take virtual themed tours (e.g., “Immunity Plants”).                 |
| UC4         | Search & Filter                 | Users filter plants based on disease, region, or AYUSH system.            |
| UC5         | Bookmark/Save Plants            | Users can mark favorite plants and save notes.                            |
| UC6         | Share to Social Media           | Share plant profiles via social platforms.                                |
| UC7         | Multimedia Playback             | Users can view video, listen to audio explanations, or photo galleries.   |
| UC8         | Admin Management (Optional)     | Admins can add/edit plant data, images, and videos.                       |

## Technology Stack

| Layer         | Technology                              |
|---------------|------------------------------------------|
| **Frontend**  | React.js, Three.js or Babylon.js (for 3D), TailwindCSS |
| **Backend**   | Node.js + Express.js                    |
| **Database**  | MongoDB (Atlas) or Firebase Firestore   |
| **Storage**   | AWS S3 / Firebase Storage (for media)   |
| **Authentication (optional)** | Firebase Auth / Auth0 |
| **DevOps/Hosting** | Vercel / Netlify (Frontend), Heroku / Render (Backend) |
| **3D Assets** | Blender (for model creation), Sketchfab (for sourcing) |
| **Others**    | Figma (UI/UX design), Postman (API testing) |

## Dependencies
🔹 Software & Libraries
React.js, Three.js or Babylon.js

Node.js, Express.js

MongoDB driver or Mongoose

AWS SDK (if using S3), or Firebase SDK

React Router, Axios, Framer Motion (for UI/UX)

Multer (for file upload in Node backend)

Cloudinary (optional for image hosting)

🔹 Hardware / External
3D model design software (Blender)

High-quality audio/video equipment (for content creation)

Cloud hosting accounts (AWS, Firebase, etc.)

🔹 Human Resource
Frontend Developer

Backend Developer

3D Modeler / Multimedia Creator

Content Writer (for plant data and AYUSH info)

UI/UX Designer

