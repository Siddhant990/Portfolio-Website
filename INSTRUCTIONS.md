# Portfolio Website Running Instructions

## Requirements

- Node.js (v14 or higher)
- npm (comes with Node.js)

## Setup

1. Clone or download this project to your computer.

2. Open a terminal in the project folder and run the following command:

```bash
npm install
```

This command will install the necessary dependencies.

## Running the Website

### Running in Development Mode

To run the website in development mode (with automatic reload when files change):

```bash
npm run dev
```

### Running in Production Mode

To run the website in production mode:

```bash
npm start
```

After running either command, you can view the website by going to `http://localhost:3000` in your browser.

## Customization

### Adding Image Files

The following image files are required for the website:

1. `images/profile.jpg` or `images/profile.jpeg` - Your profile photo (ideal size: 500x500px)
2. `images/trading.jpg` - Image for the LLM Trading Model project
3. `images/medical.jpg` - Image for the Disease Prediction Model project
4. `images/kubernetes.jpg` - Image for the Kubernetes project
5. `images/docker.jpg` - Image for the Docker project

Note: The website is configured to use profile.jpeg first, and if not found, it will try to use profile.jpg. For project images, if the original images are not found, placeholder images will be displayed.

### Updating Personal Information

To update your personal information, edit the `index.html` file:

- Your name
- Your skills
- Project descriptions
- Contact information
- Social media links

### Customizing Styles

To customize the look and feel of the website, edit the `css/styles.css` file.

## Hosting

This website can be hosted on GitHub Pages, Netlify, Vercel, or any other static website hosting service.

### Hosting on GitHub Pages

1. Create a new repository on GitHub
2. Connect your project to the repository and push it
3. Go to the GitHub repository settings
4. Navigate to the "Pages" section
5. Select "main" branch and root folder as the "Source"
6. Click "Save"

After a few minutes, your website will be live at `https://yourusername.github.io/repository-name`. 