OfferBridge on Netlify

Edit links without code
- Update all offers in one file: offers.json
- Or use a visual editor at /admin after enabling Netlify Identity + Git Gateway

Deploy
1. Create a new GitHub repo. Upload all files.
2. In Netlify, New site from Git. Select the repo.
3. Build command: none. Publish directory: .
4. Open your site.

Edit via file
- Open offers.json in GitHub. Click Edit. Change brandName, brandInitials, tagline, and offers.
- Commit. Netlify redeploys.

Edit via visual admin
1. Netlify dashboard → Identity → Enable Identity.
2. Identity → Enable Git Gateway.
3. Invite your email. Confirm.
4. Visit /admin on your site. Log in. Edit “Offers and Settings”. Publish.

Amazon links
- Use your tag parameter, for example:
  https://www.amazon.com/dp/B0XXXXXXX?tag=YOUR_TAG-20
