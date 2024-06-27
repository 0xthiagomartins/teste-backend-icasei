# ms-rails

## Setup Instructions

### Prerequisites
- Ruby (version 3.0.0 or higher)
- Rails (version 6.1 or higher)
- SQLite3
- Kafka

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/0xthiagomartins/teste-backend-icasei.git
   cd teste-backend-icasei/ms-rails
   ```

2. **Install dependencies**
    ```bash
   bundle install
    ```

3. **Set environment variables**
Create a `.env` file with the following:
    ```bash
    DATABASE_URL=sqlite3://localhost/db/development.sqlite3
    KAFKA_BROKER=localhost:9092
    ```

4. **Setup the database**
    ```bash
   rails db:create db:migrate
    ```

5. **Run the application**
    ```bash
   rails server
    ```

6. **Access the service**
The Rails microservice will be running at `http://localhost:3000`.
