# Putting the new site online

Everything here is free. It takes about 30 minutes, once.
You create the accounts yourself; I can guide you through each screen.

## 1. GitHub: where the site's files live
1. Create a free account at github.com.
2. Click **New repository**, name it `raulvisuals` and make it **Public** or **Private**.
3. Upload every file and folder from this project (drag them into the repository page).
4. Tell me your GitHub username. I'll put it in `admin/config.yml`.

## 2. Netlify: shows the site to the world
1. Create a free account at netlify.com and sign up **with GitHub**.
2. **Add new site → Import an existing project → GitHub →** pick `raulvisuals`.
3. Leave the build settings empty and click **Deploy**. You'll get a temporary link like `something.netlify.app`.

## 3. Let the admin page log you in
1. On GitHub: **Settings → Developer settings → OAuth Apps → New OAuth App**
   - Homepage URL: `https://raulvisuals.net`
   - Authorization callback URL: `https://api.netlify.com/auth/done`
2. Copy the **Client ID**, then generate and copy a **Client secret**.
3. On Netlify, open your site's settings, find **OAuth** (under Access / Security),
   choose **Install provider → GitHub** and paste both values.

## 4. Point raulvisuals.net to the new site
1. On Netlify: **Domain management → Add a domain → raulvisuals.net**.
2. Netlify shows the DNS settings to use. Enter them wherever your domain is managed
   (in Canva if you bought it there, or at your domain company).
3. Wait up to a few hours. HTTPS turns on automatically.
   Keep the Canva site until the new one shows up.

## Every day after that
1. Go to **raulvisuals.net/admin** and click **Login with GitHub**.
2. Add, edit, reorder or delete projects, change text, and upload photos and clips.
3. Click **Publish**. The live site updates in about a minute.

**Tips**
- Upload full-length videos to YouTube and paste the link. Upload only short hover clips and photos directly.
- Hover clips: 2–3 seconds, muted, 720p, under ~2 MB (DaVinci: H.264, low bitrate).
- Thumbnails: 16:9 JPGs around 1600 px wide.
