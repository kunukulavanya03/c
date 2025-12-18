# c

Backend API for c

## Tech Stack

- **Frontend**: React
- **Backend**: FastAPI + SQLAlchemy
- **Frontend Source**: GitHub ([Repository](https://github.com/HimaShankarReddyEguturi/Designecommerceproductui.git))

## Project Structure

```
c/
├── frontend/          # Frontend application
├── backend/           # Backend API
├── README.md          # This file
└── docker-compose.yml # Docker configuration (if applicable)
```

## Getting Started

### Prerequisites

- Node.js 18+ (for frontend)
- Python 3.11+ (for Python backends)
- Docker (optional, for containerized setup)

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Backend Setup

```bash
cd backend
# Follow backend-specific setup instructions in backend/README.md
```

## Features

- user registration
- user login
- user profile management
- item browsing
- cart management
- checkout

## API Endpoints

- `POST /api/register` - Create a new user account
- `POST /api/login` - Log in to an existing user account
- `GET /api/profile` - Retrieve the current user's profile information
- `PUT /api/profile` - Update the current user's profile information
- `GET /api/items` - Retrieve a list of available items
- `GET /api/items/{item_id}` - Retrieve details of a specific item
- `POST /api/cart` - Add an item to the current user's cart
- `GET /api/cart` - Retrieve the current user's cart
- `POST /api/checkout` - Complete a purchase and clear the cart

## License

MIT
