# Note Taking App  

A simple and efficient note-taking application built with **Django (backend)** and **Vite + React (frontend)**.  

## Features  
✅ User authentication (Login/Signup)  
✅ Create, edit, and delete notes  
✅ Real-time updates  
✅ Responsive UI  

## Technologies Used  
### Backend  
- Django  
- Django Rest Framework  

### Frontend  
- Vite  
- React  
- Tailwind CSS  

### Database  
- SQLite (default) or PostgreSQL  

## Installation & Setup  

### Backend Setup  
1. **Clone the repository:**  
   ```sh
   git clone https://github.com/Arun131004/Note_App.git
   cd Note_App/backend
   ```
2. **Create a virtual environment and activate it:**  
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```
3. **Install dependencies:**  
   ```sh
   pip install -r requirements.txt
   ```
4. **Run migrations and start the server:**  
   ```sh
   python manage.py migrate
   python manage.py runserver
   ```

### Frontend Setup  
1. **Navigate to frontend directory:**  
   ```sh
   cd ../frontend
   ```
2. **Install dependencies:**  
   ```sh
   npm install
   ```
3. **Run the frontend:**  
   ```sh
   npm run dev -- --host
   ```
4. **Access the application**  
   - Open `http://localhost:5173/` in your browser.  

