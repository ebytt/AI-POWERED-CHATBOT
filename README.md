EbunStoresBot: AI-Powered Chatbot
Explore the deployed chatbot here: 
EbunStoresBot Project: https://ebytt.github.io/AI-POWERED-CHATBOT/
Project Overview
EbunStoresBot is an AI-powered chatbot designed to provide seamless customer support by answering common inquiries related to product availability, order tracking, return policies, shipping details, and support guidelines. Built on Google Cloud Platform (GCP) using Vertex AI Agent Builder, it ensures scalability, reliability, and intelligent automation for enhanced customer interactions.
Project Architecture
- Google Cloud Platform (GCP) – Cloud service provider.
- Vertex AI Agent Builder – Manages and configures the chatbot.
- Google Cloud Storage – Hosts chatbot training data.
- Web Interface – Provides a user-friendly front-end for interaction.
Training Data Used
EbunStoresBot was trained using structured business data, ensuring accurate and relevant responses. The chatbot learns from the following sources:
1. Product Catalog
Provides details on available products, specifications, prices, and stock levels.
Example Query: "Do you have Flatscreen TV  in stock?"
Example Response: " We have an Ultra HD TV in stock. It has 4K resolution, Smart TV, and HDR10+ features.."
2. Order Tracking Guide
Allows users to check the status of their orders by providing their order ID and email.
Example Query: "How can I track my order?"
Example Response: "Visit our website, click on 'Track Order,' and enter your order ID and email address, view the status of your order."
3. Return Policies
Includes return timeframes, exchange policies, and refund processing details.
Example Query: "Can I return an item I purchased?"
Example Response: " ou can return items within 30 days of purchase. Refunds are processed within 7 business days after the returned item is received."
4. Shipping Policies
Explains the shipping options, costs, and estimated delivery times.
Example Query: "What shipping methods are available?"
Example Response: " Standard delivery is available in 3-5 business days. International shipping is available to selected countries for an additional fee.."
5. Support Guidelines
Assists customers with issues related to refunds, complaints, and contacting support.
Example Query: "How do I contact customer support?"

Example Response: " You can contact customer support by phone at 0123456789 or by email at support@ebunstores.com.  "

Setup Guide
Step 1: Activate Vertex AI Agent Builder API
1. Log in to GCP Console.
2. Navigate to Vertex AI > Agent Builder.
3. Enable the Agent Builder API by ticking the checkbox.
Step 2: Create the Chatbot Application
1. Click on Apps in Vertex AI Agent Builder.
2. Select Chat Application.
3. Click Create and configure the chatbot:
   - Company Name: EbunStores
   - Agent Name: EbunStoresBot
   - Location: Multi-Region
Step 3: Configure Data Storage
1. Create a Google Cloud Storage Bucket:
   - Navigate to Cloud Storage.
   - Click Create Bucket.
   - Bucket Name: ebunstoresbucket (bucket names must be unique).
   - Location: Multi-region.
2. Upload the synthetic document (CSV, JSON, etc.) containing chatbot training data.
Step 4: Connect Data Store to Chatbot
1. In Vertex AI Agent Builder, link the chatbot to the Google Cloud Storage bucket.
2. Allow the DAGflow CX agent to process and learn from the uploaded data.
Step 5: Deploy the Chatbot on a Website
1. Develop a web-based interface where users can interact with EbunStoresBot.
2. Integrate with GCP to process chatbot responses in real time.
How It Works
1. **User Interaction**: The chatbot receives queries from users via the web interface.
2. **Data Processing**: Vertex AI Agent Builder processes the input and retrieves relevant responses using the trained data.
3. **Response Generation**: The chatbot provides an appropriate response based on stored knowledge and AI-powered inference.
4. **Continuous Learning**: The chatbot improves over time as more data is processed.
Technologies Used
- Google Cloud Platform (GCP)
- Vertex AI Agent Builder
- Google Cloud Storage
- DAGflow CX Agent
- Python/JavaScript (for web integration)
- Machine Learning & NLP
Future Enhancements
- Integrate with BigQuery for real-time analytics.
- Enable voice-based interaction with Google Dialogflow.
- Improve NLP capabilities using custom-trained models.
- Expand support for multiple languages.
Conclusion
EbunStoresBot is a scalable, intelligent chatbot solution that enhances customer engagement. With seamless integration, powerful automation, and continuous learning, it’s perfect for businesses aiming to improve customer interactions.
🚀 Get Started
Deploy EbunStoresBot today and experience the power of AI-driven conversations!
![image](https://github.com/user-attachments/assets/b02a807a-286b-4d00-a894-ba0505bc234f)
