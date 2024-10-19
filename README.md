# Rule Engine with AST

![image](https://github.com/user-attachments/assets/b650b1d0-88f5-4d4c-98bb-ced66a42cf36)

This project is a **3-tier rule engine application** designed to determine user eligibility based on attributes such as **age, department, income, spend**, and more. It leverages an **Abstract Syntax Tree (AST)** to represent conditional rules, enabling dynamic creation, combination, and modification of these rules.

## 🚀 Objective

The application evaluates complex rules dynamically based on a user's data attributes. It offers APIs for:

- Creating rules and converting them into ASTs.
- Efficiently combining multiple rules.
- Evaluating rules against user data for eligibility determination.

---

## 🌟 Key Features

- **AST Representation**: Uses AST (Abstract Syntax Tree) to define and evaluate rules.
- **Dynamic Rule Creation**: Create rules from strings and convert them into AST format dynamically.
- **Efficient Rule Combination**: Combine multiple rules while minimizing redundant checks.
- **Rule Evaluation**: Evaluate user attributes against rules to determine eligibility.

---

## 🛠️ Functionalities

### For Users:
- **Create Rules**: Define conditional rules using a user-friendly UI, then convert them into ASTs.
- **Modify Rules**: Update operators, operands, or sub-expressions within the AST.
- **Evaluate Rules**: Test rules against user data (e.g., age, department, salary) for eligibility checks.
- **Combine Rules**: Merge multiple rules into a single AST using efficient strategies to reduce redundant checks.

### For Administrators:
- **Manage Rules**: Create, update, or delete rules within a centralized catalog.
- **View Rule Details**: View and validate rules in AST format for debugging.

### General Features:
- **Simple UI**: Easy-to-use interface for creating and managing rules.
- **API Integration**: RESTful API endpoints for rule creation, combination, and evaluation.
- **Data Persistence**: Persist rules and metadata in a PostgreSQL database.
- **Error Handling**: Robust error handling for invalid rule strings or formats.
- **Validation**: Ensure attributes meet predefined criteria from the rule catalog.

---

## 📸 Snapshots

### Rule Details
![Rule Details](https://github.com/user-attachments/assets/2e556085-b162-49d3-b125-09bb144c0efe)

### Create Rule
![Create Rule](https://github.com/user-attachments/assets/0fccfbef-caca-472d-996c-efaacdca8858)

### Evaluate Rule
![Evaluate Rule](https://github.com/user-attachments/assets/0a418d7f-4a49-45d9-b946-2399515f6fa7)

### Database Schema
![Database Schema](https://github.com/user-attachments/assets/e26ced63-1c75-4f89-8879-f55219676801)

---

## 🛠️ Installation & Setup

### Follow these steps to set up the project locally:

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   ```

2. **Navigate to the project directory:**

   ```bash
   cd rule-engine
   ```

3. **Install dependencies:**

   ```bash
   npm install
   ```

4. **Set up environment variables:**

   Create a `.env` file with the following keys:

   ```bash
   DB_URL=<your_database_url>
   ```

5. **Run both the Frontend and Backend:**

   **To start the frontend:**

   ```bash
   npm start
   ```

   **To start the backend:**

   ```bash
   node index.js
   ```

6. **Access the application:**  
   - **Frontend**: Open `http://localhost:3000` in your browser.  
   - **Backend**: API will run on `http://localhost:5000`.

---

## 🛠️ Tech Stack

- **Frontend**: React.js (or similar)
- **Backend**: Node.js with Express.js
- **Database**: PostgreSQL
- **Rule Engine**: Abstract Syntax Tree (AST)
- **Deployment**: Docker or cloud services (optional)

---

## 🤝 Contact

For any questions or contributions, feel free to reach out via:
- [LinkedIn](https://www.linkedin.com/in/shaswat-gusain-2924a324a/)
- [Email](mailto:shaswatgusain1@example.com)

---

