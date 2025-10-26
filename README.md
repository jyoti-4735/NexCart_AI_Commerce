# NexCart_AI_Commerce

**AI-powered full-stack e-commerce platform**  
Built with React, Node.js, MongoDB, and Python (Flask).  
Features: JWT authentication, Stripe payments, product management, AI-based recommendations, Docker, CI/CD, cloud deployment.

## 🧩 Tech Stack

| Layer       | Tech                                           |
|-------------|------------------------------------------------|
| Frontend    | React, Tailwind CSS, Redux Toolkit             |
| Backend     | Node.js, Express, Mongoose, JWT                |
| AI Service  | Python, FastAPI / Flask, scikit-learn          |
| Storage     | MongoDB Atlas                                  |
| Payment     | Stripe API                                     |
| Container   | Docker, Docker Compose                         |
| CI/CD       | GitHub Actions                                 |
| Deployment  | Vercel (frontend), Render / AWS (backend)      |

## 📂 Folder Structure


## 🚀 Getting Started

### Prerequisites
- Node.js, npm
- Python 3.x
- Docker & Docker Compose
- MongoDB Atlas connection string
- Stripe API keys

### Run Locally
1. Clone the repo  
2. Copy `.env.example` to `.env` and fill variables  
3. From root, run:

```bash
docker-compose up --build

This starts:

Frontend → http://localhost:3000

Backend API → http://localhost:5000

AI Service → http://localhost:8000

🧪 Testing

cd server && npm test

cd client && npm test

📄 API Documentation

API documentation via Swagger at http://localhost:5000/api-docs (when backend running)

🎬 Demo

(Include a link to your demo video here later)

📈 Future Enhancements

ElasticSearch for advanced product search

Wishlist / Reviews / Ratings

Recommendation explanations

Analytics dashboard

📝 License

This project is licensed under the MIT License. See LICENSE file for details.

---

## 5. First Commit Steps

1. Locally clone your repo:
   ```bash
   git clone https://github.com/jyoti-4735/NexCart_AI_Commerce.git
   cd NexCart_AI_Commerce```

2. Create the directories:
mkdir client server ai_service .github/workflows
touch docker-compose.yml

Add the Dockerfiles and CI templates above to their respective places.

Add the README template content to README.md (overwrite initial).

Add .gitignore entries:
node_modules
.env
__pycache__
*.pyc
client/node_modules
server/node_modules
ai_service/venv

Stage & commit:
git add .
git commit -m "Initial project structure + Docker + CI templates + README"
git push origin main


