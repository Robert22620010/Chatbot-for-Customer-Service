# Chatbot-for-Customer-Service
# 🤖 Customer Service Chatbot Using Python

## 📌 Project Overview

The **Customer Service Chatbot** is a Python-based project designed to answer basic customer queries automatically using a rule-based approach.

The chatbot interacts with users through a text-based interface and provides predefined responses to frequently asked questions related to orders, payments, delivery, refunds, cancellations, products, and account management.

It uses keyword matching to understand user messages and generates appropriate responses from its predefined knowledge base.

The main objective of this project is to demonstrate the basic concepts of chatbot development, rule-based systems, and natural language processing.

## ✨ Features

- **Interactive Conversation:** Communicates with users through a text-based interface.
- **Order Tracking:** Provides information about order status and tracking.
- **Payment Support:** Answers questions about payment methods and failed transactions.
- **Delivery Information:** Provides estimated delivery details.
- **Return and Refund Support:** Answers questions about product returns and refunds.
- **Order Cancellation:** Provides cancellation instructions.
- **Account Assistance:** Helps with login, registration, and password-related queries.
- **Product Information:** Answers basic product availability and pricing questions.
- **Discount Information:** Provides information about offers and coupon codes.
- **Complaint Handling:** Responds to customer complaints and problems.
- **Multiple Responses:** Selects different predefined responses randomly.
- **Exit Option:** Allows users to end the conversation by typing 'bye'.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Random Module | Selects random chatbot responses |
| Rule-Based Matching | Matches user queries with predefined keywords |
| Dictionary | Stores chatbot questions, keywords, and responses |
| VS Code / PyCharm | Development environment |

## 📂 Dataset

This project does not require an external dataset because it uses a predefined knowledge base created directly in Python.

The knowledge base contains 14 customer service categories:

| Category | Example Queries |
|---|---|
| Greeting | Hello, Hi, Hey |
| Order Status | Track my order |
| Payment | Payment failed |
| Delivery | When will my order arrive? |
| Return | How can I return a product? |
| Refund | Where is my refund? |
| Cancellation | Cancel my order |
| Account | Forgot my password |
| Product | Is this product available? |
| Discount | Do you have any offers? |
| Complaint | I have a problem |
| Contact | Contact customer support |
| Working Hours | What are your support hours? |
| Thanks / Goodbye | Thank you, Bye |

Each category contains multiple keywords and predefined responses.

## 🧠 Model Architecture

The chatbot follows a **Rule-Based Chatbot Architecture**.

It uses keyword matching to identify the user's intention and provides an appropriate response.

### Working Process

1. **User Input:** The user enters a question or message.
2. **Text Preprocessing:** Converts the input into lowercase and removes unnecessary surrounding spaces.
3. **Keyword Matching:** Compares the user's message with predefined keywords stored in the knowledge base.
4. **Category Identification:** Identifies the matching customer service category.
5. **Response Generation:** Randomly selects one response from the matching category.
6. **Output:** Displays the response to the user.

### Architecture Flow

```text
       User Input
            |
            v
     Text Preprocessing
            |
            v
      Keyword Matching
            |
            v
    Category Identification
            |
            v
    Response Selection
            |
            v
      Chatbot Response
            |
            v
        User Output
```

### Algorithm Used

**Rule-Based Keyword Matching**

The chatbot searches for predefined keywords in the user's message.

For example:

- User Input: "Where is my order?"
- Matching Keyword: "where is my order"
- Category: Order Status
- Response: "You can track your order using the tracking ID sent to your email."

The Random module selects one response from the available responses.

## 📊 Results

The chatbot successfully responds to common customer service queries using predefined keywords and responses.

### Sample Input

```text
You: Hello

You: Where is my order?

You: How can I get a refund?

You: I forgot my password.

You: Thank you!

You: Bye
```

### Sample Output

```text
Bot: Hi there! Welcome to customer support.

Bot: You can track your order using
the tracking ID sent to your email.

Bot: You can check your refund status
in the My Orders section.

Bot: Use the Forgot Password option
to reset your password.

Bot: You're welcome! Happy to help.

Bot: Thank you for using our
customer service chatbot!
```

### Result Analysis

- Successfully identifies predefined customer queries.
- Provides relevant responses for supported keywords.
- Supports multiple customer service categories.
- Generates different responses using random selection.
- Handles unknown queries with a default response.

**Note:** This is a basic rule-based chatbot, not a trained machine learning model. Its response accuracy depends on the keywords defined in the knowledge base.

## 🚀 How to Run

Follow these steps to run the chatbot on your computer.

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/customer-service-chatbot.git
```

### Step 2: Open the Project Folder

```bash
cd customer-service-chatbot
```

### Step 3: Install Requirements

No external Python libraries are required.

The project uses Python's built-in `random` module.

### Step 4: Run the Python Program

```bash
python customer_chatbot.py
```

### Step 5: Start Chatting

Enter your questions in the terminal and the chatbot will generate suitable responses.

Type `bye` to exit the chatbot.

## 📁 Repository Structure

```text
customer-service-chatbot/
│
├── customer_chatbot.py
│
├── README.md
│
├── requirements.txt
│
└── screenshots/
    └── chatbot_output.png
```

## 👨‍💻 Author

**Gargi Kumar Choudhery**

- GitHub: https://github.com/Robert22620010
