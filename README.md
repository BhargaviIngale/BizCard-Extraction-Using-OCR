# 📇 BizCardX: Extracting Business Card Data with OCR

BizCardX is a Streamlit web application that allows users to upload images of business cards and automatically extract key information using **easyOCR**. The app extracts data such as name, designation, phone number, email, website, address, and more. Users can view, edit, update, and delete this data through a clean and interactive interface, with all information stored in an **SQL database** along with the original card image.

---

## 🌐 Domain

**Document Processing, Business Management, Automation**

---

## 🚀 Features

- 📤 Upload business card images
- 🧠 Extract key details using OCR (easyOCR)
- 🖼️ Store original image in database
- 🗃️ View, update, and delete entries via Streamlit UI
- 🧩 Clean and modular Python code
- 💾 SQLite/MySQL database integration
- ✅ Streamlined UI for smooth user experience
- 🔐 Scalable, maintainable, and easily extendable

---

## 🧑‍💻 Technologies Used

- Python
- Streamlit
- easyOCR
- OpenCV
- SQLite/MySQL
- Pandas
- PIL (Python Imaging Library)

---

## 🔍 Project Objectives

1. **Image Upload & OCR Integration**  
   Upload a business card image and extract the following:
   - Company Name
   - Cardholder Name
   - Designation
   - Mobile Number
   - Email Address
   - Website URL
   - Area, City, State, and Pin Code

2. **Text Extraction**  
   Use `easyOCR` and `OpenCV` for text detection and enhancement.

3. **Interactive Streamlit App**  
   - Show extracted data in an editable format.
   - Use file uploader, buttons, and input fields for user interaction.

4. **Database Operations**  
   - Store extracted info and card image using SQLite/MySQL.
   - Perform Update and Delete directly via the GUI.

5. **Data Management Interface**  
   - View all entries in a table format.
   - Select specific records to update or delete.

---

## 🗃️ Data Source

- **Input**: Uploaded business card images (`.jpg`, `.jpeg`, `.png`)
- **Storage**: Text data + image path stored in a relational database

---

## 🎯 Learning Outcomes

By working on the **BizCardX** project, we gain practical experience and insights in the following areas:

###  1. Optical Character Recognition (OCR)
- Understand the fundamentals of OCR using **easyOCR**.
- Apply image preprocessing techniques (e.g., grayscale conversion, thresholding) to enhance OCR accuracy.
- Extract structured text data from unstructured image input.

###  2. Image Processing
- Use **OpenCV** to manipulate and enhance image quality for better text detection.
- Learn to apply operations like resizing, denoising, and bounding box detection.

###  3. Streamlit Web App Development
- Build an interactive web-based UI using **Streamlit**.
- Implement file uploads, form inputs, and dynamic content display.
- Handle session state and user-triggered events (like buttons).

###  4. Backend & Database Integration
- Use **SQLite/MySQL** to design and manage relational databases.
- Perform **CRUD operations** (Create, Read, Update, Delete) through Python.
- Store both image paths and extracted data persistently.

###  5. End-to-End Application Building
- Integrate frontend (Streamlit), backend (Python), and database into a single application.
- Modularize code into functional blocks for maintainability and scalability.


###  6. Version Control & Documentation
- Use **GitHub** for version control and collaborative development.
- Write effective documentation including README, code comments, and demo media.
- Share your work publicly and build your project portfolio.

###  7. Real-World Problem Solving
- Develop a practical solution for automating business contact management.
- Improve productivity by reducing manual data entry.
- Understand user interaction flow and usability design.

---

