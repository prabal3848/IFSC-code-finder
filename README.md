# IFSC-code-finder


# Bank IFSC Finder 

A responsive web application built with HTML, CSS, and JavaScript that allows users to look up comprehensive bank branch details using a valid Indian Financial System Code (IFSC).

---

## Features

- **Instant Details Retrieval**: Fetches bank name, branch, address, city, district, state, and contact info directly from the IFSC code.
- **Validation**: Checks code formatting and ensures empty queries are flagged before submitting.
- **Responsive Layout**: Clean, mobile-friendly user interface.
- **Copy-to-Clipboard**: Quick access to copy retrieved details directly to the clipboard.
- **Error Handling**: Displays helpful alerts if an invalid or non-existent IFSC is entered.

---

## Built With

- **HTML5** – Markup structure and input forms
- **CSS3** – Modern styling, Flexbox/Grid layout, and smooth animations
- **JavaScript (ES6+)** – Fetch API for asynchronous requests and DOM manipulation
- **Razorpay IFSC API** (`https://ifsc.razorpay.com/`) – Open API endpoint for fetching branch records

---

## How It Works

1. Enter an 11-character IFSC code (e.g., `SBIN0000001` or `HDFC0000128`).
2. Click **Search** or hit **Enter**.
3. The application sends an asynchronous `GET` request to the IFSC lookup API.
4. If found, the branch information renders instantly on screen.

---

## Project Structure

```text
├── index.html       # Application layout and forms
├── style.css        # Styling and layout rules
├── script.js        # API call logic, validation, and DOM updates
└── README.md        # Project documentation
