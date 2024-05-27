The issue with the images not showing up in your GitHub `README.md` file is likely due to the paths to the images. GitHub's Markdown rendering requires the image paths to be correct and relative to the repository.

Here are a few things to check:

1. **Correct Paths**: Ensure that the image paths are correct relative to the location of the `README.md` file. For example, if the `README.md` file is in the root directory and the images are in a folder called `website img`, the paths should be relative to the root.

2. **URL Encoding**: Spaces in file or directory names should be URL encoded as `%20`. However, it's often better to avoid spaces in filenames and directories. Consider renaming the directory to avoid spaces, e.g., `website-img`.

3. **Case Sensitivity**: Ensure that the filenames and paths match the exact case (uppercase/lowercase) as GitHub is case-sensitive.

Here's an updated version of your `README.md` with these considerations:

````markdown
# React Training Project

## Instructions

1. **Clone the repository and create a new branch**  
   Create a new branch and name it `[surname-react-training01]`  
   (example: `doe-react-training01`)

   ```sh
   git clone [repository-url]
   cd [repository-directory]
   git checkout -b [surname-react-training01]
   ```
````

2. **Install the node_modules**  
   Run the following command to install the necessary dependencies:

   ```sh
   npm install
   ```

3. **Create the mockup website**  
   Refer to the provided link for the mockup and create the following pages:

   - Home Page
   - About Page
   - Services Page
   - Contact Page

4. **Use any CSS library**  
   You may use any CSS library such as Tailwind, Bootstrap, or Pure CSS.

5. **Implement responsive breakpoints**  
   Ensure the best breakpoints for each screen size (Desktop, Mobile, Tablet).

6. **Make it responsive**  
   Ensure the website is responsive and looks good on all screen sizes.

## Notes

- Pay close attention to the design and make sure it matches the mockup as closely as possible.
- Focus on creating a clean, user-friendly interface.
- Test the responsiveness thoroughly on various devices & browsers.
- For the assets, you may inspect the respective images directly in the mockup link provided below.

  [Website Mockup](https://preview.themeforest.net/item/metize-landing-page-wordpress-theme/full_screen_preview/52251111)

## Getting Started

1. Clone the repository and navigate to the project directory.
2. Create a new branch with your surname.
3. Install the project dependencies.
4. Start developing the pages as per the instructions.

Good luck, and happy coding!
