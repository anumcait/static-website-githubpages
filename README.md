# Static Website Deployment with GitHub Pages

This README provides detailed instructions for deploying a static website using GitHub Pages. Follow the steps below to create and customize your static website.

## Project Structure

```
static-website
├── index.html
├── .github
│   └── workflows
│       └── github-pages.yml
└── README.md
```

## Step 1: Create the `index.html` File

1. Create a file named `index.html` in the `static-website` directory.
2. Add the HTML structure for your website. Here is a simple example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Static Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to My Static Website</h1>
    </header>
    <main>
        <p>This is a simple static website hosted on GitHub Pages.</p>
    </main>
    <footer>
        <p>&copy; 2023 My Static Website</p>
    </footer>
</body>
</html>
```

## Step 2: Push to a New GitHub Repository

1. Create a new repository on GitHub.
2. Initialize a local Git repository in your `static-website` directory:

```bash
git init
```

3. Add your files to the repository:

```bash
git add .
```

4. Commit your changes:

```bash
git commit -m "Initial commit"
```

5. Link your local repository to the GitHub repository:

```bash
git remote add origin https://github.com/USERNAME/REPOSITORY_NAME.git
```

6. Push your changes to GitHub:

```bash
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click on the "Settings" tab.
3. Scroll down to the "Pages" section.
4. Under "Source", select the `main` branch and the root folder.
5. Click "Save".

## Step 4: Access Your Live Website

After a few minutes, your website will be available at:

```
https://USERNAME.github.io/REPOSITORY_NAME/
```

Replace `USERNAME` with your GitHub username and `REPOSITORY_NAME` with the name of your repository.

## Step 5: Customize Your Site

1. To customize your website, you can add CSS styles. Create a `styles.css` file in the `static-website` directory and link it in your `index.html`.
2. Modify the HTML structure and content in `index.html` as needed.

## Conclusion

You have successfully deployed a static website using GitHub Pages! Feel free to explore and customize your site further.