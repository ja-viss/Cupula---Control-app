# Firebase Studio

This is a NextJS starter in Firebase Studio.

To get started, take a look at src/app/page.tsx.

For a detailed explanation of the technologies used in this project, please see the [TECHNOLOGIES.md](./TECHNOLOGIES.md) file.

## Local Development

To run this project on your local machine, follow these steps:

1. **Set Up Environment Variables:**
   - Find the `.env.example` file in the root of the project.
   - Create a copy of this file and rename it to `.env`.
   - Open the new `.env` file and replace the placeholder value for `MONGODB_URI` with your actual MongoDB Atlas connection string.

2. **Install Dependencies:**
   - Open a terminal in the root directory of the project.
   - Run the following command to install all the necessary packages:
     ```bash
     npm install
     ```

3. **Run the Development Server:**
   - After the installation is complete, run the following command to start the application:
     ```bash
     npm run dev
     ```
   - The application should now be running on [http://localhost:9002](http://localhost:9002).
