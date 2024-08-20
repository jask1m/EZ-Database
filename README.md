# EZ Database Notes

## Note-Taking Application

EZ Database Notes is a robust, full-stack application that enables users to create, store, and organize digital notes securely and efficiently. This application combines the power of Django Rest Framework on the backend with the dynamic user interface capabilities of React on the frontend, delivering a seamless and intuitive note-taking experience.

<img width="440" alt="Screenshot 2024-08-20 at 3 46 22 PM" src="https://github.com/user-attachments/assets/df987621-041b-4c89-9df4-bf413ca03b71">

### Key Features

- **Intuitive Organization**: Effortlessly categorize and tag your notes for quick retrieval.
- **Real-time Synchronization**: Access your notes across devices with fast updates.
- **RESTful API**: Built on Django Rest Framework, offering a scalable and maintainable backend architecture.
- **JWT Authentication**: Implement industry-standard JSON Web Tokens for secure user authentication and authorization.
- **Responsive Design**: Enjoy a fluid user experience across desktop, tablet, and mobile devices.

### Technology Stack

#### Backend
- **Django**: High-level Python web framework known for its "batteries-included" philosophy.
- **Django Rest Framework**: Powerful and flexible toolkit for building Web APIs.
- **PostgreSQL**: Advanced open-source database for data integrity and complex queries.

#### Frontend
- **React**: A JavaScript library for building user interfaces with reusable components.
- **Redux**: State management for consistent application behavior.
- **Axios**: Promise-based HTTP client for seamless API integration.

### Security First

EZ Database Notes prioritizes your data's security:

- End-to-end encryption for all stored notes
- JWT token-based authentication to prevent unauthorized access
- Regular security audits and updates

### Getting Started

1. Clone the repository
   ```
   git clone https://github.com/yourusername/ez-database-notes.git
   ```

2. Set up the backend
   ```
   cd ez-database-notes/backend
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   ```

3. Set up the frontend
   ```
   cd ../frontend
   npm install
   npm start
   ```

4. Open your browser and navigate to `http://localhost:3000`
