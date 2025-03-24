# E-Commerce Product Management

This project provides a convenient platform for browsing, purchasing, and managing products in an online store.

---

## How to Run

1. **Navigate to the project directory**

   ```bash
   cd project/app
   ```

2. **Build and start Docker Compose**

   ```bash
   docker-compose up -d --build
   ```

3. **Open the application in your browser**
   - The application is available at [http://localhost:8000](http://localhost:8000)
   - API documentation is available at [http://localhost:3000/docs](http://localhost:3000/docs)

---

## Example .env File

Place the `.env` file in the same folder as `docker-compose.yml`:

```
MYSQL_PASSWORD=pass
MYSQL_DATABASE=ECPM
MYSQL_USER=mysql
MYSQL_HOST=localhost
MYSQL_PORT=3306
MYSQL_ROOT_PASSWORD=root_pass

SECRETKEY=your_key

GOOGLE_CLIENT_ID=your_data
GOOGLE_CLIENT_SECRET=your_data
REDIRECT_URI=http://127.0.0.1:8000/oauth/callback

AZURE_CONNECTION_STRING=your_data
AZURE_ACCOUNT_NAME=your_data
AZURE_ACCOUNT_KEY=your_data
AZURE_CONTAINER_NAME="imagecontainer"

GITHUB_CLIENT_ID=your_data
GITHUB_CLIENT_SECRET=your_data
```

> **Note**: Adjust any values as needed to fit your environment.

---

## Technologies Used

- **Node.js**
- **Sequelize**
- **Vue.js**
- **Vue Router**
- **Pinia**
- **Zod**
- **Tailwind CSS**
- **Docker + Docker Compose**
- **Azure Blob Storage**
- **JWT (JSON Web Tokens)**
- **Google OAuth**
- **Github OAuth**
- **Swagger**
