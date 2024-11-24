# Blog Website

This project is a simple blog website created to explore the world's wonders and hidden gems. Users can read blog posts about various destinations and experiences. The website is built using HTML and CSS.

## Files

### `index.html`

The `index.html` file contains the main structure of the blog website. This file includes the title, a brief description, and four blog posts. Each blog post consists of a heading, a paragraph, a list of activities or tips, and images. The key elements of this HTML file are:

- **Header**: Displays the page title and a brief description.
- **Main Content**: Contains four separate blog posts, each covering a different topic.
- **Images**: Visual elements to enhance the content of each blog post.
- **Links**: External links to additional resources for users to explore more information.

The main purpose of the HTML file is to structure the content of the page, with visual styling and layout provided by the linked CSS file.

### `style.css`

The `style.css` file is responsible for styling the elements in the `index.html`. This CSS file enhances the appearance of the website and includes various style rules. Some key features of the CSS file include:

- **General Styling (body)**: Sets the background color and text color for the page.
  - `background-color: #E6E9AF`: The background color is set to a soft yellow-green shade.
  - `color: #22177A`: The text color is set to a deep shade of purple.
  
- **Header Styling (header)**: Defines the background color, text alignment, and padding for the header section.
  - `background-color: #605EA1`: The header background color is a medium shade of purple.
  - `text-align: center`: Centers the text within the header.
  
- **Blog Post Styling**: Each blog post is styled with a unique background color, rounded corners, padding, and shadow to make it visually distinct.
  - `background-color: #8EA3A6`: The background color of the blog posts is set to a soft teal.
  - `border-radius: 10px`: Rounds the corners of the blog post containers.
  - `box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1)`: Adds a subtle shadow effect to each blog post.
  
- **Image Styling**: Images are styled to appear in a responsive, flexible layout with spacing between them.
  - `max-width: 25%`: Ensures that images do not exceed 25% of the container width.
  - `border-radius: 10px`: Rounds the corners of the images.
  
- **Links Styling**: Links are styled to stand out with bold text and a color change on hover.
  - `color: #605EA1`: Links are colored with the same shade of purple used in the header.
  - `text-decoration: none`: Removes the underline from the links by default.
  - `a:hover`: Adds an underline to links when the user hovers over them.

- **Responsive Design**: Media queries are used to make the website responsive on smaller screens, adjusting the layout of blog posts and images for mobile devices.
  - `@media (max-width: 768px)`: Reduces the width of blog posts and adjusts image sizes for better readability on smaller screens.
