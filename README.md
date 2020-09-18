# Student Performance Prediction

- [Student Performance Prediction](#student-performance-prediction)
  - [Problem Statement](#problem-statement)
  - [Introduction](#introduction)
  - [How To Run](#how-to-run)
  - [Contributors](#contributors)
  - [Contributing](#contributing)
  - [License](#license)
  - [Project status](#project-status)
  - [Author](#author)

> Student's Performance Prediction Using Machine Learning Approach

<img height="350px" width="500px" src="https://swingeducation.com/wp-content/uploads/2018/08/How-to-Increase-Student-Performance-with-High-Expectations.jpg">

## Problem Statement 

Problem Statement - Predicting the Students performance using Machine learning based on their previous data and results for early prevention.

## Introduction

## How To Run

- Install python3
  - pip install pipenv

Go to Base-Directory run following commands to start server

```bash
pipenv install
pipenv shell
python manage.py runserver
```

```bash
# migrate database for user/admin login
python manage.py migrate 
# to create admin user
python manage.py createsuperuser
```

visit <https://localhost:8000> on your pc

## Contributors

- [Deepak Raj](https://github.com/shubham5351) -  Django backend & Deployment
- [Shubham Pawar](https://github.com/shubham5351) - Maintainer, ML Modeling and Analyis
- [Deepak Kumar](https://github.com/dkpcs92) - ML Modeling and analysis
- []() - Frontend Part

## Contributing

Before submitting a bug, please do the following:

Perform basic troubleshooting steps:

- Make sure you are on the latest version. If you are not on the most recent version, your problem may have been solved already! Upgrading is always the best first step.
- Try older versions. If you are already on the latest release, try rolling back a few minor versions (e.g. if on 1.7, try 1.5 or 1.6) and see if the problem goes away. This will help the devs narrow down when the problem first arose in the commit log.
- Try switching up dependency versions. If the software in question has dependencies (other libraries, etc) try upgrading/downgrading those as well.

## License

For open source projects,Under MIT License.

## Project status

## Author

- Project : Student Performance Prediction
- Author  : Py-Contributors
- Language : Python
- Github : <https://github.com/Py-Contributors/>
