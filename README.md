# Leveraging BabelFish Protocol for Custom Domains

The BabelFish protocol allows you to connect custom domains to any location on the internet or blockchain.

The BabelFish dashboard offers tools for hosting and managing web content directly on the blockchain. However, it's important to inform the community about the different hosting options available.

GitHub Pages is an excellent example of a free platform where you can host websites and easily connect them to a custom domain using the BabelFish protocol.


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

This commit triggers the publishing process. The URL (e.g., `https://your-user-name.github.io/hello-world`) will be live within minutes after the commit. Check it in a browser.

*Url of this repository [https://deep-thought-computer.github.io/hello-world](https://deep-thought-computer.github.io/hello-world/), 

### 4. Normal Workflow
To fully edit your repository, clone it locally on your computer with `git clone https://github.com/your-user-name/hello-world.git`. 

Edit files (e.g., `index.html`), then run `git add .`, `git commit -m "Update"`, and `git push origin main`. 

Each push will automatically update your site on GitHub Pages at the URL (e.g., `https://your-user-name.github.io/hello-world`).

## Connecting Your GitHub Pages Site to On-chain Domain With BabelFish

Now that your site is hosted on GitHub Pages, you can connect it to your own domain. There are two ways to do this:

1. **Link as mirror URL)**: In your BabelFish panel, set the GitHub Pages URL (e.g., `https://your-user-name.github.io/hello-world`) as a "mirror URL". This makes your custom domain a direct reflection of the GitHub Pages site.

2. **Link with IP address**: In your GitHub repository, go to "Settings" > "Pages", and under "Custom domain", enter your domain (e.g., `yourdomain.qom`). Then, in your BabelFish panel, specify the IP addresses of GitHub's servers to point your domain to GitHub Pages.
