# EduGenius – AI-Powered Tutoring Platform

---

## Overview

EduGenius is a cutting-edge AI-powered educational platform designed to enhance student learning through personalized quizzes, real-time doubt resolution, and an intuitive, engaging user interface. Built to address critical gaps in traditional learning platforms, EduGenius leverages advanced machine learning and natural language processing techniques to provide seamless, personalized education at scale.

---

## Table of Contents

- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Development and Contribution](#development-and-contribution)
- [Testing](#testing)
- [License](#license)

---

## Features

### 1. Personalized Quiz Generation

- AI-driven generation of customized quizzes based on user learning progress and knowledge gaps.
- Real-time adaptive difficulty adjustments.
- Comprehensive performance tracking and analytics.

### 2. Real-time Doubt Resolution

- Instant query resolution leveraging advanced Large Language Models (LLMs).
- OCR-based image query submission allowing students to easily upload handwritten notes and textbook images.
- Seamless, automated explanations post-quiz to enhance understanding.

### 3. Interactive and User-Friendly Interface

- Intuitive design aimed at minimizing cognitive load and enhancing user engagement.
- Multilingual support for increased accessibility.
- Integrated feedback and notification system for continual improvement.

### 4. Curated Learning Resources

- Integration with YouTube API and customized web scrapers for curated educational videos.
- Tailored content recommendations based on quiz performance and query patterns.

---

## Technology Stack

- **Frontend:** React.js, Tailwind CSS, Bootstrap, HTML5
- **Backend:** Node.js, Flask, Python
- **AI and ML:** LangChain, OpenAI GPT models, OCR (Tesseract), TensorFlow
- **Database:** MongoDB, PostgreSQL
- **Cloud Infrastructure:** AWS (Lambda, EC2, S3, DynamoDB)
- **Tools and Services:** Google Translate API, YouTube API

---

## Installation

Follow these instructions to set up EduGenius on your local environment:

### Prerequisites

- Git
- Node.js & npm
- Python 3.8 or higher
- MongoDB and PostgreSQL
- AWS account with access keys configured

### Steps

```bash
# Clone repository
git clone https://github.com/Arbiter09/EduGenius.git
cd EduGenius

# Setup frontend
cd frontend
npm install

# Setup backend
cd ../backend
pip install -r requirements.txt

# Configure environment variables
cp .env.example .env
# Update .env file with required keys and configurations

# Start services
npm run start-frontend
npm run start-backend
```

---

## Usage

Once EduGenius is running, access it via your browser:

```bash
http://localhost:3000
```

- Create a user account or log in to the existing one.
- Navigate through personalized quizzes or directly upload images for doubt resolution.
- Track performance metrics through the user dashboard.

---

## Development and Contribution

We encourage contributions to improve EduGenius. To contribute:

- Fork this repository.
- Create your feature branch (`git checkout -b feature/AmazingFeature`).
- Commit your changes (`git commit -m 'Add amazing feature'`).
- Push to the branch (`git push origin feature/AmazingFeature`).
- Open a Pull Request.

### Best Practices

- Write clear and concise code with comments.
- Ensure all tests pass before submitting a pull request.
- Maintain code readability and consistency throughout.

---

## Testing

EduGenius includes a comprehensive test suite to maintain robustness:

### Running Tests

```bash
# Frontend testing
npm run test

# Backend testing
pytest tests/
```

### Automated Testing

- CI/CD integrated via GitHub Actions.
- Automated unit tests, integration tests, and linting checks.

---

## License

Distributed under the MIT License. See `LICENSE` file for more information.

---

## Contact

For questions, issues, or collaboration, please contact:

- **Jas Shah**: [jasshah9513@gmail.com]
- **Project Link**: [https://github.com/Arbiter09/EduGenius.git]

---

2025 EduGenius
