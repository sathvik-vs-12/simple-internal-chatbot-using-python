# simple-internal-chatbot-using-python
Here’s a well-structured **README.md** for your GitHub repository:  

---

# **Internal ChatBot Builder** 🤖  

A Python-based chatbot framework that allows users to **create, manage, train, and test chatbot datasets** dynamically. This system enables storing intents, responses, and datasets efficiently, making chatbot development more flexible and scalable.  

---

## **🚀 Features**  
✔️ **Create & Manage Datasets** – Organize chatbot responses under different datasets.  
✔️ **Intent Handling** – Add, update, and delete chatbot intents dynamically.  
✔️ **Trainable System** – Train the chatbot using stored datasets.  
✔️ **Test Intent Recognition** – Input test sentences to find the best-matching intent or response.  
✔️ **File Storage** – Persist chatbot data using `responses.txt` for long-term storage.  
✔️ **Interactive CLI Menu** – Simple menu-driven interface for easy use.  

---

## **🛠️ Tech Stack**  
- **Programming Language:** Python 🐍  
- **Data Storage:** File-based (`responses.txt`)  
- **Core Libraries:** Built-in Python libraries (`os`, `eval`, `dict`, `list`)  

---

## **📂 Project Structure**  
```
📦 InternalChatBot  
│── 📜 responses.txt  # Stores chatbot datasets  
│── 📜 chatbot.py      # Main chatbot script  
│── 📜 README.md       # Documentation  
```  

---

## **⚙️ Installation & Setup**  
### **🔹 Prerequisites**  
- Install Python (>=3.6)  
- Clone the repository  
```bash
git clone https://github.com/your-username/InternalChatBot.git
cd InternalChatBot
```
- Run the chatbot script  
```bash
python chatbot.py
```

---

## **📌 Usage**  
Upon running the script, you will be presented with an interactive menu to manage datasets and intents.  

### **1️⃣ Create a Dataset**  
- Enter a dataset keyword (e.g., `customer_support`)  
```text
Enter the dataset keyword: customer_support
Dataset with keyword 'customer_support' created.
```

### **2️⃣ Add an Intent & Responses**  
- Define chatbot responses for an intent.  
```text
Enter the dataset keyword: customer_support  
Enter the intent: greeting  
Enter responses (comma-separated): Hello! How can I help you?, Hi! Need any assistance?  
Intent 'greeting' added to dataset 'customer_support' with responses.  
```

### **3️⃣ Read an Intent's Response**  
```text
Enter the dataset keyword: customer_support  
Enter the intent to read: greeting  
Intent 'greeting' response in dataset 'customer_support': ['Hello! How can I help you?', 'Hi! Need any assistance?']
```

### **4️⃣ Update an Intent**  
Modify responses for an existing intent.  
```text
Enter the dataset keyword: customer_support  
Enter the intent to update: greeting  
Enter new responses (comma-separated): Hey there! How can I assist?, Welcome!  
Intent 'greeting' updated successfully.
```

### **5️⃣ Delete an Intent**  
```text
Enter the dataset keyword: customer_support  
Enter the intent to delete: greeting  
Intent 'greeting' deleted from dataset 'customer_support'.
```

### **6️⃣ Train the Chatbot**  
```text
Enter the dataset keyword to train the chatbot: customer_support  
Chatbot trained successfully with dataset keyword 'customer_support'.
```

### **7️⃣ Test Intent Matching**  
Input a test sentence and see the chatbot response.  
```text
Enter the dataset keyword: customer_support  
Enter a test intent: Hello, I need help  
Intent: 'greeting', Responses: ['Hey there! How can I assist?', 'Welcome!']
```

### **8️⃣ View All Stored Datasets**  
```text
Stored Datasets:  
Dataset Keyword: customer_support  
  Intent: greeting, Responses: ['Hey there! How can I assist?', 'Welcome!']
```

### **9️⃣ Exit Program**  
```text
Exiting the program. Goodbye!
```

---

## **📌 Future Enhancements**  
✅ **Integrate NLP for better intent recognition**  
✅ **Implement database storage (SQLite, Firebase) instead of file-based storage**  
✅ **Web or GUI-based chatbot interface**  
✅ **Pre-trained datasets for quick chatbot setup**  

---


---

Would you like any modifications or additions? 🚀
