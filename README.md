
# IH2 Website Deployment (GitHub Pages)

## Steps to Deploy
1. Create a public GitHub repository (e.g., `ih2-site`)
2. Upload all files from this ZIP into the repository root.
3. In your GitHub repo, go to **Settings > Pages**.
4. Under "Source", select the **main branch** and `/ (root)` folder.
5. Save — your site will be live at: `https://yourusername.github.io/ih2-site/`

## To use your custom domain (ih2.online)
1. Go to your domain provider (e.g., Namecheap or Exabytes)
2. Create a CNAME record pointing `www` to `yourusername.github.io`
3. In the GitHub repo, create a file called `CNAME` (no extension) with one line:
   ```
   www.ih2.online
   ```

4. Wait for DNS to propagate (~15 minutes to a few hours)
