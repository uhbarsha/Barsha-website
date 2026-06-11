# How to Get Your Website Live
## Step-by-step guide — takes about 30 minutes

---

## STEP 1 — Create a GitHub account (5 min)

1. Go to **github.com**
2. Click **Sign up**
3. Enter your email, create a password, choose a username (e.g. `ummeyhanibarsha`)
4. Verify your email

---

## STEP 2 — Upload your site files to GitHub (10 min)

1. Log in to GitHub
2. Click the **+** icon (top right) → **New repository**
3. Name it: `barsha-portfolio`
4. Set it to **Public**
5. Check **"Add a README file"**
6. Click **Create repository**
7. On your new repository page, click **"uploading an existing file"**
8. Drag and drop **all the files and folders** from the zip you downloaded:
   - `index.html`
   - `netlify.toml`
   - `admin/` folder (with both files inside)
   - `_data/` folder (with all .json files inside)
   - `images/` folder (empty is fine)
9. Click **Commit changes**

---

## STEP 3 — Create a Netlify account and connect GitHub (10 min)

1. Go to **netlify.com**
2. Click **Sign up** → choose **Sign up with GitHub** (easiest)
3. Authorize Netlify to access your GitHub
4. On the Netlify dashboard, click **"Add new site"** → **"Import an existing project"**
5. Click **GitHub**
6. Find and select your `barsha-portfolio` repository
7. Leave all settings as default
8. Click **Deploy site**
9. Wait ~1 minute — Netlify will give you a URL like `sparkly-name-abc123.netlify.app`

---

## STEP 4 — Enable the CMS login (5 min)

1. In Netlify, go to **Site configuration** → **Identity**
2. Click **Enable Identity**
3. Scroll down to **Registration** → set to **Invite only**
4. Go to **Site configuration** → **Identity** → **Services** → **Git Gateway**
5. Click **Enable Git Gateway**
6. Now go to **Identity** tab (top menu) → click **Invite users**
7. Enter your own email address → Send invite
8. Check your email → click the invite link → set your password

---

## STEP 5 — Log in to your admin panel

1. Go to: `https://your-site-name.netlify.app/admin`
2. Log in with your email and password
3. You will see the full editor with tabs: **Home, Research, Teaching, Creative**
4. Edit anything → click **Save** → your live website updates within 1 minute

---

## Your secret admin URL
`https://your-site-name.netlify.app/admin`

Keep this private — only people you invite can log in.

---

## To add your own domain name (optional, ~$12/year)
1. Buy a domain at **namecheap.com** (e.g. `ummeyhanibarsha.com`)
2. In Netlify → Domain management → Add custom domain
3. Follow Netlify's instructions to point your domain to their servers

