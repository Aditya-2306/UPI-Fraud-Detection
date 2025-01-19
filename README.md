# UPI Fraud Detection System

A web-based application for detecting fraudulent UPI transactions using machine learning algorithms and Streamlit interface.

![UPI Fraud Detection Demo](./assets/demo.gif)

## Features

- **User Authentication System**
  - Secure login and registration
  - Password hashing for security
  - Session management

- **Transaction Analysis**
  - Real-time transaction verification
  - Multiple payment type support (CASH_IN, CASH_OUT, DEBIT, PAYMENT, TRANSFER)
  - Balance verification

- **Interactive UI Components**
  - Clean and intuitive interface
  - Responsive design
  - Navigation menu with multiple sections

## Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Authentication**: SHA-256 hashing
- **Data Storage**: CSV
- **Deployment**: Ngrok for tunneling

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/upi-fraud-detection.git
cd upi-fraud-detection
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run main.py
```

## Project Structure

```
upi-fraud-detection/
├── main.py               # Main application file
├── user_data.csv         # Transaction data storage
├── user_login.csv        # User authentication data
├── requirements.txt      # Project dependencies
└── README.md
```

## Usage

1. Register/Login to the system
2. Enter transaction details:
   - Transaction amount
   - Sender and recipient information
   - Balance details
   - Transaction type
3. Click "Predict" to analyze the transaction
4. View results in the Analysis section

## Features in Detail

### Home Page
- Transaction detail input form
- Real-time validation
- Data persistence

### Analysis Section
- Transaction pattern analysis
- Fraud detection algorithms
- Visual representations

### Login System
- Secure user authentication
- Password encryption
- Session management

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## Team

- Sarli 
- Kaushal Asiwal 
- Prem Dev Singh 
- Aditya Pandey 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Project developed as part of B.Tech Project at NSUT
- Streamlit for the amazing web framework
- Contributors and maintainers
