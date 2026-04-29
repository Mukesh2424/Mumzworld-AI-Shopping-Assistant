# 🛍️ Mumzworld AI Shopping Assistant  
### AI Engineering Intern Assignment | Mukesh Inukula  

---

## 📌 Overview
This project is an AI-powered shopping assistant built for Mumzworld that helps parents discover the most suitable baby products based on their needs.

The system uses structured prompt engineering and a custom dataset to generate intelligent, constraint-based recommendations.

---

## 🎯 Problem
Parents often struggle to choose the right baby products due to:
- Too many options  
- Lack of clear guidance  
- Difficulty matching products to specific needs (age, skin type, budget)  

---

## 💡 Solution
Designed and implemented an AI shopping assistant that:
- Understands user queries  
- Filters products based on constraints  
- Recommends the best matches  
- Explains WHY each product is suitable  

---

## ⚙️ Tech Stack
- Google AI Studio (Gemini)  
- Prompt Engineering  
- JSON Dataset  

---

## 🔍 How It Works
1. User enters a query (e.g., "Best shampoo for 2 year old baby")  
2. AI interprets constraints (age, budget, features)  
3. Filters dataset  
4. Returns top 2–3 recommendations with reasoning  
5. Provides multilingual output (English + Arabic)  

---

## ✨ Key Features
- 🧠 Constraint-based reasoning (age, price, features)  
- 🌍 Multilingual support (English + Arabic)  
- 📊 Structured recommendations (clear format)  
- ❌ Rejection logic ("Why not other products")  

---

## 🧪 Sample Queries
- Best shampoo for 2 year old baby  
- Affordable baby lotion under ₹300  
- Products for sensitive skin baby  
- Best shampoo for 3 year old under ₹250  

---

## 📊 Evaluation Approach
- Relevance of recommendations  
- Accuracy in handling constraints  
- Quality of reasoning  
- Multilingual consistency  

---

## ⚠️ Tradeoffs
- Limited dataset (manually created)  
- No real-time product integration  

---

## 🔮 Future Improvements
- Integrate RAG with real product database  
- Add personalization  
- Voice-based interaction  

---

## 🎥 Demo Video
👉 https://www.loom.com/share/6e3b2c96f11f489fb4dfd9a3e5a7d013  

---

## 🔗 Project Link (Google AI Studio)
👉 https://ai.studio/apps/458a8e46-e5f2-44b9-bedb-db29ebc40552  

---

## 📦 Dataset
```json
[
  {
    "name": "Johnson's Baby Lotion",
    "category": "Skincare",
    "price": "₹250",
    "age_group": "0-2 years",
    "features": ["Gentle", "Hypoallergenic", "No parabens"],
    "description": "Softens baby's skin and prevents dryness"
  },
  {
    "name": "Himalaya Baby Shampoo",
    "category": "Haircare",
    "price": "₹180",
    "age_group": "0-5 years",
    "features": ["Tear-free", "Herbal", "Mild"],
    "description": "Cleans hair gently without irritation"
  },
  {
    "name": "Mamaearth Baby Wash",
    "category": "Skincare",
    "price": "₹399",
    "age_group": "0-5 years",
    "features": ["Soap-free", "Natural", "Tear-free"],
    "description": "Gently cleanses baby's skin without dryness"
  },
  {
    "name": "Sebamed Baby Cream",
    "category": "Skincare",
    "price": "₹450",
    "age_group": "0-3 years",
    "features": ["pH balanced", "Dermatologically tested", "Moisturizing"],
    "description": "Protects baby's delicate skin from dryness"
  },
  {
    "name": "Dabur Baby Massage Oil",
    "category": "Skincare",
    "price": "₹200",
    "age_group": "0-2 years",
    "features": ["Ayurvedic", "Nourishing", "Safe"],
    "description": "Strengthens baby's muscles and keeps skin soft"
  },
  {
    "name": "Chicco Baby Moments Shampoo",
    "category": "Haircare",
    "price": "₹320",
    "age_group": "0-5 years",
    "features": ["No tears", "Paraben-free", "Gentle"],
    "description": "Cleans baby's hair while being gentle on eyes"
  },
  {
    "name": "Pigeon Baby Wipes",
    "category": "Hygiene",
    "price": "₹150",
    "age_group": "0-3 years",
    "features": ["Alcohol-free", "Soft", "Moisturizing"],
    "description": "Keeps baby's skin clean and fresh"
  },
  {
    "name": "Mee Mee Baby Powder",
    "category": "Skincare",
    "price": "₹220",
    "age_group": "0-3 years",
    "features": ["Smooth", "Dermatologically tested", "Mild fragrance"],
    "description": "Keeps baby's skin dry and comfortable"
  }
]
