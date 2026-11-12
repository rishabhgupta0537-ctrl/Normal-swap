SKILLSWAP — NETLIFY WEBSITE

FILES
- index.html: complete responsive SkillSwap landing page and join form
- success.html: confirmation page shown after form submission
- README.txt: setup notes

DEPLOY
1. Extract this ZIP.
2. In Netlify, choose Add new site > Deploy manually.
3. Upload the extracted folder containing index.html and success.html.
4. This is plain HTML/CSS. Leave Build command empty. Publish directory: .
5. After the first successful deploy, open Netlify site dashboard:
   Forms > find "skillswap-join" > Form notifications > Add notification
   > Email notification, then enter the recipient email address.
6. Submit one test entry on the live website and verify it appears under Forms
   and that the email notification arrives.

IMPORTANT
- The join form uses Netlify Forms. It will not send email merely because an
  email address is written in the HTML. You must configure the notification
  in Netlify using the recipient email address provided by the site owner.
- Do not put passwords, secret API keys, or private information in this site.
- This is a simple public landing page + enquiry form, not a full member
  platform. There is no account login, member database, chat, or skill matching.
- Netlify plan limits and form availability may apply. Check your Netlify
  dashboard for current usage and settings.
