BizCardX: Extracting Business Card Data with OCR
Overview
BizCardX is a Streamlit web application which extracts data from business cards using Optical Character Recognition (OCR). Users can upload an image of a business card and the application uses the easyOCR library to extract relevant information from the card. The extracted information is then displayed in a user-friendly format and can be stored in a MySQL database for future reference.

The application allows users to view, modify, or delete the extracted data. It also has a user interface for uploading business card images and a table interface for displaying the extracted data. The application is created by Arshad Ayub Ahmed.

Prerequisites
To run this application, you'll need:

Python environment (Python 3.x recommended)
Streamlit, Pandas, easyOCR, PIL, cv2, matplotlib, re, mysql-connector-python libraries installed
MySQL server setup and running
Features
Home: Displays an overview of the app including technologies used and a brief description of the app.
Upload & Extract: This section allows the user to upload an image of a business card. The application then processes the image and extracts data such as company name, card holder name, designation, mobile number, email, website, area, city, state, pin code, and the image of the card.
Modify: This section allows users to select an entry from the database using a dropdown menu, which they can then update or delete. The changes are committed to the database.
How to Run
Clone the repository or download the python script.
Run the script using the command line: streamlit run app.py
The application will open in a new tab of your web browser. You can then navigate through the application, upload images of business cards, and view or modify the extracted data.
Note: Ensure your MySQL server is running and the database details in the script match your MySQL setup.
