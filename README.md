QueryGenie is an intelligent chatbot that allows users to interact with relational databases using plain English. It translates natural language queries into accurate SQL statements using intent classification and slot filling, enabling seamless database access for non-technical users.

## 🚀 Key Features

- 🔄 Converts English queries into SQL with **95%+ accuracy**
- 🧠 Uses **Intent Classification** to identify query type
- 🧩 Applies **Slot Filling** to extract tables, columns, conditions, and operators
- 📊 Supports **50+ SQL query patterns**
- ✅ Tested with **100+ scenarios** to ensure correctness and compliance
- 💬 Chat-based interaction model
- 🔒 Prevents malformed and invalid SQL generation

## 🏗️ System Workflow

1. User enters a query in natural language  
2. Intent classification identifies query purpose  
3. Slot filling extracts required entities  
4. SQL template is generated  
5. Query is validated  
6. SQL is executed on the database  
7. Results are returned to the user  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **NLP:** spaCy / NLTK / Transformer-based models  
- **ML:** Intent Classification Models  
- **Database:** MySQL / PostgreSQL / SQLite  
- **Backend:** Flask / FastAPI  
- **Testing:** Custom automated test suite  
