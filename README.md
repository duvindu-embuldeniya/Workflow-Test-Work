# Workflow Test Work

## Project Description
This project serves as a demonstration of workflow automation using CI/CD practices. It is designed to showcase the principles of Continuous Integration and Continuous Deployment in a practical manner.

## Project Structure
```
Workflow-Test-Work/
├── .github/
│   └── workflows/
│       ├── ci.yml
│       └── cd.yml
├── src/
│   └── main.py
├── tests/
│   └── test_main.py
└── README.md
```

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/duvindu-embuldeniya/Workflow-Test-Work.git
   cd Workflow-Test-Work
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**
   ```bash
   python src/main.py
   ```

## CI/CD Workflow
The CI/CD workflow is defined in the `.github/workflows/` directory. It includes:
- **Continuous Integration (ci.yml):** Triggers on push or pull request to the main branch, running tests and static checks.
- **Continuous Deployment (cd.yml):** Triggers on successful CI runs to deploy the code to the production environment.

This setup ensures that code is frequently tested and deployed, adhering to best practices in software development.
