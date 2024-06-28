# Overview

This project contains different components hosted in various environments. Here's a quick guide to help you remember where each component is hosted and how to deploy them.

## Components and Deployment Instructions

### 1. Main Landing Page
- **Deployment Command**: `npm run deploy`
- **Make sure to check again using**: `git remote -v`
- **Hosting Location**: Local Computer
- **Notes**: The main landing page files are hosted locally. Use the above command to deploy changes to the main landing page.

### 2. LocalStorage
- **Deployment Command**: `vercel --prod`
- **Hosting Location**: Vercel
- **Notes**: The LocalStorage component is hosted on Vercel. Deploy updates using the specified command to push changes to Vercel.

### 3. Khodam
- **Deployment Command**: `vercel --prod`
- **Hosting Location**: Vercel
- **Notes**: The Khodam component is also hosted on Vercel. Use the command mentioned above to deploy updates to Vercel.

### 4. Token-Tracker
- **Deployment Command**: `vercel --prod`
- **Hosting Location**: Vercel
- **Notes**: The Token-Tracker component is hosted on Vercel. Deploy changes with the given command to update the Vercel hosting.

## General Notes
- Ensure you are in the correct directory before running the deployment commands.
- For Vercel deployments, make sure you are logged into your Vercel account using `vercel login` before deploying.
- Check the `package.json` file for any specific scripts related to deployment if adjustments are needed.

## Additional Information
For more detailed instructions on how to work with this project, refer to the documentation or reach out to the project maintainers.

---

Happy Coding!


Last deployed: 2024-06-28 11:51:04 GMT+7