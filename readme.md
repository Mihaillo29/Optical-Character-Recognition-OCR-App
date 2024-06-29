
# Steps to Run the Application Locally

1. **Create a copy of the project.**

2. **Open Command Prompt and navigate to the project directory:**
   Change your current path to the folder where you can find the `app.py` file.

3. **Create a virtual environment:**
   ```bash
   conda create -name <environment name>
   ```

4. **Activate the environment:**
   ```bash
   conda activate <environment name>
   ```

5. **Install Tesseract:**
   Download and install Tesseract using the Windows installer available at: [Tesseract GitHub](https://github.com/UB-Mannheim/tesseract/wiki).

6. **Note the Tesseract installation path:**
   The default installation path is `C:\Program Files\Tesseract-OCR`. This may change, so please check the actual installation path.

7. **Set the Tesseract path in your code:**
   ```python
   pytesseract.pytesseract.tesseract_cmd = r'C:\Program Files\Tesseract-OCR\tesseract.exe'
   ```

8. **Install the required dependencies:**
   ```bash
   python -m pip install -r requirements.txt
   ```

9. **Run the application:**
   ```bash
   python app.py
   ```
   You will get a URL; copy it and paste it into your browser.

10. **Test with sample data:**
    Use the `sample_data` folder where you can find images to test.
```
