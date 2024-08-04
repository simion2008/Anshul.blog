# Anshul.blog
To make your website accessible to viewers online, you need to host it on a web server. Here are some steps you can follow to do this:

### Step 1: Choose a Hosting Service
There are several options for hosting your static website. Some popular choices include:

1. **GitHub Pages** (Free): Ideal for hosting static websites.
2. **Netlify** (Free & Paid Plans): Easy to use with continuous integration.
3. **Vercel** (Free & Paid Plans): Great for static websites and serverless functions.
4. **Amazon S3** (Paid): Offers scalable storage for hosting static websites.

For simplicity, I'll guide you through hosting your static website using **GitHub Pages**.

### Step 2: Set Up GitHub Pages

1. **Create a GitHub Account:**
   - If you don't already have a GitHub account, sign up at [github.com](https://github.com).

2. **Create a New Repository:**
   - Go to your GitHub dashboard.
   - Click on the `Repositories` tab and then the `New` button.
   - Name your repository (e.g., `anshuls-blog`).
   - Choose `Public` and click `Create repository`.

3. **Upload Your Project Files:**
   - You can upload your files directly through the GitHub web interface:
     - Click on `Add file` > `Upload files`.
     - Drag and drop your project files (all files inside the `anshuls-blog` folder, including subfolders) into the upload area.
     - Commit the changes by adding a commit message and clicking the `Commit changes` button.
   - Alternatively, you can use Git to push your files from your local machine to GitHub:
     ```sh
     git init
     git add .
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin https://github.com/your-username/anshuls-blog.git
     git push -u origin main
     ```

4. **Enable GitHub Pages:**
   - Go to the `Settings` tab of your repository.
   - Scroll down to the `Pages` section on the left sidebar.
   - Under `Source`, select the `main` branch and click `Save`.
   - GitHub will automatically publish your website. The URL will be in the format `https://your-username.github.io/anshuls-blog`.

### Step 3: Share Your Website
Once your site is published, you can share the URL with your viewers. They can now visit your blog at the provided GitHub Pages URL.

### Example URL
If your GitHub username is `anshul`, and your repository is named `anshuls-blog`, your website URL will be:
```
https://anshul.github.io/anshuls-blog
```

### Summary
By following these steps, you can host your static website on GitHub Pages, making it accessible to viewers online. If you need more features, consider exploring other hosting options like Netlify or Vercel, which offer additional functionalities like custom domains, serverless functions, and continuous deployment. If you have any further questions or need more detailed instructions, feel free to ask!
