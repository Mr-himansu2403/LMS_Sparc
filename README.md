# SPARC LMS (Learning Management System)

A modern Learning Management System built with Flask backend and HTML/CSS frontend.

## 🚀 Features

- Clean and responsive web interface
- Flask-based backend architecture
- User authentication system (Login/Register)
- Modular frontend and backend structure

## 📁 Project Structure

```
LMS_Sparc/
├── backend/
│   ├── app.py              # Main Flask application
│   ├── requirements.txt    # Python dependencies
│   └── templates/
│       └── index.html      # Flask templates
├── frontend/
│   ├── index.html          # Frontend HTML
│   └── style.css           # Styling
└── README.md
```

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.7+
- pip (Python package manager)
- Git

### Local Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Mr-himansu2403/LMS_Sparc.git
   cd LMS_Sparc
   ```

2. **Set up Python virtual environment**
   ```bash
   # On Windows
   py -m venv venv
   venv\Scripts\activate
   
   # On macOS/Linux
   python -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   cd backend
   pip install -r requirements.txt
   ```

4. **Run the application**
   ```bash
   # On Windows
   py app.py
   
   # On macOS/Linux
   python app.py
   ```

5. **Access the application**
   Open your browser and navigate to `http://localhost:5000`

## 🔧 Development

### Backend Development
- The Flask application is located in `backend/app.py`
- Templates are stored in `backend/templates/`
- Add new routes and functionality in the Flask app

### Frontend Development
- Static frontend files are in the `frontend/` directory
- Modify `frontend/style.css` for styling changes
- Update HTML templates as needed

## 📝 API Endpoints

Currently available routes:
- `GET /` - Home page

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👥 Authors

- **Mr-himansu2403** - *Initial work* - [GitHub Profile](https://github.com/Mr-himansu2403)

## 🐛 Issues

If you encounter any issues, please report them on the [Issues page](https://github.com/Mr-himansu2403/LMS_Sparc/issues).

## 🔮 Future Enhancements

- [ ] User authentication system
- [ ] Course management
- [ ] Student enrollment
- [ ] Assignment submission
- [ ] Grade tracking
- [ ] Discussion forums
- [ ] Video content support
- [ ] Mobile responsiveness improvements

---

**Happy Learning! 📚**