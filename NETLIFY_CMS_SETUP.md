# Netlify CMS Setup Guide for PPEsoc

## What is Netlify CMS?

Netlify CMS is a free admin panel where non-technical users can edit website content without touching code. Users simply log in and see forms to update events, blog posts, team members, and more.

## Step-by-Step Deployment Instructions

### Step 1: Deploy to Netlify (5 minutes)

1. Go to **[netlify.com](https://netlify.com)** and click "Sign Up"
2. Choose "GitHub" as your sign-up method
3. Authorize Netlify to access your GitHub account
4. Click "New site from Git"
5. Select **unswppesociety/unsw-ppe-society** repository
6. Leave settings as default and click "Deploy site"
7. Wait 2-3 minutes for deployment to complete

**Your site will be live at:** `https://[random-name].netlify.app`

To set a custom domain (optional):
- Go to Site Settings → Domain Management → Add Custom Domain
- Enter your domain (e.g., `ppesoc.unsw.edu.au`)
- Follow DNS setup instructions

### Step 2: Enable Netlify Identity (2 minutes)

1. In Netlify dashboard, go to **Site Settings**
2. Click **Identity** in the left menu
3. Click **Enable Identity**
4. Under "Registration preferences" select **Invite only**
5. Under "External providers" click **Enable Google** (optional)

### Step 3: Invite Team Members (1 minute per person)

1. Go to **Identity** tab in Netlify
2. Click **Invite users**
3. Enter team member's email address
4. They'll receive an email with a setup link
5. They click the link and set a password

**That's it!** Team members can now access `/admin` to edit content.

---

## How to Use the CMS

### For Team Members:

1. **Go to:** `yoursite.com/admin` (e.g., `https://ppesoc.netlify.app/admin`)
2. **Log in** with the email they were invited with
3. **Select a collection** from the left menu:
   - **Events** - Add/edit society events
   - **Blog Posts** - Write and publish articles
   - **Executive Team** - Update team member info
   - **Pages** - Edit main website content
   - **Job Opportunities** - Post internships/roles

4. **Click "New [Collection Name]"** to create new content
5. **Fill out the form** - it's just like Google Forms!
6. **Click "Publish"** when done

Changes go live to the website immediately! 🎉

---

## What Each Team Member Can Edit

### Events Director
- Add/edit/delete events
- Change dates, times, locations
- Add registration links
- Upload event flyers

### Publications Director
- Write and publish blog posts
- Upload featured images
- Tag posts (Philosophy, Politics, Economics, etc.)

### Academics/Careers Director
- Add job opportunities/internships
- Update course resources links
- Edit page descriptions

### President/Secretary
- Update team member information
- Edit contact details
- Update social media links

---

## Troubleshooting

**"I see a blank page at /admin"**
- Wait 5 minutes for Netlify to rebuild
- Clear browser cache (Cmd+Shift+Delete)
- Try a different browser

**"I can't log in"**
- Check your spam folder for invite email
- Make sure you're using the email you were invited with
- Reset password in the login form

**"My changes aren't showing"**
- Click "Publish" (not just "Save")
- Wait 30 seconds for rebuild
- Hard refresh your browser (Cmd+Shift+R on Mac)

**"I can't access the admin panel"**
- You need to be invited first
- Contact the site admin to send you an invite
- Check your email (including spam) for the Netlify invitation

---

## Security Notes

- Only team members with invites can access the admin panel
- All changes are tracked in GitHub history
- You can always revert changes if needed
- Passwords are securely stored by Netlify

---

## Next Steps

1. **Deploy to Netlify** using steps above
2. **Invite your executive team** to Netlify Identity
3. **Test the CMS** by adding a test event
4. **Train your team** to use the forms
5. **Enjoy easy content management!** 🚀

---

## Support

If you need help:
1. Check the [Netlify CMS documentation](https://www.netlifycms.org/docs/)
2. Contact the site creator/developer
3. Netlify support: support@netlify.com
