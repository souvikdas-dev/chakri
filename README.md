# Chakri - Job Portal

**Chakri** is a modern and dynamic job portal developed using Laravel, the PHP framework for web artisans. It provides a platform where job seekers can find their dream jobs and employers can post job listings to find suitable candidates. Chakri is designed with a focus on ease of use, performance, and security.

## Features

- **User Authentication**: Secure login and registration for job seekers and employers.
- **Job Listings**: Employers can create, update, and manage job listings.
- **Job Applications**: Job seekers can apply for jobs and track their application status.
- **Search & Filter**: Advanced search and filtering options for job seekers to find relevant job listings.
- **User Profiles**: Customizable profiles for both job seekers and employers.
- **Notifications**: Email notifications for job applications and job alerts.
- **Admin Panel**: A comprehensive admin panel for managing users, jobs, and site settings.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/chakri.git
    ```

2. Navigate to the project directory:
    ```bash
    cd chakri
    ```

3. Install the dependencies:
    ```bash
    composer install
    ```

4. Copy the `.env.example` file to `.env` and configure your environment variables:
    ```bash
    cp .env.example .env
    ```

5. Generate the application key:
    ```bash
    php artisan key:generate
    ```

6. Run the migrations to set up the database:
    ```bash
    php artisan migrate
    ```

7. Seed the database with initial data (optional):
    ```bash
    php artisan db:seed
    ```

8. Serve the application:
    ```bash
    php artisan serve
    ```

## Contributing

Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the the [MIT license](https://opensource.org/licenses/MIT).

## Contact

For any inquiries or feedback, feel free to reach out at [souvikdas.dev@gmail.com].
