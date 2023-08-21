# Art-Auction-Backend

This README provides instructions on how to set up your development environment and run the Flask application.

## Getting Started

### Prerequisites

- Python 3.9.10+
- Git

### Clone the Repository

Clone this repository to your local machine using the following command:

```sh
git clone https://github.com/CHA0sTIG3R/Art-Auction-Backend.git
cd Art-Auction-Backend
```

## Set Up Virtual Environment

1. **Navigate to the repository directory:**

   ```sh
   cd your-repo
   ```

2. **Create a virtual environment:**

   - On Windows:

     ```sh
     py -m venv venv
     ```

   - On macOS and Linux:

     ```sh
     python3 -m venv venv
     ```

3. **Activate the virtual environment:**

   - On Windows:

     ```sh
     env\Scripts\activate
     ```

   - On macOS and Linux:

     ```sh
     source env/bin/activate
     ```

## Install Dependencies

While the virtual environment is active, install the project dependencies using pip:

```sh
pip install -r requirements.txt
```

## Run the Flask App

With the virtual environment still active, you can start the Flask app:

```sh
flask run
```

The app will be accessible at [http://127.0.0.1:5000/](http://127.0.0.1:5000/).
