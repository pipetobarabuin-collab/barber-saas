# Barber Shop SaaS Project Documentation

## Project Structure

The Barber Shop SaaS project is structured to allow for easy navigation and development. Below is the breakdown of the main directories and their purposes:

- **/src**: Contains the source code for the application.
- **/public**: Holds the static files such as images, fonts, and stylesheets.
- **/tests**: Includes unit and integration tests.
- **/config**: Configuration files, including environment variables and database configurations.

## Installation

To install the Barber Shop SaaS project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/<your-github-username>/barber-saas.git
   cd barber-saas
   ```
2. Install the dependencies:
   ```
   npm install
   ```
3. Set up the environment variables. Create a `.env` file based on the `.env.example` provided in the repository:
   ```
   cp .env.example .env
   ```
4. Start the development server:
   ```
   npm run dev
   ```

## Features

- **User Management**: Allows barbers to manage their profiles and customers.
- **Appointment Scheduling**: Customers can schedule, reschedule, and cancel appointments.
- **Payment Processing**: Integration with payment gateways for secure transactions.
- **Reporting**: Barbers can generate reports on appointments and earnings.
- **Notifications**: Email and SMS notifications for appointments and promotions.

For detailed feature descriptions and usage guidelines, refer to the `/docs` directory.

## Contributing

Contributions are welcome! Please read the `CONTRIBUTING.md` file for guidelines on how to contribute to this project.