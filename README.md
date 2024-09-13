# **Advanced AI Negotiation Chatbot**

## **Overview**
The **Advanced AI Negotiation Chatbot** is an AI-driven system that simulates a real-world negotiation process. It allows users to interact with a virtual salesperson by making offers for a product, while the AI calculates and responds with realistic pricing based on customer loyalty, competitor prices, and product features.

This chatbot uses Google’s Gemini Generative AI model to create dynamic and flexible interactions, making it an ideal tool for sales negotiations and customer interactions in a business setting.

---

## **Key Features**
- **Product Negotiation**: Users can negotiate the price of a product by offering different prices.
- **Real-Time Interaction**: The AI responds in real-time, justifying the price based on various factors.
- **Dynamic Pricing**: The chatbot adjusts its offers based on product features, competitor prices, and customer loyalty.
- **7 Rounds of Negotiation**: The AI allows up to 7 negotiation rounds before settling on a final price.
- **Competitor Pricing**: The chatbot compares competitor prices and uses them as part of the negotiation strategy.
- **Customer Loyalty Factor**: The AI factors in customer loyalty to adjust discounts and pricing strategies.

---

## **Installation**

### **Prerequisites**
- Python 3.7+
- Streamlit
- Google Generative AI SDK
- A Google Cloud account with access to the Generative AI API

### **Steps to Install**
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/negotiation-chatbot.git
    cd negotiation-chatbot
    ```

2. **Install Dependencies**:
    Install the required Python packages using the following command:
    ```bash
    pip install -r requirements.txt
    ```

3. **Set Up Google Gemini API**:
    - Sign up for Google Cloud and get access to the Generative AI API (Gemini).
    - Create a new API key and replace the `api_key` in the source code with your own API key.

4. **Run the Application**:
    Launch the chatbot using Streamlit:
    ```bash
    streamlit run app.py
    ```

---

## **Usage**
Once the application is running, you will be able to interact with the AI chatbot in a web interface.

1. **Start a New Negotiation**: The chatbot will greet you and provide the product's current price and features.
2. **Make an Offer**: Enter your offer into the chat input, and the chatbot will respond by either accepting or countering your offer based on internal calculations.
3. **View Competitor Prices**: The chatbot will also provide competitor prices to help you understand the market and make informed offers.
4. **Negotiate Further**: You can negotiate for up to 7 rounds before the chatbot settles on a final price.

---

## **Project Structure**
- **app.py**: The main file that runs the Streamlit application.
- **requirements.txt**: Lists all the required dependencies.
- **README.md**: This file containing instructions and project
