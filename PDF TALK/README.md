# AI SaaS Challenge Project  

Welcome to the **AI SaaS Challenge Project** repository! This project demonstrates the creation of a scalable SaaS platform that integrates cutting-edge AI technologies, user authentication, and payment processing. Built using modern frameworks and tools, this project is a complete solution for managing documents, real-time chat, and subscription-based services.  

---

## **Features**  
- **User Authentication**: Secure user login and role management with Clerk authentication and middleware.  
- **Document Management**: Upload, view, delete, and download documents with seamless file handling via Firebase Storage.  
- **Real-Time Chat**: AI-powered chat functionality using Langchain and OpenAI for document-related queries.  
- **Payment Integration**: Subscription plans and payment processing through Stripe with webhook integration.  
- **Scalable Design**: Built with responsive and modular components using Shadcn/UI.  

---

## **Tech Stack**  
- **Frontend**: Next.js, React, Shadcn/UI  
- **Backend**: Firebase (Firestore & Storage), Stripe Webhooks  
- **AI Integration**: Langchain, OpenAI  
- **Authentication**: Clerk  
- **Deployment**: Vercel  

---

## **Installation**  

### Prerequisites  
- Node.js >= 16.x  
- Firebase account  
- Stripe account  
- Clerk account  

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Nilansh7/ai-saas-challenge.git  
   cd ai-saas-challenge  
   ```  

2. Install dependencies:  
   ```bash  
   npm install  
   ```  

3. Configure environment variables:  
   Create a `.env` file with the following keys:  
   ```env  
   NEXT_PUBLIC_CLERK_FRONTEND_API_KEY=<Your Clerk API Key>  
   FIREBASE_API_KEY=<Your Firebase API Key>  
   STRIPE_SECRET_KEY=<Your Stripe Secret Key>  
   OPENAI_API_KEY=<Your OpenAI API Key>  
   ```  

4. Start the development server:  
   ```bash  
   npm run dev  
   ```  

5. Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.  

---

## **Usage**  
- **Upload Documents**: Log in and upload documents via the dashboard.  
- **AI Chat**: Use the AI-powered chat to ask questions about your documents.  
- **Manage Subscriptions**: Upgrade or downgrade plans on the pricing page.  
- **Test Real-Time Features**: Delete, download, or modify files instantly.  

---

## **License**  
This project is licensed under the MIT License.  

## **Acknowledgments**  
Special thanks to the **PAPA Challenge Team** for organizing this event and providing the resources to build this project.  
