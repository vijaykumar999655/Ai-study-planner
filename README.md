# AI Study Plan Generator 📚

An intelligent application that generates personalized study plans based on subjects, topics, and available study time using Streamlit.

## 🚀 Features

- Generate personalized study plans
- Allocate study hours based on topic difficulty
- Visual progress tracking
- Export study plan as CSV
- User-friendly web interface

## 🛠️ Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

## 🚀 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/AI_StudyPlan_Generator.git
   cd AI_StudyPlan_Generator
   ```

2. **Create and activate a virtual environment**
   ```bash
   # Windows
   python -m venv venv
   .\venv\Scripts\activate
   
   # macOS/Linux
   python3 -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

## 🏃‍♂️ Running the Application

1. **Start the Streamlit app**
   ```bash
   streamlit run app.py
   ```

2. **Access the application**
   Open your web browser and navigate to:
   ```
   http://localhost:8501
   ```

## 📝 Usage

1. Enter the subjects you want to study (comma-separated)
2. Specify the total number of study hours available
3. Click "Generate Study Plan" to create your personalized plan
4. View your study plan with topic-wise hour allocation
5. Download the plan as a CSV file if needed

## 📁 Project Structure

```
AI_StudyPlan_Generator/
├── app.py              # Main Streamlit application
├── study_planner.py    # Core study plan generation logic
├── utils/
│   └── optimizer.py    # Optimization algorithms
├── data/
│   └── topics_difficulty.csv  # Topic difficulty data
└── requirements.txt    # Python dependencies
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with [Streamlit](https://streamlit.io/)
- Icons by [EmojiOne](https://www.emoji.com/)
