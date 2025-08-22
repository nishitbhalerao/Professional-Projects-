

# ✈️ Have A Break Tourism – Trip Itinerary & Booking

A **travel itinerary and booking demo web app** built with **HTML, CSS, and Vanilla JavaScript**.
This project allows users to browse curated itineraries, calculate trip costs dynamically, and manage bookings with **local storage persistence**.

---

## ✨ Features

* 🎨 **Modern UI/UX** – Responsive design with gradients, cards, and animations.
* 🗺️ **Featured Destinations** – Explore **Kashmir, Rajasthan, Kerala, Mumbai, and Kolkata**.
* 📅 **Booking Form** – Select destination, travel dates, travelers, hotel class, and plan type.
* 💰 **Auto Price Calculator** – Estimates cost based on:

  * Destination-specific base rate
  * Number of nights (auto from selected dates)
  * Adults + children (children count as 60%)
  * Hotel class multiplier (3★, 4★, 5★)
  * Plan type multiplier (Budget, Standard, Luxury)
* 📖 **Sample Itineraries** – Day-wise activities for each destination (accordion-style).
* 📂 **My Bookings Section** – Stores booking history in **browser localStorage**:

  * View bookings in a responsive table
  * **Edit** – Load booking back into form
  * **Delete** – Remove from saved bookings
* 🔔 **Toast Notifications** – Subtle alerts for actions (booking, edits, deletions).

---

## 📂 Project Structure

Single **HTML file** containing everything:

* **HTML** → Structure (navbar, hero, form, destinations, itineraries, bookings).
* **CSS (inside `<style>`)** → Styling with CSS variables, grid/flex layouts, and dark mode theme.
* **JavaScript (inside `<script>`)** →

  * Itinerary rendering
  * Price calculation logic
  * Booking form interactions
  * Local storage management
  * Toast notifications

---

## 🚀 Getting Started

1. Clone or download the project.
2. Open the file in any modern browser:

   ```bash
   open index.html
   ```

   or double-click the file.
3. Start browsing itineraries and making demo bookings! 🎉

---

## 🎮 Usage Flow

1. **Browse Destinations**

   * Explore featured destinations with best travel season tags.

2. **Check Itineraries**

   * Expand destination accordions to view 4-day sample itineraries.

3. **Book a Trip**

   * Fill in booking form → destination, dates, travelers, hotel, plan.
   * Estimated cost auto-updates instantly.
   * Submit booking → Added to "My Bookings".

4. **Manage Bookings**

   * View all bookings in a table.
   * **Edit** → Pre-fills form with booking details.
   * **Delete** → Removes from local storage.

---

## 🛠️ Tech Stack

* **HTML5** – Markup
* **CSS3** – Theming, responsive grid, flexbox, shadows
* **JavaScript (Vanilla)** –

  * DOM interactions
  * Local storage (`gv_bookings`)
  * Pricing + booking logic

---

## 📌 Notes

* This is a **demo UI only** – **no backend, no real payments**.
* Bookings are stored in **browser local storage**, persisting until cleared.
* Default trip duration = **3 nights** if dates are not selected.
* Designed for educational & demo purposes.

---


