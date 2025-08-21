One Question Life Test
"One Question Life Test" is a simple web application that allows people to share their biggest life regrets. Users write an answer to a single question and can anonymously read the shared responses of other users. The project works without the need for a server-side API, operating directly on the client-side with Firebase Firestore, Google's cloud-based database solution.

Features
Anonymous Answer Sharing: Users can submit their answers without revealing their identity.

Real-Time Data Access: New answers become instantly visible to other users.

Answer Search: Provides the ability to search through shared answers based on keywords.

Modern Interface: Features a clean and modern design built with Tailwind CSS.

Technologies Used
HTML5: The structure of the page.

CSS3 (Tailwind CSS): The design and styling of the application.

JavaScript (ES6): The logic and interactivity of the application.

Firebase Firestore: The serverless database used to store and synchronize answers in real-time.

Setup and Deployment
Setting up the project is straightforward as it does not require a back-end server.

Clone the Repository:

git clone https://github.com/yourusername/your-project-name.git
cd your-project-name

Add the File:

Replace the index.html file in your repository with the latest version of the code for this project. The final version includes the Firebase integration.

This prevents the fetch errors you were encountering and allows the project to run directly in the browser.

Deploy with GitHub Pages:

On your GitHub repository, go to Settings > Pages.

Under Source, select Deploy from a branch and choose main (or whichever branch you are using).

Save your changes.

GitHub will start to build and publish your site within a few minutes. You can find your site's URL on the Pages settings page.
