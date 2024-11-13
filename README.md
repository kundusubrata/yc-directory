
# Startup Directory Platform
A Next.js 15 platform where entrepreneurs can submit their startup ideas for virtual pitch competitions, browse other pitches, and gain exposure through a clean, minimalistic design for a smooth user experience.

## Features

-   **Dynamic Homepage**: Displays the latest startup ideas using Sanity's Content API.
-   **User Authentication**: Easy login with GitHub.
-   **Submit Startup Ideas**: Title, description, category, and multimedia links (images),content.
-   **Browse and Filter**: Browse submitted ideas and filter by category.
-   **Detailed Pitch View**: View full pitch details, including multimedia.
-   **User Submissions**: View the list of pitches submitted by the user.
-   **View Tracking**: Track the number of views for each pitch.
-   **Search Functionality**: Efficient pitch loading and viewing with search capabilities.
-   **Minimalistic Design**: Clean and essential UI for a great user experience.

## Screenshots

![Blog Homepage](/public/yc-directory.png)

## Prerequisites

Before you begin, ensure you have the following installed on your local machine:

- **git** 
- **Node.js** (v16 or later) 
- **npm** (Node Package Manager)

## Local Setup

1. Clone the Repository

	```bash
	git clone https://github.com/kundusubrata/yc-directory.git
	cd yc-directory
	```
2. Install Dependencies
	```bash
	npm install
	```
3.  Configure Environment Variables
	Create a new file named `.env.local` in the root of your project and add the following content:
	```bash
	AUTH_SECRET="="  
	AUTH_GITHUB_ID=""
	AUTH_GITHUB_SECRET=""
	NEXT_PUBLIC_SANITY_PROJECT_ID=""
	NEXT_PUBLIC_SANITY_DATASET="production"
	NEXT_PUBLIC_SANITY_API_VERSION="vX"
	SANITY_WRITE_TOKEN=""
	```
	Replace the placeholder values with your actual Sanity credentials and add the necessary environment variables. To obtain these values, sign up and create a new project on the [Sanity website](https://www.sanity.io/). For GitHub integration, go to [GitHub Developer Settings](https://github.com/settings/developers) and obtain the required credentials.

4. Run the Development Server
	```bash
	npm run dev
	```
	This will start the development server at `http://localhost:3000`.
5. Access the Application
	Open your browser and navigate to `http://localhost:3000` to see the  application in action.

## Contributing

Feel free to fork this repository, create a branch, and submit pull requests for any improvements or fixes.
