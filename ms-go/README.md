# ms-go

## Setup Instructions

### Prerequisites
- Go (version 1.16 or higher)
- MongoDB
- Kafka

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/0xthiagomartins/teste-backend-icasei.git
   cd teste-backend-icasei/ms-go
    ```

2. **Install dependencies**
    ```bash
   go mod tidy
    ```

3. **Set environment variables**
Create a `.env` file with the following:
    ```bash
    MONGO_URI=mongodb://localhost:27017/products
    KAFKA_BROKER=localhost:9092
    ```

4. **Run the application**
go run main.go

5. **Access the service**
The Go microservice will be running at `http://localhost:8080`.