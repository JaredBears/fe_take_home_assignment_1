# Take Home Assignment

## Thought Process

For this project, I initially considered using React and Material UI, as this is the framework I am most familiar with using for front end assignments.  However, for this particular assignment I determined this may be a bit overkill, and determined that Bootstrap would be more than sufficient for the needs of the assignment.

Upon reviewing the provided screenshot, I determined the page should be split up into the following sections:

### Sidebar

In both of the screenshots, it appears the Sidebar takes up approximately 25% of the page, so I set it up as col-4 in bootstrap.

I used the color-picker tool in paint to match the requested color scheme.

None of the provided images matched the Logout icon in the screenshot, so I copied the `Nav-logout icon-solid.svg` file and modified it as `Nav-logout icon-hollow.svg`

### Course Grid

It appears the Course Grid takes up the remaining 75% of the page in both screenshots.

### Course Cards

## Notes

At the moment, this is only a mockup of a front-end application designed to appear as close as possible to the provided imagery, primarily with HTML and CSS.  It will need substantial modifications to be incorporated into any full-stack application.

## Running the Application

To ensure a smooth start to your project, we've set up some initial steps. Following these steps will help you get up and running with the provided HTML page and the Node.js HTTP server, which you'll use to serve your page.

### Step 1: Clone this repository

You can either download the repository as a ZIP file or clone it using Git. 

### Step 2: Review the Provided HTML Page

You’ll begin your assignment with a basic HTML page. This page is configured to be the starting point of your project.

### Step 3: Setting Up Node.js

If you haven't already, you will need to install Node.js. This can be done by visiting the [Node.js website](https://nodejs.org/) and downloading the installer for your operating system.

### Step 4: Serving the HTML Page with Node.js

After installing Node.js, follow these steps to serve the HTML page using the Node.js environment:

1. **Install Dependencies:**
   - Open your terminal or command prompt.
   - Navigate to the directory where your project is located.
   - Run the command **`npm install`**.
   - This will install **`http-server`** and any other necessary dependencies as defined in the **`package.json`**.
2. **Start the Server:**
   - In the same directory, run the command **`npm start`**.
   - This will start a local web server.
3. **Accessing Your Page:**
   - Open a web browser and go to **`http://localhost:8080`**.
   - You should see the provided HTML page being served.