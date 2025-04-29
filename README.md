
## Overview

**Fake Data Generator** is a Streamlit-based application that enables users to generate realistic synthetic data using the **Faker** library. Users can customize the number of records, select specific locales, and define which fields to include. The generated data can be downloaded in either CSV or JSON format.

## Usage Instructions

1. **Install Requirements:**  
   First, install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Application:**  
   Use the following command to start the Streamlit app:

   ```bash
   streamlit run app.py
   ```

3. **Access the Interface:**  
   After launching, your browser will open to the Streamlit interface (usually at [http://localhost:8501](http://localhost:8501)).

4. **Generate Data:**  
   - Choose between **Home** (predefined profile fields) or **Customize** (select your own fields).
   - Select the number of records and desired locale(s).
   - Choose the output format (CSV or JSON).
   - Click the download link to save the generated data.

## Key Features

- **Customizable Fake Data Generation:**  
  Generate synthetic profiles with selected fields, locales, and record counts.

- **Multiple Output Formats:**  
  Download generated data in CSV or JSON formats.

- **Interactive UI:**  
  Built using [Streamlit](https://streamlit.io/) for a responsive and user-friendly interface.
