# Dawson Carmouche Personal Website

This is a personal website for Dawson Carmouche, built with HTML, CSS, and JavaScript. It features information about his passions, mission, work (tech and social media), and a blog.

## Project Structure

- `index.html`: The main HTML file for the website.
- `style.css`: Contains all the CSS styling for the website.
- `script.js`: (Currently empty) For any future JavaScript functionality.

## Getting Started

To view this website locally, simply open the `index.html` file in your web browser.

## Deployment to GitHub Pages

This guide assumes you have `git` installed and are familiar with basic Git commands.

1.  **Initialize Git Repository (if not already done):**

    If you haven't already initialized a Git repository in your project directory, navigate to your `DawsonCarmouche Website` directory in your terminal and run:

    ```bash
    git init
    ```

2.  **Add Your GitHub Repository as Remote:**

    Set your GitHub repository as the remote origin. Replace `YOUR_USERNAME` with your GitHub username:

    ```bash
    git remote add origin https://github.com/TheRevolutionists/DawsonCarmouche.git
    ```

    If you already have a remote named `origin`, you might need to update it:

    ```bash
    git remote set-url origin https://github.com/TheRevolutionists/DawsonCarmouche.git
    ```

3.  **Commit Your Files:**

    Add all your website files to the staging area and commit them:

    ```bash
    git add .
    git commit -m "Initial commit: Personal website setup"
    ```

4.  **Push to GitHub:**

    Push your committed changes to the `main` branch (or `master` if that's your default) on GitHub:

    ```bash
    git push -u origin main
    ```

5.  **Enable GitHub Pages:**

    - Go to your repository on GitHub (`https://github.com/TheRevolutionists/DawsonCarmouche`).
    - Click on the **Settings** tab.
    - In the left sidebar, click on **Pages**.
    - Under "Build and deployment", for "Source", select `Deploy from a branch`.
    - For "Branch", select the `main` (or `master`) branch and choose the `/ (root)` folder.
    - Click **Save**.

    Your website should now be live at `https://therevolutionists.github.io/DawsonCarmouche/` (it might take a few minutes for the changes to propagate). 