# Parcel2Go 📦

Parcel2Go is a robust package tracking system offering a CLI and a future web interface for tracking parcels across multiple service providers like DHL. Built using Golang and AWS services, it focuses on best practices and aims to provide a seamless tracking experience.

![Parcel2Go CLI Screenshot](screenshot.png)  <!-- Replace with actual screenshot -->

## Features 🚀

- CLI-based tracking
- Multi-service provider support (DHL, FedEx, etc.)
- Real-time tracking updates
- Future plans for web interface
- User authentication via AWS Cognito
- Map visualization using Google Maps API (Upcoming)

## Tech Stack ⚙️

- **Backend**: Golang
- **CLI**: Golang
- **Frontend**: [Future]
- **Authentication**: AWS Cognito
- **Database**: [Your choice]
- **Maps**: Google Maps API

## Getting Started 🖥

### Prerequisites

- Golang
- AWS CLI
- Docker (Optional)

### Setup and Installation

1. **Clone the repository**
    ```bash
    git clone https://github.com/YourUsername/Parcel2Go.git
    ```

2. **Navigate to the project directory**
    ```bash
    cd Parcel2Go
    ```

3. **Install dependencies**
    ```bash
    go get -d ./...
    ```

4. **Run the project**
    ```bash
    go run main.go
    ```

### Testing 🧪

To run tests, use the following command:

```bash
go test ./...
```

## Usage 📚

This section provides instructions on how to use the Parcel2Go CLI.

### Tracking a Package 📦

To track a package, you can use the following command:

```bash
parcel2go track --id=PACKAGE_ID --provider=DHL
```

### User Authentication (Upcoming) 🔒

Features related to user registration, login, and authentication are in development and will be part of future updates.

## Contributing 🤝

Feel free to contribute to this project. For major changes, please open an issue first to discuss what you would like to change.

## License 📜

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Contact 💌

Marco Braun - [marco_alexander_braun@proton.me](mailto:marco_alexander_braun@proton.me)
