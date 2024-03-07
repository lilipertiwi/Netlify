
## How to Set Up Netlify

**1. Visit the Netlify Website:**
   Go to the official Netlify website at https://www.netlify.com/.
   ![Netlify Homepage](https://i.ibb.co/568GzND/netlify-home.jpg "Netlify Homepage")

**2. Click on "Sign Up" and select sign up with email:**
   You will be directed to a sign-up page where you need to provide your email address and create a password. Alternatively, some services allow you to sign up using your GitHub, GitLab, or Bitbucket account.
   ![Netlify Signup Page](https://i.ibb.co/w4hdfwx/signup-email.jpg "Netlify Signup Page")

**3. Verification:**
   After submitting your information, you may need to verify your email address. Check your email for a verification message from Netlify and follow the instructions to complete the verification process.
   ![Verify](https://i.ibb.co/f9zJ6kN/image.png "Email Verification")

**4. Login:**
   Once your account is verified, you can log in to your new Netlify account using the email and password you provided during the sign-up process.
   ![Login](https://i.ibb.co/Wtc0NWG/image.png "Login with registered email")

---

## Connect Netlify to Github Project

**Prerequisites:**
* GitHub Account:
Ensure you have a GitHub account, and you've already created a repository for your project.

* Netlify Account:
If you don't have a Netlify account, sign up following the instructions in the previous response.

**Steps:**
1. Log in to Netlify
Go to https://www.netlify.com/ and log in to your Netlify account.

2. Navigate to Sites page, click on Add new Site and select on "Import an existing project"
![Import an existing project](https://i.ibb.co/kK5DSxL/image.png)

3. Click on "Deploy with Github":
On the Netlify dashboard, click on the "New site from Git" button. If you haven't connected Netlify to your GitHub account before, you'll need to authorize the integration. Follow the prompts to authorize Netlify.
![Select Github](https://i.ibb.co/yQqZMwP/image.png)

4. Select Your Repository:
After authorization, Netlify will present a list of your GitHub repositories. Choose the repository that you want to connect to Netlify and deploy.
![Select Repository](https://i.ibb.co/4Svthgn/image.png)

5. Configure Your Settings:
   * Site name
   Input site name you want to give to your website.
   * Branch to deploy
   Choose the branch you want Netlify to deploy

6. Click on "Deploy [Your Site Name]" button
   After configuring your settings, click on the "Deploy Site" button. Netlify will start the deployment process.

7. Website will be deployed and can be accessed with the site name
   ![Deployed](https://i.ibb.co/dcY7PYZ/image.png)

---

## Github Deployment
1. Create new branch `git checkout -b [branch name]`
2. Add new updates `git add .`
   Check the status that changes ready to be committed with `git status`
   ![alt text](/sources/images/image.png)
3. Commit changes with `git commit -m "[comment]"`
4. Push `git push --set-upstream main branch-test`
5. Create and merge Pull Request
   * Open Github to check new Push
   ![New Push](https://i.ibb.co/XDZnnKW/image.png)
   * Create Pull Request
   ![Create PR](https://i.ibb.co/YRR8Mms/image.png)
   * Merge Pull Request
   ![Merge PR](https://i.ibb.co/9p7xqMZ/image.png)
6. Netlify will automatically detect any PR merged to deploy branch (main) and will deploy the new updates.

---

## Connect Custom Domain and DNS
**Prerequisites:**
* Domain name which can be purchase from a domain registrar (e.g. Niagahoster)

**Steps:**
1. Go to Domain page
   From Netlify Dashboard, go to Domains page, then click on "Add or register domain" or access through this link [register domain on netlify](https://app.netlify.com/teams/lilipertiwi/dns/setup/)
2. Choose Domain
   Input domain name that you already purchased from a domain provider, verify, then click Add domain.
   ![Add domain](https://i.ibb.co/nw1CbMh/image.png)
3. Add DNS records
   Click Continue
4. Activate Netlify DNS
   On the last step, you will be given DNS Netlify.
   ![DNS Netlify](https://i.ibb.co/88Xr2r1/image.png)
   Add DNS servers to your domain
   ![Activate DNS](https://i.ibb.co/PTwK04W/image.png)
5. Your DNS will be activated and your site will be hosted in Netlify in 24 hours.
