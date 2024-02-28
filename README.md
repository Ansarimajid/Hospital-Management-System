# Hospital Bed Management System

The Hospital Bed Management System is designed to efficiently manage and monitor the availability and allocation of beds within a hospital facility. This system utilizes a stack of technologies for both the frontend and backend to provide a user-friendly interface for hospital staff to manage bed allocation effectively.

## Tech Stack

### Frontend
- HTML5
- CSS3
- jQuery
- Bootstrap 4

### Backend
- Django framework

### Database
- SQLite

## Local Setup

1. Clone repository:
    ```bash
    git clone https://github.com/Ansarimajid/Hospital-Management-System.git
    ```

2. Setup virtual environment:
    ```bash
    cd Hospital-Management-System
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Run Django development server:
    ```bash
    python manage.py runserver
    ```

5. Visit `http://127.0.0.1:8000` in your web browser to access the Hospital Bed Management System.

## Features

- **Bed Allocation**: Allows hospital staff to assign and manage the allocation of beds for patients.
- **Bed Availability**: Provides real-time updates on bed availability within the hospital.
- **Patient Information**: Stores and displays relevant information about patients occupying beds.

## Usage

Upon accessing the system via the provided local setup, users (hospital staff) can perform the following actions:

- Add new patients to the system.
- Allocate available beds to patients.
- Update patient information as needed.
- View and manage bed availability.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).
