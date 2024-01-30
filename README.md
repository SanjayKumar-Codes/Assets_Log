# Asset Management System 🖥️📊

Welcome to the Asset Management System repository! This web application facilitates organizations in requesting and obtaining approval for needed assets, while also providing robust features for tracking, managing assets, identification, and maintenance scheduling.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Asset Management System is a comprehensive solution for organizations seeking effective control and visibility over their assets. It streamlines the asset request process, ensures efficient approval workflows, and provides tools for asset tracking, identification, and maintenance scheduling.

## Features

- **Asset Request**: Seamlessly request needed assets from higher authorities.
- **Approval Workflow**: Obtain approval for asset requests through a structured workflow.
- **Asset Tracking**: Keep a detailed record of all organization assets.
- **Identification**: Easily identify and categorize assets for efficient management.
- **Maintenance Scheduling**: Plan and schedule maintenance activities to ensure asset longevity.

## Technologies

This project utilizes the following technologies:

- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Backend**: Python, Flask
- **Database**: SQLite (Can be upgraded to a more robust solution for larger deployments)
- **Authentication**: Flask-Security
- **Approval Workflow**: Flask-Approve
- **Reporting**: Matplotlib (for basic reports)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/asset-management-system.git
cd asset-management-system
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Set up the database:

```bash
python manage.py create_db
```

## Usage

1. Run the application:

```bash
python manage.py runserver
```

2. Access the application in your web browser at `http://localhost:5000`.

3. Log in using your credentials and start managing assets and requests.

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/new-feature`)
3. Make your changes and commit them (`git commit -m 'Add new feature'`)
4. Push the changes to your branch (`git push origin feature/new-feature`)
5. Open a pull request

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as needed.

Optimize your asset management with the Asset Management System! 🚀
