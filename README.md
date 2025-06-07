# JITkau
 Just-in-time Bug Prediction for DVAD81, vt25 Project in Automated Software Engineering 46027

# Bug Prediction Jupyter Notebook

This project uses Python and Jupyter Notebook to predict buggy commits using machine learning models.  
All required libraries are listed in `requirements.txt`.

## Installation

1. **Clone the repository or download the notebook and requirements file.**

2. **Create a virtual environment (recommended):**
    ```
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    ```

3. **Install the required packages:**
    ```
    pip install -r requirements.txt
    ```

4. **Install Jupyter Notebook (if not already included):**
    ```
    pip install notebook
    ```

5. **Launch Jupyter Notebook:**
    ```
    jupyter notebook
    ```

6. **Open the notebook file (.ipynb) and start exploring!**


## Opening the Notebook in Visual Studio Code

1. **Install Visual Studio Code**  
   Download and install [Visual Studio Code](https://code.visualstudio.com/).

2. **Install Required Extensions**  
   Open VS Code and install the following extensions from the Extensions view (`Ctrl+Shift+X`):
   - **Python** (by Microsoft)
   - **Jupyter** (by Microsoft)

3. **Open Your Project Folder**  
   Use `File > Open Folder...` to open the folder containing your notebook and requirements files.

4. **Activate Your Virtual Environment**  
   Open a terminal in VS Code and activate your virtual environment:
   - On macOS/Linux:  
     ```
     source venv/bin/activate
     ```
   - On Windows:  
     ```
     venv\Scripts\activate
     ```

5. **Select the Python Interpreter**  
   Press `Ctrl+Shift+P` to open the Command Palette, type `Python: Select Interpreter`, and choose the interpreter from your virtual environment.

6. **Open the Notebook**  
   - Locate your `.ipynb` notebook file in the Explorer sidebar and click to open it.
   - The notebook will open in the native VS Code Notebook Editor.

7. **Run Code Cells**  
   - Use the "Run" button next to each cell or press `Shift+Enter` to execute code.
   - Ensure the correct Python kernel (your virtual environment) is selected at the top right of the notebook editor.

For more details, see the [official VS Code Jupyter documentation](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)[1][6][7].