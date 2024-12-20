# Deployment Guide: To-Do List Application on DigitalOcean

This guide outlines the steps to deploy the To-Do List Application using DigitalOcean's App Platform.

---

## Steps to Deploy

### 1. Connect to GitHub
- Log in to your [DigitalOcean account](https://www.digitalocean.com/).
- Navigate to the **App Platform** and create a new app.
- Select **GitHub** as the deployment source and connect your GitHub account.
- Choose the repository containing your To-Do List application.

### 2. Configure the Build Environment
- Set the application as a **React App** in the configuration.
- DigitalOcean automatically detects and sets the correct build and run commands:
  - Build command: `npm run build`
  - Start command: `npm start`

### 3. Deploy the App
- Click on **Deploy** to start the process.
- Wait for the deployment to complete. Once done, a public URL will be provided.

### 4. Verify Deployment
- Visit the provided URL to confirm that your application is live and functional.

---

## Additional Notes
- **Branch Selection**: Ensure you select the correct branch (e.g., `main`) for deployment.
- **Environment Variables**: If required, you can set environment variables in the App Platform settings.
- **Auto-deploy**: Enable auto-deploy to redeploy the app automatically whenever new changes are pushed to the repository.

---
## Screenshots  

### Repository Selection  
![Selection of Repository](https://i.ibb.co/RCpBDdH/Screenshot-2024-11-27-115414.png)  
This screen showcases the process of selecting a repository for deployment.  

### Successful Deployment  
![Successfully Deployed](https://i.ibb.co/tMrGb2k/Screenshot-2024-11-27-115830.png)  
The application has been deployed successfully, as indicated in this confirmation screen.  

### Browser View  
![Browser Screen](https://i.ibb.co/YPNw5zQ/Screenshot-2024-11-27-115839.png)  
The deployed application is accessible and fully functional in the browser.  




## Links
- DigitalOcean App Platform: [https://www.digitalocean.com/products/app-platform](https://www.digitalocean.com/products/app-platform)
- React Documentation: [https://reactjs.org/](https://reactjs.org/)
