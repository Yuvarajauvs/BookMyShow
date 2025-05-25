# 🎬 Movie Booking Website (Frontend)

---

## About This Project

This is a simple movie ticket booking website, like BookMyShow. It is made **entirely with HTML, CSS, and JavaScript**. Its goal is to show how an interactive and user-friendly web UI can be created using basic web technologies, without relying on any extra frameworks or build tools.

---

## What It Can Do

* **Show Movies:**
* On visiting the site, it presents a list of all films available.
* Each film displays its **name, genre (category), and a picture (poster)**.

* **Search Movies with Ease:**
    * **Name Search:** You can type the name of a movie. The list will update to show only matching movies.
* **Find by City:** You have the option of choosing a city (e.g., "Bangalore" or "Chennai"). The website will thereafter show only movies showing in this city.
    * **Find by Type:** You also have the option of choosing a movie type (like Drama or Thriller) to show just those movies.

* **Book Tickets (Website-Side Only):**
* **Film Details:** Tap on a movie to get more information about it, including its **plot, cost, and showtimes available**.
    * **Choose Theater & Showtime:** Select a theater and showtime you like.
* **Select Your Seats:** There is a seating map available. You can choose your preferred seats. The website shows you which seats are available, which seats you have chosen, and the seated seats.
* **Confirm Booking:** After you select seats, you'll be shown a recap of your booking, such as the film, your chosen seats, and the price. **(Note: This is a frontend-only confirmation. No money is transferred, and no real booking or reservation is made.)**

* **User Login/Register (Website-Side Only):**
    * You can locate forms to **register an account and login**.
* These files process input, but they **do not store your data anywhere**. This site doesn't have a backend (server and database) to handle actual user accounts or secure authentication.

---

## Tools Used

* **HTML:** To create the structure and content of the web pages.
* **CSS:** To style the website and make it visually appealing on different screen sizes (it utilizes **Tailwind CSS** for effective styling).
* **JavaScript:** For adding all interactive aspects, dynamic updating of content, search/filtering logic, showing details, and client-side form processing.

---

## Project Status

This project is **solely a frontend application** developed using conventional web technologies. It vividly showcases UI/UX design and client-side logic without needing any server-side elements or frameworks.

**Important Note:**
* There is **no backend** (server or database) for this project.
* This implies that there are no real user accounts, no data storage of movie information, and no actual booking or payment handling. Everything works directly in the browser of the user.

---

## Setting Up (For Your Machine)

If you'd like to test this site on your own machine:

1.  **Clone the project:**
    ```bash
git clone [https://github.com/Yuvarajauvs/MovieBookingRepoName.git](https://github.com/Yuvarajauvs/MovieBookingRepoName.git) # Important: Change to the actual link to *this particular Movie Booking project's* GitHub repository
    cd MovieBookingRepoName # Move into the project folder
    ```
    *(If this particular project is a subfolder of a greater `Portfolio` repository, you would clone the `Portfolio` repo, and then move into this project's particular folder after cloning.)*

2.  **Open in Browser:**
    * Just find the `index.html` file in the project directory on your machine.
    * **Double-click `index.html`** to load it in your web browser.
    * **No Node.js, `npm install`, or `npm run dev` required** for this project since it's just HTML, CSS, and JavaScript.

---

## How to Put It Online (Deploy)

This project is very easy to host online with **GitHub Pages** since it is purely static HTML, CSS, and JavaScript files.

1.  **Place your primary `index.html` file at the root of your project directory.**
2.  **Push the project files into your GitHub repository's `main` branch:**
    ```bash
    git add .
    git commit -m "Initial commit of Movie Booking project"
```
git push origin main
```    
*(If you'd rather deploy from a `gh-pages` branch, you would push to `gh-pages` rather than `main` after committing.)*

3.  **Set up GitHub Pages:**
    * Navigate to your repository on GitHub in your web browser.
    * Click on the **Settings** tab.
* In the left sidebar, click on **Pages**.
    * Under "Build and deployment", choose **Branch** for the "Source".
    * Select `main` (or `gh-pages` if you pushed to that branch) as the branch to deploy from.
    * Ensure the folder is set to `/ (root)`.
    * Click **Save**.
* Your site should then be accessible live at a URL such as `https://Yuvarajauvs.github.io/YourMovieBookingRepoName/` (put the actual name of *this* particular GitHub repository in place of `YourMovieBookingRepoName`). 

---
