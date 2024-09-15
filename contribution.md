## Installation

To install my-project

1. **Clone the Repository**
First, clone the project repository from your version control system (e.g., GitHub). Open your terminal or command prompt and run:

```bash
git https://github.com/Avinash24R/web-Scrapper.git
```

2. **Navigate to the Project Directory**
Change to the project directory:

```bash
cd web-scrappe
```
3. **Create a Virtual Environment**


For Windows:

```bash
python -m venv web_scarpper
```
**Activate the Environment**
```
.\web_scrapper\Scripts\Activate.ps1

```
4. **Install Required Packages**


```bash
pip install -r requirements.txt
```
5. **Check for ollama in your local host**
Go to command prompt
```bash
ollama list
```
you should have llama 3.1

if not than pull llama3
```bash
ollama pull llama3
```
6. **Run the Application**
```bash
streamlit run main.py
```
