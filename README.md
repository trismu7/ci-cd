# CI/CD Demo Project

This is a simple web application demonstrating Continuous Integration and Continuous Deployment (CI/CD) practices using GitHub Actions.

## Features

- Flask web application
- Automated testing with pytest
- CI/CD pipeline with GitHub Actions
- Modern, responsive UI

## Setup

1. Clone the repository:

```bash
git clone <your-repository-url>
cd cicd-demo
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
python app.py
```

5. Run tests:

```bash
pytest
```

## CI/CD Pipeline

The project includes a GitHub Actions workflow that:

1. Runs tests on every push and pull request
2. Deploys the application when changes are pushed to the main branch

## Project Structure

```
.
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── test_app.py        # Test cases
├── templates/         # HTML templates
│   └── index.html    # Main page template
└── .github/
    └── workflows/    # GitHub Actions workflows
        └── ci-cd.yml # CI/CD pipeline configuration
```

## Contributing

1. Create a new branch for your feature
2. Make your changes
3. Run tests locally
4. Create a pull request

## License

MIT License
