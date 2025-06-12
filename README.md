# 🤖 DFD-AI Generator

This project was built as part of my master’s thesis to explore how artificial intelligence can be used to automatically generate Data Flow Diagrams (DFDs) for smart systems. It uses a fine-tuned OpenAI model that takes a natural language description as input and outputs a complete DFD diagram.

---

## 📁 What's Inside?

- `main.py`: The main script you run to generate diagrams.
- `dfd_utils.py`: Contains utility functions to help build and render DFDs.
- `requirements.txt`: A list of Python libraries needed for the project.
- `generated_dfd.dot`: A sample Graphviz file output.
- `.env`: **Not included**. You'll need to create this file with your OpenAI API key.

---

## 🧑‍💻 How to Download and Run This Project

Here’s how you can set it up on your own laptop in a few easy steps:

---

### ✅ 1. Download the project

- Go to this repository
- Click the green **“Code”** button → choose **“Download ZIP”**
- Extract the ZIP file somewhere on your computer (e.g., Desktop)

---

### ✅ 2. Open a terminal in that folder

If you're using Windows:
- Right-click inside the folder → select **"Open in Terminal"**

---

### ✅ 3. (Optional but recommended) Create a virtual environment

python -m venv venv
venv\Scripts\activate

✅ 4. Install the required Python packages
pip install -r requirements.txt

✅ 5. Install Graphviz
Windows:
Download and install from: https://graphviz.org/download
(During installation, make sure to check “Add Graphviz to system PATH”)

Ubuntu:
sudo apt install graphviz

✅ 6. Create your .env file
Inside the same project folder, create a new file called .env and add the following line:

OPENAI_API_KEY=your_openai_key_here

✅ 7. Run the tool
Once everything is set up, run:
python main.py
You’ll be asked to enter a smart system description.
The tool will then generate:

generated_dfd.dot: the raw Graphviz output

generated_dfd.png: the rendered image

All files will be saved in the outputs/ folder.


📝 Notes
You need an internet connection to access the OpenAI API.

This tool was developed for academic and research purposes.

You can modify the description or prompts to explore different systems.

👩‍💻 Author
Sumayah Najah Sabea Alaasam
Master’s Thesis – Software Engineering
Mälardalens University, Sweden


