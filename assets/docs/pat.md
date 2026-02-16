# Generating a PAT token
Step-by-Step: Generating a PAT (Classic)

1. Open Settings: Click your profile photo in the top-right corner of GitHub and select Settings.

    Developer Settings: Scroll all the way down the left sidebar and click Developer settings.

    Personal Access Tokens: Click on Personal access tokens and then select Tokens (classic).

   Note: While GitHub offers "Fine-grained tokens," the "Classic" version is usually more compatible with simple IDE integrations like this one.

2. Generate New Token: Click the Generate new token dropdown and select Generate new token (classic).

    Configure Scopes:

   Note: Give it a name (e.g., "Keycap Editor").

   Expiration: Set it to 30, 60, or 90 days (or "No expiration" if you are careful).

   Select Scopes: For this application to save files, you must check the repo box. This gives the token power to read and write to your repositories.

3. Copy the Token: Click Generate token at the bottom.

   ⚠️ Important: Copy the token immediately. GitHub will never show it to you again once you leave the page.
   
5. Adding to Keycap

   Click the **Push to github** button

   Enter your token and click connect

   Click the button another time and create a repo on your github page

   Enter the repo name : It will push it to github
   
