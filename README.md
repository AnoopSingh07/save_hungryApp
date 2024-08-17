
# Savehungry - Food Recipe Website

Savehungry is a full-stack web application designed to provide users with a platform to explore, share, and contribute food recipes. This project was created using the MERN stack and focuses on API integration, responsive design, and user engagement.

## Project Overview

- **Objective**: To accomplish a full stack web application and harness the power of (MongoDB, Express, React, Nodejs) MERN stack.
- **Timeframe**: June 2022 - July 2022
- **Deployment**: The project is live at [Savehungry on Render](https://save-hungry.onrender.com/)

## Features

- **API Integration**: Implemented RESTful APIs to retrieve recipe data, demonstrating an understanding of API integration and data manipulation.
- **User Contributions**: Enabled users to submit their feedback and recipes, enhancing user engagement and contribution within the application.
- **Responsive Design**: Used CSS media queries to create an engaging and user-friendly interface that adheres to responsive web design standards.
- **Version Control**: Git was used to manage version control, ensuring smooth development and deployment processes.

## Project Structure

\`\`\`
.
│   backend.js               # Main server-side script
│   package-lock.json         # Auto-generated file for npm dependencies
│   package.json              # Lists project dependencies and scripts
│   
└───build                     # Contains the production build of the front-end
    │   asset-manifest.json
    │   favicon.png
    │   index.html            # Main HTML file for the front-end
    │   manifest.json
    │   robots.txt
    │
    └───static                # Static assets used by the front-end
        ├───css
        │       main.65cbe7f3.css
        │       main.65cbe7f3.css.map
        │
        ├───js
        │       main.cae6116b.js
        │       main.cae6116b.js.LICENSE.txt
        │       main.cae6116b.js.map
        │
        └───media             # Media assets (images, logos) used in the app
                foodlogo1.9a891f81e384385b5010.png
\`\`\`

## Installation and Setup

To run this project locally:

1. Clone the repository:
   \`\`\`bash
   git clone https://github.com/your-username/savehungry.git
   cd savehungry
   \`\`\`

2. Install dependencies:
   \`\`\`bash
   npm install
   \`\`\`

3. Create a \`.env\` file in the root directory and add your MongoDB URI and other necessary environment variables:
   \`\`\`
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   \`\`\`

4. Start the application:
   \`\`\`bash
   npm start
   \`\`\`

5. Open your browser and navigate to \`http://localhost:3000\`.

## Usage

- Explore a wide range of food recipes.
- Submit your own recipes and provide feedback on existing ones.
- Enjoy a responsive design that works seamlessly on both desktop and mobile devices.

## Technologies Used

- **Front-End**: React JS, HTML, CSS (media queries)
- **Back-End**: Node.js, Express.js
- **Database**: MongoDB
- **Version Control**: Git
- **Deployment**: Render

