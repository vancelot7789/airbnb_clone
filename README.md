# Airbnb Clone 
This project is a clone of Airbnb, built with React, TypeScript, Next.js, Tailwind CSS, and MongoDB. <br>
See [Demo](https://book-clone-demo-1ihsalpx7-vancelot7789.vercel.app/).
![airbnb](https://github.com/vancelot7789/airbnb_clone/assets/31930515/c358ef32-9c1f-4cac-bc20-24a9a84fa5f4)


## Tools
![text](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![text](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![text](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![text](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)
![text](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

## Key Features
- Credential authentication / Google authentication / Github authentication
- Booking & Reservation system
- Creation and deletion of properties
- Both residents and property owners can use the location selection and map feature.
- Filtering of desired properties based on date, property category, number of rooms, and number of bathrooms

## Installation
First, install packages
```bash
npm install
```

## Environment Variables

You will need to configure your own environment variables for the application to function correctly. This can be done in a `.env` file in the root of your project directory.
Below is the format your `.env` file should follow. The keys are already provided, you just need to copy and paste and then fill in with your own IDs and secrets.

```bash
DATABASE_URL=                # Your MongoDB URL

NEXTAUTH_SECRET="NEXTAUTH_SECRET"  # Your NextAuth Secret

GITHUB_ID=                   # Your GitHub ID
GITHUB_SECRET=               # Your GitHub Secret

GOOGLE_CLIENT_ID=            # Your Google Client ID
GOOGLE_CLIENT_SECRET=        # Your Google Client Secret

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=   # Your Public variable from Cloudinary

```
Please replace the comments (# Your ...) with your actual values.

## Obtaining the IDs and Secrets

Follow the instructions below to obtain your own IDs and secrets.

### GitHub

1. Go to your GitHub settings.
2. Navigate to "Developer settings".
3. Click on "OAuth Apps" and then "New OAuth App".
4. Fill in the form and you'll get your GitHub ID and Secret.

### Google

1. Go to the [Google Developer Console](https://console.developers.google.com/).
2. Create a new project.
3. Navigate to "Credentials".
4. Click on "Create Credentials" and choose "OAuth client ID".
5. Fill in the form and you'll get your Google Client ID and Secret.

Remember, replace the placeholders in your `.env` file with the IDs and Secrets you obtained from these steps. 


## Run the project

```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.


## Deployment

Before deploying the project, you can run:
```bash
npm run build
```
This will help you ensure everything is functioning correctly.
### Vercel
You can easily deploy it on Vercel on [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js. Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
