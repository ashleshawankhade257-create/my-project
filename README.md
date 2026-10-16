this is my college miniproject for DS 
🍽️ CraveCorner — Campus Food Ordering Website

CraveCorner is a modern, responsive campus food ordering website designed to make ordering food simple, convenient, and organized. This academic project demonstrates a food ordering workflow with a focus on user experience and the use of a First-In, First-Out (FIFO) queue data structure for fair order processing.

✨ Features

- Home Page: Elegant design with a campus-food theme.
- Food Menu: Browse dishes, search for items, and filter vegetarian options.
- Shopping Cart: Add food items and review your order.
- Checkout: Enter customer details and pickup or delivery notes.
- Order Tracking: Check order status using an order number.
- Order Management: Demonstrates order processing through pending, preparing, and completed states.
- Responsive Design: Designed to work across desktop and mobile screens.
- Queue-Based Processing: Uses FIFO principles to process orders in the order they arrive.

🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Python 3
- Flask
- SQLite
- Python "collections.deque"
- Fetch API

🧠 Data Structure Used

First-In, First-Out (FIFO) Queue

CraveCorner demonstrates how a queue can organize incoming food orders fairly.

1. New orders are added to the rear of the queue.
2. The first pending order is moved into preparation.
3. Orders progress from Pending → Preparing → Completed.
4. Completed orders are removed from the active queue, while receipts are retained in the database.

This demonstrates a practical application of data structures in a real-world-style food ordering system.

🚀 How to Run

Option 1: View the HTML file

1. Download "CraveCorner.html" from this repository.
2. Open it in a modern web browser.
3. Explore the website's interface.

Note: The HTML file contains the website interface, but a complete Flask backend requires the corresponding Python server code, database setup, and any supporting files. The standalone HTML file alone may not support all backend-dependent features.

Option 2: Run the complete application

If the full project includes the Flask backend and its supporting files:

1. Install Python 3.
2. Install Flask and any other required dependencies.
3. Configure the SQLite database as needed.
4. Start the Flask application using its documented entry point.
5. Open the local URL provided by Flask in your browser.

🎯 Project Objective

The objective of CraveCorner is to demonstrate how web development and data structures can be combined to create a user-friendly campus food ordering system. It connects frontend design with concepts such as queues, order status management, and database persistence.

📚 Project Type

Academic Project · Web Development · Data Structures and Algorithms

👩‍💻 Author

Created as an academic project.

📄 License

This project is intended for educational and demonstration purposes. Add a license file if you wish to specify formal permissions for reuse and distribution.

---

CraveCorner — Good food. Good timing. 🍴
CraveCorner/
├── README.md
├── CraveCorner.html
├── app.py              # If available
├── requirements.txt    # If available
└── database/           # If your project uses this folder
