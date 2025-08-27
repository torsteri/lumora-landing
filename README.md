
# Deploy Lumora Landing Page to Azure Static Web Apps

## Steps
1. Create a GitHub repository and upload these files.
2. Go to Azure Portal → Create a Static Web App.
3. Link your GitHub repo and select `main` branch.
4. Set build details:
   - **App location**: `/`
   - **API location**: *(leave blank)*
   - **Output location**: `/`
5. Click **Review + Create**.

Azure will deploy and give you a live subdomain.
You can later map a custom domain (e.g. lumora.com).
