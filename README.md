# Agricultural Crop Recommendation System

A web-based application that recommends the best crop to cultivate based on soil and environmental parameters, and suggests suitable fertilizers for the recommended crop.

## Features
- User registration and login system
- Crop recommendation based on input parameters (Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall)
- Fertilizer suggestions for the recommended crop
- Informative overview and about us pages
- Modern UI with Bootstrap and custom CSS

## Project Structure
```
├── main.py
├── Crop_recommendation.csv
├── models/
│   ├── model.pkl
│   ├── minmaxscaler.pkl
│   └── standscaler.pkl
├── static/
│   ├── akki.css
│   ├── d.json  
│   ├── pic.jpg
│   ├── plant.jpg
│   
└── templates/
    ├── index.html
    ├── login.html
    ├── register.html
    ├── overview.html
    └── about_us.html
```

## Installation
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/agricultural-crop-recommendation.git
   cd agricultural-crop-recommendation
   ```
2. **Install dependencies:**
   ```sh
   pip install flask scikit-learn numpy
   ```
3. **Run the application:**
   ```sh
   python main.py
   ```
4. **Access the app:**
   Open your browser and go to `http://localhost:3002`

## Usage
- Register a new user or log in with existing credentials.
- Enter soil and environmental parameters on the main page.
- Get crop and fertilizer recommendations instantly.

## Data & Model
- The model is trained using the data in `Crop_recommendation.csv`.
- Pre-trained model and scalers are stored in the `models/` directory.
- Fertilizer information is loaded from `static/d.json`.

## Screenshots
Add screenshots of the UI (index, login, register, overview, about us) here.

## Contributing
Feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.

