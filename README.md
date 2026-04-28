# House Ventures MVP

## Overview
AI-powered ATS and opportunity system.

## Stack
- Backend: Go
- Frontend: React

## Run Backend
cd backend
go run cmd/api/main.go

## Run Tests
go test ./...

## Run Frontend
cd frontend
npm install
npm start

# PROJECT STRUCTURE

house-ventures/
│
├── backend/
│   ├── cmd/
│   │   └── api/
│   │       └── main.go
│   │
│   ├── internal/
│   │   ├── handlers/
│   │   │   └── resume_handler.go
│   │   │
│   │   ├── services/
│   │   │   ├── ats_service.go
│   │   │   └── matcher_service.go
│   │   │
│   │   ├── repository/
│   │   │   └── resume_repository.go
│   │   │
│   │   ├── models/
│   │   │   └── resume.go
│   │   │
│   │   └── utils/
│   │       └── response.go
│   │
│   ├── tests/
│   │   ├── ats_service_test.go
│   │   ├── matcher_service_test.go
│   │   └── resume_handler_test.go
│   │
│   ├── go.mod
│   ├── go.sum
│   └── README.md
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── pages/
│   │   │   └── AtsPage.jsx
│   │   ├── components/
│   │   │   └── ResumeForm.jsx
│   │   └── App.jsx
│   ├── package.json
│   └── README.md
│
├── docs/
│   └── architecture.md
│
├── scripts/
│   ├── run_backend.sh
│   ├── run_tests.sh
│   └── run_frontend.sh
│
├── .gitignore
├── README.md
└── LICENSE
