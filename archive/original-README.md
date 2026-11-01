# Invoice Extractor Using Gemini Pro

## **UI**
<img src="images\invoice_english_ui.png" alt="Sample Image" width="400"/>
<img src="images\invoice_hindi_ui.png" alt="Sample Image" width="400"/>

## **Steps to use the app**

1. **Create a Google API Key**
   - Visit [Google AI Studio](https://aistudio.google.com/app/apikey) to create your API key.

2. **Install Requirements**
   - Install all the necessary packages from `requirements.txt` by running:
     ```sh
     pip install -r requirements.txt
     ```

3. **Run the Streamlit App**
   - Start the Streamlit app with the following command:
     ```
     streamlit run app.py
     ```

## Usage

1. Upload an invoice image.
2. Provide a prompt in the sidebar to get the answer.

The app will display the uploaded image and the response from the Gemini Pro model.
