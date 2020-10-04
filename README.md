# project
Project Tracking and Documentation

## Developer Onboarding
**Currently only Seth admins, teachers, and parents can contribute to the Seth website**

### Prerequisite 1: Access to Seth website
- Go to https://seth-institute.org in browser
- Click on `Log In` on upper right
- Click on `New to this site? Sign Up`
- Sign up with email account registered with Seth (the one that has access to shared folder in Google Drive, default @svca account, use `Sign up with Google` if it is a Google account)
- Wait for approval and on gaining access login
- Update your name and photo through https://seth-institute.org/account/settings, click on `Edit` on the profile card on the top left
- Subscibe to the blog through same url https://seth-institute.org/account/settings, Blog Subscription > Subscribe

### Prerequisite 2: Create and have existing Github account
Go to https://github.com in browser and Sign up if creating new

### Prerequisite 3: Set up Node in local environment
Go to https://nodejs.org/en/ in browser and follow steps to download & install

### Gain access to Seth private repo and Wix
- Email Huang Qi and David Tu new developer Github username
- David will add new developer Github account to Seth
- Qi will grant new developer edit access to Wix

### Tour Wix
- Log in to https://wix.com and click on `Seth Education` tile
- Click on `Site Actions > Edit Site`
- Explore but do not make edits until rest of the steps in developer onboarding is complete

### Clone code for Seth Education website locally
- Create base folder for Seth on computer
- `npx create-corvid-app wix-app https://seth-institute.org` to create project linked with Wix and clone source code: it will ask you to login (use your seth-institute website login account)
- `cd wix-app`
- `git init`
- `git remote add origin git@github.com:seth-institute/wix-app.git` if you have ssh set up with Github (https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/connecting-to-github-with-ssh) or `git remote add origin https://github.com/seth-institute/wix-app.git` otherwise
- `git fetch`
- `git reset --hard origin/master`: now you have the latest code from Github repo
