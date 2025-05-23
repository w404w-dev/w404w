# Steps to Fork this GitHub Repository and Set Up GitHub Pages

### 1. Fork the Repository
In order to can use this repository as base for your own page, you need to "Fork" it... it's like copy/paste it on your own account.

1. Click on "Fork" (top-right corner).
2. Review the details panel, you can change the name optionally (you can edit it any time in the future)
3. Click on Fork to complete.

*Ensure the new repository is **public** (select "Public" when creating if the option is present) to use GitHub Pages for free.

### 2. Configure GitHub Pages
1. In your fork, navigate to "Settings" > "Pages". 
2. Under "Source", select the `main` branch and the root folder `/`.
3. Click "Save".

*A commit is needed to start publishing (next step).

### 3. Make an Initial Commit
To generate your site for the first time, create a simple commit. 

1. From the GitHub web interface, go to your repository
2. Open `README.md`, click the pencil icon (edit)
3. Add a word or character (e.g., type "Hello")
4. Click "Commit changes".

This commit triggers the publishing process.

### 4. Normal Workflow
To fully edit your repository, clone it locally on your computer with `git clone https://github.com/your-user-name/hello-world.git`. 

Edit files (e.g., `index.html`), then run `git add .`, `git commit -m "Update"`, and `git push origin main`. 

Each push will automatically update your site on GitHub Pages at the URL (e.g., `https://your-user-name.github.io/hello-world`).

## Notes

- The URL (e.g., `https://your-user-name.github.io/hello-world`) will be live within minutes after the commit. Check it in a browser.
