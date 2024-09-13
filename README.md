## .env File Configuration

In the root directory of your project, create a `.env` file with the following content:

```bash
# Backend Variables
PORT = 3000
MONGO_DB_URI = mongodb+srv://<your-username>:<your-password>@cluster0.3bxz1.mongodb.net/<your-database>?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET = your_jwt_secret
NODE_ENV = development

# Frontend Variables (Vite)
VITE_API_URL = http://localhost:3000
