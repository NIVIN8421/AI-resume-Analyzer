

**<img src="https://github.com/user-attachments/assets/76906dbc-343d-4267-ace5-048d428fff42" width="20px"> Next-Level Features for Success:**  
1. 🕵️ **Deep Resume Analysis:**  
   - 🛡️ ATS Compatibility Score  
   - 🔑 Keyword Gap Analysis  
   - 🧩 Role-specific Feedback  
   - 📊 Skills Gap Breakdown  

2. 🎨 **AI-Powered Resume Builder:**  
   - **Themes that Shine** (Modern, Minimal, Professional, Creative)  
   - **Smart Content Suggestions**  
   - **ATS-Optimized Formatting**  
   - **Customizable Sections**  

3. 🤖 **AI Optimization Engine:**  
   - 💡 Keyword Highlighting  
   - ✍️ Content Enhancement Tips  
   - 🌟 Industry-Specific Insights  

**🎉 Why Use Smart Resume AI?**  
Get real-time feedback, boost your resume's impact, and maximize your chances of getting shortlisted—all with a sleek and intuitive interface.  



## <img src="https://github.com/user-attachments/assets/0cefad05-58a9-4aa0-a070-f75a0c9b0353" height="32px">  Tech Stack 
<details>
  <summary>🌐 Frontend</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**Streamlit**](https://streamlit.io/)   | Builds interactive and user-friendly web apps for resume analysis.     |  
| [**HTML**](https://developer.mozilla.org/en-US/docs/Learn/HTML)  | Provides the basic structure for web pages.                             |  
| [**CSS**](https://developer.mozilla.org/en-US/docs/Web/CSS)      | Adds styling and layouts to the frontend.                               |  
| [**JavaScript**](https://developer.mozilla.org/en-US/docs/Learn/JavaScript) | Enables interactivity and dynamic behavior for the web pages.          |  

</details>

<details>
  <summary>⚙️ Backend</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**Streamlit**](https://streamlit.io/)   | Handles backend logic and integrates machine learning models.           |  
| [**Python**](https://www.python.org/)    | Provides core programming language for implementing functionalities.    |  

</details>

<details>
  <summary>🗄️ Database</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**SQLite3**](https://www.sqlite.org/index.html) | Stores and retrieves resume data for efficient processing.             |  

</details>

<details>
  <summary>📦 Modules</summary>

| **🌟 Technology**    | **💼 Role**                                                             |  
|-----------------------|-------------------------------------------------------------------------|  
| [**spaCy**](https://spacy.io/)          | Enhances NLP for keyword analysis and ATS compatibility checks.        |  
| [**Python-docx**](https://python-docx.readthedocs.io/en/latest/)    | Enables Word document editing for resume customization.                |  
| [**PyPDF2**](https://pypdf2.readthedocs.io/en/latest/)         | Processes PDF files for extracting and analyzing resumes.              |  
| [**scikit-learn**](https://scikit-learn.org/)   | Drives machine learning models for resume optimization.                |  
| [**Plotly**](https://plotly.com/)         | Creates interactive charts for skills gap and keyword analysis.        |  
| [**NLTK**](https://www.nltk.org/)         | Provides tools for tokenization, stemming, and text preprocessing in NLP. |  
| [**openpyxl**](https://openpyxl.readthedocs.io/en/stable/)      | Facilitates reading, writing, and modifying Excel files for data visualization and export. |  

</details>

## 💡 **How It Works**  

1. **Upload or Start from Scratch**  
   - Import your resume in **PDF/Word** or create one from scratch with our AI-powered builder.  

2. **Analyze Your Resume**  
   - **ATS Compatibility**: Ensure your resume meets recruiter expectations.  
   - **Keyword Insights**: Find and fill gaps in your content.  
   - **Skills Gap Analysis**: Discover key skills missing for your target role.  

3. **Build a Stunning Resume**  
   - Select from **4 unique templates** and customize sections like skills, achievements, or hobbies.  

4. **Download & Apply**  
   - Export your resume in **PDF** format, ready for submission.  This project has evolved with significant enhancements to its resume analysis capabilities:


Follow these steps to run Smart Resume AI:  

#### **Setup Instructions** 🛠️

Follow the steps below to set up and run the **Smart AI Resume Analyzer** on your local machine.

1. **Clone the repository:**

Open a terminal and run:

   ```bash
   git clone <your-fork-or-repo-url>.git
   cd Smart-AI-Resume-Analyzer
   ```

2. **Create a Virtual Environment(Optional)**

Set up a virtual environment to manage dependencies:

```bash
python -m venv venv
```

#### **Activate the Virtual Environment:**

- **Windows:**
  ```bash
  python -m venv venv
  ```
- **MacOS & Linux:**
  ```bash
  source venv/bin/activate
  ```

3. **Install dependencies:**

Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

4. **Download the spaCy model:**

Ensure that the necessary NLP model is installed:

   ```bash
   python -m spacy download en_core_web_sm
   ```
   
``Congratulations 🥳😱 your set-up 👆 and installation is finished 🥳😱``


5. **Configure Environment Variables (Mandatory for AI-Analyzer Functionality):**

To enable access to the **Gemini API** used by the AI Resume Analyzer, you need to set up environment variables securely.

#### ✅ Step-by-Step:

1. **Create a `.env` file** inside the `utils/` directory.
2. **Paste your Google Gemini API key** in the following format:

#### 📄 Example content for `utils/.env`:
```env
GOOGLE_API_KEY=your_google_gemini_api_key
```

#### <img src="https://assets.codepen.io/1468070/Google+G+Icon.png" alt="Google LOGO" width="1.6%" /> Get your Gemini API Key:
Visit  **[Google AI Studio – Gemini API Access](https://aistudio.google.com/app/apikey)** 👉 Grab and use your **own API key** — Since Mine One Have Usage Limits.


6. **Run the application:**

Start the application using Streamlit:

   ```bash
   streamlit run app.py
   ```

<details>
  <summary>📁 Folder Structure After Adding <code>.env</code></summary>

> 🔐 **Important:**  
> - **Do not commit your `.env` file** to version control (e.g., GitHub). It should be listed in `.gitignore`.
> - If you're collaborating, you can provide a safe `.env.example` file with dummy data.

  <div align="center">  
    <table>
      <tr>
        <td align="center"><b>🗂️ Folder Structure Preview 1</b></td>
        <td align="center"><b>🗂️ Folder Structure Preview 2</b></td>
      </tr>
      <tr>
        <td>
          <img src="https://github.com/user-attachments/assets/a6636ec0-f1e6-45ed-90f5-583ecbf7f67f" alt="Folder Structure Preview 1" height="350px" width="600px">
        </td>
        <td>
          <img src="https://github.com/user-attachments/assets/10fea5d7-5b9f-491e-871f-75a9ab716ebb" alt="Folder Structure Preview 2" height="355px" width="600px">
        </td>
      </tr>
    </table>
  </div>
  

</details>

## Admin Login Credentials

### 🔹 New Login Credentials:
   - **Username:**
```python3
admin@gmail.com
```
   - **Password:**
```python3
admin123
```

### 🔹 Admin Panel Access:
   - The **Admin Section** will be visible **only after login**, right below the **Dashboard** section.



