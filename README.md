# Malcolm's Anatomy: VerifyMed

**VerifyMed** is a hybrid mobile and web application designed to authenticate medications using barcode and QR code scanning. The app helps users verify the authenticity of drugs, providing alerts for counterfeit or unregistered products and additional drug information.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Drug Scanning**: Utilize the mobile camera to scan barcodes/QR codes on drug packaging.
- **Real-Time Verification**: Cross-check drug information with a NAFDAC (or similar) database to verify authenticity.
- **User Alerts**: Notify users if a drug is counterfeit or unregistered.
- **Drug Information**: Provide additional details about the drug, such as dosage, expiration date, and side effects.

## Technologies

- **Backend**: 
  - Python (Flask/Django)
  - Database (PostgreSQL/MySQL)
    
- **Mobile App**: 
  - Kivy
  - Barcode scanning libraries (e.g., `zbarlight`)
    
- **Web App**: 
  - React
  - Barcode scanning libraries (e.g., `react-qr-reader`)
    
- **Version Control**: Git
  
- **Deployment**: Heroku/AWS/Vercel/Netlify

## Installation

### Backend

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/malcolms-anatomy-verifymed.git
   ```
2. Navigate to the backend directory:
   ```bash
   cd malcolms-anatomy-verifymed/backend
   ```
3. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
4. Activate the virtual environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
5. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Mobile App

1. Navigate to the mobile directory:
   ```bash
   cd malcolms-anatomy-verifymed/mobile
   ```
2. Install Kivy and other dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Web App

1. Navigate to the web directory:
   ```bash
   cd malcolms-anatomy-verifymed/web
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

## Usage

### Backend

1. Start the backend server:
   ```bash
   flask run
   ```
2. Access the API at `http://localhost:5000`.

### Mobile App

1. Run the mobile app:
   ```bash
   python main.py
   ```

### Web App

1. Start the web server:
   ```bash
   npm start
   ```
2. Access the web app at `http://localhost:3000`.

## API Endpoints

- **GET /api/drugs**: Retrieve a list of drugs from the database.
- **POST /api/verify**: Verify a drug using its barcode/QR code.
- **GET /api/drugs/:id**: Retrieve detailed information about a specific drug.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message here"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, please contact:

- **Malcolm Chikadibia Iheremelam**  
  Email: [admin@malcolmsanatomy.com.ng](mailto:admin@malcolmsanatomy.com.ng)  
  Website: [Malcolm's Anatomy](https://malcolmsanatomy.com.ng)

---

Thank you for checking out **Malcolm's Anatomy: VerifyMed**! Your contributions and feedback are highly appreciated.
```
