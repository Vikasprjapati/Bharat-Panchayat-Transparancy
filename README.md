# Bharat Panchayat Transparency

Bharat Panchayat Transparency is a comprehensive digital platform designed to bring transparency and accountability to local governance in India. It empowers citizens to monitor village development projects, track fund allocations, and participate in the democratic process at the grassroots level.

## 🚀 What It Does

- **Project Tracking:** Real-time monitoring of ongoing and completed panchayat projects.
- **Financial Transparency:** Detailed breakdown of budget allocations and expenditures for various schemes.
- **Citizen Dashboard:** A user-friendly interface for citizens to view local development data.
- **Officer Panel:** A secure portal for officials to update project statuses, upload documents, and manage fund tracking.
- **Grievance Redressal:** (Feature placeholder/implementation) A system for citizens to report issues or provide feedback on local projects.

## 💡 Potential Use Cases

- **Citizen Empowerment:** Helping villagers understand where their tax money is going.
- **Governance Auditing:** A tool for NGOs and auditors to verify ground-reality against official records.
- **Data-Driven Planning:** Assisting local leaders in identifying areas that need more investment.
- **Preventing Corruption:** Public visibility of contracts and fund transfers reduces the scope for financial irregularities.

## 🛠️ Tools & Technologies Used

### Frontend
- **React.js:** For building a dynamic and responsive user interface.
- **Vanilla CSS / Tailwind CSS:** Custom styling for a modern, premium look.
- **Axios:** For API communication with the backend.

### Backend
- **FastAPI (Python):** High-performance backend API framework.
- **SQLAlchemy:** SQL toolkit and Object-Relational Mapper (ORM).
- **SQLite:** Lightweight database for local development and demonstration.
- **Pydantic:** Data validation and settings management.

## ⚙️ Setup Guide

### Prerequisites
- **Python 3.9+**
- **Node.js 16+**
- **npm** or **yarn**

### 1. Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
3. Activate the virtual environment:
   - **Windows:** `venv\Scripts\activate`
   - **Unix/macOS:** `source venv/bin/activate`
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Start the backend server:
   ```bash
   uvicorn main:app --reload
   ```

### 2. Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

## 🏗️ Project Structure

- `/frontend`: React source code, components, and assets.
- `/backend`: FastAPI routes, database models, and logic.
- `panchayat.db`: Main database file (SQLite).

---
Developed with ❤️ for a more transparent Bharat.
