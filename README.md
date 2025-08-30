# IDS706_Arushi_Wk1
My repo

# IDS706 – Week 1 Project Skeleton  

[![Build & Test](https://github.com/arushi40868/IDS706_Arushi_Wk1/actions/workflows/ci.yml/badge.svg)](https://github.com/arushi40868/IDS706_Arushi_Wk1/actions)  

This repository is a **Python project skeleton** created as part of the IDS706 course. It demonstrates professional software development practices, including code structure, testing, linting, automation, and CI/CD.  

---

## Project Structure  

IDS706_Arushi_Wk1/
├── src/ # Python source code
│ └── example.py # Sample Python script
├── tests/ # Unit tests
│ └── test_example.py
├── Makefile # Commands for setup, linting, and testing
├── requirements.txt # Project dependencies
├── .github/workflows/ # CI/CD pipeline (GitHub Actions)
│ └── ci.yml
└── README.md # Project documentation

Setup Instructions

Clone the repository

git clone https://github.com/arushi40868/IDS706_Arushi_Wk1.git
cd IDS706_Arushi_Wk1


Create & activate a virtual environment

python3 -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows

Install dependencies

make setup

Run the example script:

python src/example.py

Testing

Run unit tests:

make test

Linting

Check code style with flake8:

make lint

Continuous Integration

This project uses GitHub Actions for CI/CD.
On every push or pull request, the pipeline automatically runs:

Environment setup

Dependency installation

Linting checks

Unit tests

You can view the latest build status via the badge at the top of this README.
