# Boutique_assistance-
# 👗 Smart Boutique AI Assistant

A premium, interactive chatbot designed for boutique e-commerce experiences. This assistant features a modern "Glassmorphism" UI, dynamic product catalogs, and clickable selection logic.

---

## ✨ Key Features

* **Interactive Selection:** Users can click directly on product cards to select items, triggering contextual bot responses.
* **Intelligent Intent Recognition:** Uses basic NLP logic to handle greetings, product inquiries, and order tracking.
* **State Management:** The bot "remembers" if it is waiting for specific user input (like an Order ID).
* **Responsive UI:** Optimized for both desktop and mobile viewing with a sleek, pink-accented boutique theme.
* **Fuzzy Matching:** Built to understand common user requests even with minor variations in phrasing.

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Structure and semantic content. |
| **CSS3** | Modern styling, Flexbox layouts, and fadeIn animations. |
| **JavaScript (ES6)** | Logic, state handling, and dynamic DOM manipulation. |

## 🚀 How to Use

1.  **Clone the project:** Save the `.html` file to your local machine.
2.  **Launch:** Open the file in any modern web browser (Chrome, Safari, Edge).
3.  **Interact:**
    * Type `"Show collection"` to see clickable product cards.
    * Click on a **Product Card** to instantly select it.
    * Type `"Track order"` to enter the order tracking state.

## 📂 Code Structure

* `inventory[]`: An array of objects containing product names and prices.
* `selectProduct(id, name)`: The core function that bridges the UI and the bot logic when a card is clicked.
* `addMessage(text, sender)`: A reusable utility to inject chat bubbles into the interface.
* `handleSend()`: Processes text input and determines the bot's reaction.

## 📝 Future Enhancements

- [ ] **Database Integration:** Connect to Firebase or MongoDB to save real-time orders.
- [ ] **Payment Gateway:** Integrate Stripe or Razorpay for direct checkout within the chat.
- [ ] **Image Support:** Add high-resolution images to the product cards.

---

*Developed for Premium Boutique Experiences.*
