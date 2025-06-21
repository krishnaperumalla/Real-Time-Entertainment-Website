# Entertainment Hub


Welcome to Entertainment Hub, your ultimate destination for discovering and exploring movies, web series, anime, and popular franchises. This project is a responsive, real-time entertainment website designed to provide a rich and engaging user experience for cinema lovers.

## ✨ Features

*   **Dynamic Content:** Browse through curated lists of content, including Popular, New Releases, Most Watched, Top Rated, and Coming Soon sections.
*   **Comprehensive Categories:** Dedicated pages for Movies, Web Series, Anime, and Franchises.
*   **Interactive UI:** Smooth carousels and sliders powered by Swiper.js for an engaging browsing experience.
*   **User Profiles:** A functional profile page where users can view and edit their information, change their password, and upload a profile picture. User data is managed using `localStorage`.
*   **Search Functionality:** A real-time search bar to quickly find your favorite entertainment content.
*   **Responsive Design:** A mobile-first design that ensures a seamless experience across desktops, tablets, and smartphones.
*   **About Us Page:** An interactive page detailing the history of the Entertainment Hub, its mission, values, and the team behind it.
*   **Page Preloader:** A loading animation ensures a smooth transition while content loads.

##  Navigate the Hub

The website is composed of several key pages:

*   **`index.html`**: The landing page for new visitors, showcasing the platform's main features.
*   **`home.html`**: The main dashboard for logged-in users, displaying various carousels of entertainment content.
*   **`movies.html`**: A dedicated section for browsing movies.
*   **`web-series.html`**: A section specifically for web and TV series.
*   **`anime.html`**: For all the anime fans, this section is dedicated to anime series and movies.
*   **`franchises.html`**: Explore popular media franchises and their collections.
*   **`profile.html`**: Manage your personal information, credentials, and profile picture.
*   **`aboutus.html`**: Learn more about the Entertainment Hub team and our vision.

## 🛠️ Technologies Used

*   **Frontend:** HTML5, CSS3, JavaScript
*   **Libraries:**
    *   [Swiper.js](https://swiperjs.com/): For creating modern touch sliders and carousels.
    *   [Boxicons](https://boxicons.com/): For high-quality icons.

## 🚀 Getting Started

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/krishnaperumalla/Real-Time-Entertainment-Website.git
    ```

2.  **Navigate to the project directory:**
    ```sh
    cd Real-Time-Entertainment-Website
    ```

3.  **Run with a local server:**
    Because the project uses root-relative paths (e.g., `/css/styles.css`), you need to serve the files from a local web server. Opening the `index.html` file directly in the browser will result in broken links.

    A simple way to do this is by using the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension for Visual Studio Code. Once installed, right-click on `index.html` and select "Open with Live Server".

##  usage

1.  When you first visit the site, you will land on the `index.html` page.
2.  Click the "Get Started" or "SIGN UP" button to navigate to the login/signup flow. (Note: The current implementation simulates login using `localStorage`).
3.  Once "logged in," you will be redirected to `home.html`, the main dashboard.
4.  Use the navigation bar on the left (or bottom on mobile) to switch between Home, Movies, Series, Anime, and Franchises.
5.  Use the search bar at the top to find specific titles.
6.  Click on the user icon to visit your `profile.html` page and manage your account.

