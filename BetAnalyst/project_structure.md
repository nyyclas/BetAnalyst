# BetAnalyst

## Project Structure

```
BetAnalyst/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   └── services/
│   ├── tests/
│   ├── Dockerfile
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│   │   └── utils/
│   ├── tests/
│   ├── Dockerfile
│   └── package.json
│
├── config/
│   ├── config.yaml
│   └── .env
│
├── docker-compose.yml
├── README.md
└── .gitignore
```

## Directories and Files Description
- **backend/**: Contains backend server code.
    - **src/**: Source files for backend development.
    - **tests/**: All test cases for the backend.
    - **Dockerfile**: Docker configuration for running backend.
    - **package.json**: Dependencies and scripts for the backend.
- **frontend/**: Contains frontend application code.
    - **src/**: Source files for frontend development.
    - **tests/**: All test cases for the frontend.
    - **Dockerfile**: Docker configuration for running frontend.
    - **package.json**: Dependencies and scripts for the frontend.
- **config/**: Configuration files for the application.
    - **config.yaml**: Main configuration file.
    - **.env**: Environment variables for the project.
- **docker-compose.yml**: Docker Compose file for managing multi-container Docker applications.
- **README.md**: Project documentation.
- **.gitignore**: Specifies which files and directories to ignore in the repository.
