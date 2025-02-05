

### **Encoding in Machine Learning**  
Encoding converts categorical data into numerical format for ML models.  

#### **Types of Encoding:**  
✅ **Label Encoding** – Assigns a unique integer to each category.  
   - Example (for features): `["Red", "Blue", "Green"] → [0, 1, 2]`  
   - Example (for target variable in binary classification): `["Yes", "No"] → [1, 0]`  
   - ⚠️ Can create unintended ordinal relationships in non-ordered categories.  

✅ **One-Hot Encoding** – Represents categories as binary vectors.  
   - Example:  
     ```  
     Red   → [1, 0, 0]  
     Blue  → [0, 1, 0]  
     Green → [0, 0, 1]  
     ```  

✅ **Ordinal Encoding** – Maps ordered categories to integers.  
   - Example: `["Low", "Medium", "High"] → [0, 1, 2]`  

Each method is used based on category type and model requirements. 🚀  
