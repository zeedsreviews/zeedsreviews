# Zeeds Reviews

## Tech Stack
- **Frontend:** React, Redux
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Testing:** Jest, Mocha

## File Structure
```
├── client
│   ├── public
│   └── src
│       ├── components
│       ├── pages
│       └── redux
├── server
│   ├── config
│   ├── controllers
│   ├── models
│   └── routes
├── .gitignore
├── README.md
└── package.json
```

## Features
- User authentication and authorization
- Review posting and editing
- Searching and filtering of reviews
- User profiles and dashboards

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/zeedsreviews/zeedsreviews.git
   ```
2. Navigate into the project directory:
   ```bash
   cd zeedsreviews
   ```
3. Install dependencies for both client and server:
   ```bash
   cd client && npm install && cd ../server && npm install
   ```
4. Run the client and server:
   ```bash
   cd client && npm start
   ```
   In another terminal:
   ```bash
   cd server && npm start
   ```

## API Documentation
- **GET /api/reviews**: Retrieve all reviews
- **POST /api/reviews**: Create a new review
- **GET /api/reviews/:id**: Retrieve a review by ID
- **PUT /api/reviews/:id**: Update a review by ID
- **DELETE /api/reviews/:id**: Delete a review by ID
