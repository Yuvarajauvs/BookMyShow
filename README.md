#  🎬  Movie Booking Website (Frontend)

---

## About This Project

This is a basic movie ticket booking website, similar to BookMyShow. It is limited to the user level (frontend). It demonstrates what you can do with simple web technology to create a good-looking and user-friendly website.

---

## What It Can Do

* **Show Movies:**
* When you visit the website, it displays all the movies.
* Every film has its **title, category (genre), and an image (poster)**.

* **Search for Movies Easily:**
* **Search by Name:** You can search for a movie's name to search it. The list will be modified to display only matching films.
* **Find by City:** You can select a city (such as "Bangalore" or "Chennai"). The site will then display only movies running in that city.
* **Find by Type:** You may also select a movie type (such as Drama or Thriller) to display only those movies.

* **Book Tickets (Just on the Website):**
* **Movie Information:** Click on a movie to view more about it, such as its **story, price, and when it's playing**.
* **Select Theater & Showtime:** Select a movie theater and a showtime you prefer.
* **Choose Your Seats:** You will be able to see the map of seats. You are able to choose your seats. The site indicates which seats are available, which ones you selected, and which seats are occupied.
* **Confirm Booking:** Once you choose seats, you'll have a summary of your booking with the movie, your seats, and cost. **(Important: This is only on the website. No actual money or actual booking occurs here.)**

* **User Login/Register (Only on the Website):**
* You can notice forms to **create an account and log in**.
* These types check what you input, but they **don't store your info anywhere**. This site doesn't have a backend (server and database) to manage user accounts.

---

## Tools Used

* **HTML:** To create the layout of the web pages.
* **CSS:** To get the site to look nice and display properly on various screen sizes (uses **Tailwind CSS** to speed up styling).
* **JavaScript:** Used to enable the site to become interactive, such as searching, filtering, displaying details, and form handling.
* **React:** JavaScript framework for constructing the components of the website (parts) in an understandable and efficient manner.
* **Vite:** An efficient tool that assists in constructing the website quickly for development purposes and when it is deployed.

---

## Project Status

This site is **solely a frontend project**. It's wonderful to demonstrate how to create user interfaces and process actions within the website itself.

**Important Note:**
* There is **no backend** (server or database) for this project.
* That implies no actual user accounts, no storing movie information, and no actual booking or payment. All takes place on your computer.

---

## How to Set It Up (For Your Computer)

If you wish to host this website on your own machine:

1. **Clone the project:**
```bash
git clone [https://github.com/Yuvarajauvs/Portfolio.git](https://github.com/Yuvarajauvs/Portfolio.git) # Use your actual project link
cd Portfolio
```

2. **Install what it requires:**
```bash
npm install
```

3. **Host the website:**
```bash
npm run dev
```
This will normally open the website in your browser at `http://localhost:5173`.

---

## How to Put It Online (Deploy)

This project is deployed online with **GitHub Pages**.

### Special Scripts

In the `package.json` file, there are special scripts to assist with putting the website online:
```json
"homepage": "[https://Yuvarajauvs.github.io/Portfoliot](https://Yuvarajauvs.github.io/Portfoliot)",
"predeploy": "npm run build",
"deploy": "gh-pages -d dist"
```
