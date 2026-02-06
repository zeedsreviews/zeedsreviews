# README.md

## Tech Stack
- **Frontend:** React, Redux
- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Testing:** Jest, Enzyme
- **Deployment:** Heroku

## File Structure
```
/ 
├── src/              # Source files
│   ├── components/   # React components
│   ├── redux/        # Redux files
│   ├── api/          # API calls
│   └── utils/        # Utility functions
├── public/           # Static files
├── tests/            # Test files
├── package.json      # NPM dependencies
├── server.js         # Entry point for the server
└── README.md         # Documentation
```

## Features
- User authentication
- CRUD operations for reviews
- User profile management
- Responsive design
- Search functionality

## Installation Instructions
1. Clone the repository: `git clone https://github.com/zeedsreviews/zeedsreviews`
2. Navigate to the directory: `cd zeedsreviews`
3. Install dependencies: `npm install`
4. Start the application: `npm start`

## Available Scripts
- `npm start` - Starts the development server.
- `npm test` - Runs tests.
- `npm run build` - Builds the app for production.

## Dependencies
- **Frontend:**
  - `react`
  - `redux`
- **Backend:**
  - `express`
  - `mongoose`

## Development Guidelines
- Follow the code style outlined in `.eslintrc`
- Write tests for all new features
- Create pull requests for all changes

## API Documentation
- **GET /api/reviews** - Fetch all reviews
- **POST /api/reviews** - Create a new review
- **GET /api/reviews/:id** - Get a specific review
- **PUT /api/reviews/:id** - Update a review
- **DELETE /api/reviews/:id** - Delete a review

## Contributing Guidelines
1. Fork the repo
2. Create your feature branch: `git checkout -b feature/AmazingFeature`
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`
4. Push to the branch: `git push origin feature/AmazingFeature`
5. Open a Pull Request
6. Write your description of your changes
7. Wait for feedback

---

This project is licensed under the MIT License. See LICENSE for details.