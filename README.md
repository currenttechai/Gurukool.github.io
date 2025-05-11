hsc-qa-platform/
├── backend/
│   ├── config/
│   │   └── db.js
│   ├── controllers/
│   │   ├── authController.js
│   │   ├── subjectController.js
│   │   ├── questionController.js
│   │   ├── answerController.js
│   │   └── commentController.js
│   ├── middleware/
│   │   ├── authMiddleware.js
│   │   └── roleMiddleware.js
│   ├── models/
│   │   ├── User.js
│   │   ├── Subject.js
│   │   ├── Question.js
│   │   ├── Answer.js
│   │   └── Comment.js
│   ├── routes/
│   │   ├── auth.js
│   │   ├── subjects.js
│   │   ├── questions.js
│   │   ├── answers.js
│   │   └── comments.js
│   ├── utils/
│   │   └── cloudinary.js
│   ├── .env
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── public/
│   │   ├── index.html
│   │   └── favicon.ico
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.js
│   │   │   ├── SubjectList.js
│   │   │   ├── QuestionCard.js
│   │   │   ├── AnswerCard.js
│   │   │   ├── CommentSection.js
│   │   │   ├── MediaUploader.js
│   │   │   └── ... (other reusable components)
│   │   ├── pages/
│   │   │   ├── Home.js
│   │   │   ├── SubjectPage.js
│   │   │   ├── QuestionPage.js
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   ├── FAQ.js
│   │   │   └── AdminDashboard.js
│   │   ├── utils/
│   │   │   ├── api.js         # Axios instance
│   │   │   ├── auth.js        # JWT helpers
│   │   │   └── ... 
│   │   ├── context/           # (Or state management folder)
│   │   │   └── AuthContext.js
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ... (styles, assets, etc.)
│   ├── .env
│   └── package.json
└── README.md
