# Certificate Generator with Streamlit For Synapse Machine Learning Committee

Generate customized certificates using this Streamlit application. Upload a template image and a list of names, and the app will overlay the names onto the certificates. Perfect for creating personalized certificates for events, workshops, and more.

## Features

- Upload your own certificate template.
- Input a list of names to generate certificates for.
- Names are overlaid onto the template with adjustable fonts and positioning.
- Intuitive user interface built with Streamlit.
- Easily customizable to fit your design preferences.

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/Gaurang-Singhania/Synapse-Certificate-Generator.git
   cd Synapse-Certificate-Generator
   ```

2. Install the required packages:

   ```bash
   pip install streamlit pandas Pillow
   ```

3. Replace `template.png` with your own certificate template.

4. Prepare your data in a CSV file (e.g., `data.csv`), with a column named "Name" containing the names for certificates.

5. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```

6. Enter a name and see the generated certificate!

## Customization

- Adjust fonts, sizes, and colors in the `overlay_name_on_template` function.
- Modify the Streamlit app layout and style to match your preferences.

## Contributing

Contributions are welcome! If you have any feature suggestions or find any issues, please open an issue or a pull request.
