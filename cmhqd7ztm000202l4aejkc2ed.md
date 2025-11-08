---
title: "How to Host Your Website on GitHub Pages"
seoTitle: "Host Your Website on GitHub Pages"
seoDescription: "Learn how to easily host your static website on GitHub Pages for free with this step-by-step guide. Perfect for portfolios, blogs, and more!"
datePublished: Sat Nov 08 2025 14:13:58 GMT+0000 (Coordinated Universal Time)
cuid: cmhqd7ztm000202l4aejkc2ed
slug: how-to-host-your-website-on-github-pages
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1762611164205/74195a70-120e-4d68-ab7b-1918d58307bb.jpeg
tags: github, deployment

---

If you’ve ever built a small website — maybe your portfolio, a simple project, or a personal blog — you’ve probably wondered how to put it online **without paying for hosting**.

That’s where **GitHub Pages** comes in.

It’s one of the easiest and most reliable ways to host your static website (HTML, CSS, JS) completely **for free**, with zero ads and free SSL.  
I’ve used it for years to share demos, side projects, and even documentation pages — and it just works.

Let’s go step-by-step.

---

## 🧰 What You’ll Need

Before you start, make sure you have:

* ✅ A **GitHub account** (create one at [github.com](https://github.com))
    
* ✅ Your website folder (with `index.html`, `css`, `js`, etc.)
    
* ✅ A bit of patience for the first setup 😉
    

---

## 🪜 Step-by-Step: Deploying Your Website on GitHub Pages

### **Step 1: Create a New Repository**

1. Go to [https://github.com/new](https://github.com/new)
    
2. Enter a repository name — for example: `my-portfolio`
    
3. Make it **Public**
    
4. Check **“Add a README file”** (optional but helpful)
    
5. Click **Create Repository**
    

Done ✅ — you now have a new GitHub repo ready to host your site.

---

### **Step 2: Upload Your Website Files**

You’ve got two easy options here:

#### Option 1: Upload via Browser

1. Inside your repo, click **“Add file” → “Upload files”**
    
2. Drag and drop your entire website folder  
    (make sure `index.html` is in the root)
    
3. Scroll down and click **Commit changes**
    

#### Option 2: Upload via Git (for developers)

If you use Git locally:

```python
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/my-portfolio.git
git push -u origin main
```

That’s it — your files are now in GitHub.

---

### **Step 3: Enable GitHub Pages**

Now comes the fun part 🎉

1. In your repo, click on **Settings** (top right)
    
2. Scroll down to the **Pages** section (or search “Pages”)
    
3. Under **“Source”**, select the branch — usually `main`
    
4. Choose `/ (root)` folder
    
5. Click **Save**
    

Wait 30–60 seconds ⏳  
GitHub will automatically build and publish your site.

---

### **Step 4: Your Site Is Live!**

You’ll see a green message like:

> “Your site is live at https://yourusername.github.io/my-portfolio/”

Visit that link — congratulations, your site is officially online! 🎊

You can share this link with anyone, and it will load your HTML site instantly.

---

### **Step 5: Update Anytime**

Need to make changes later?  
Just update your files and push the changes to GitHub again.

If you uploaded manually, re-upload and commit.  
If you use Git, just:

```python
git add .
git commit -m "Updated homepage text"
git push
```

GitHub Pages will automatically refresh your live website — no redeploy needed.

---

## ⚙️ Optional: Custom Domain Setup

Want your own domain like `mywebsite.com` instead of `github.io`?  
You can do that too:

1. Buy a domain from any provider (e.g., Namecheap, GoDaddy)
    
2. In your repo, create a file named `CNAME`
    
3. Inside it, write your custom domain:
    
    ```python
    mywebsite.com
    ```
    
4. Go to your domain DNS settings  
    → Add a CNAME record pointing to:
    
    ```python
    yourusername.github.io
    ```
    

Within a few hours, your custom domain will point to your GitHub Pages site.

---

## 💡 Pro Tips

* GitHub Pages gives you **free HTTPS** — no setup needed
    
* You can even host Jekyll-based blogs or documentation sites
    
* Works perfectly for small projects, resumes, or client demos
    
* Keep your repo public; private repos require GitHub Pro plan
    

---

## 🏁 Conclusion

GitHub Pages is hands down one of the most reliable and beginner-friendly ways to host a website for free.  
It’s fast, secure, and completely ad-free — and you can connect your own domain if you want to look professional.

If you’ve never deployed a site before, this is the perfect place to start.  
No servers, no headaches — just push your code and go live.

Now go ahead, try it yourself, and see your project shine online 🚀