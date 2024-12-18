#  CalorieMate: AI-Powered Nutrition Assistant 
**CalorieMate** is an AI-powered nutritionist assistant that helps users calculate the total calorie content of food items in an image. By uploading an image of food, the app uses the **Gemini** API to analyze the content and provide detailed information about each food item along with its calorie count.  
## 🎬 Demo  
You can see a demo of the **Gemini Health App** in action below:
<img width="629" alt="Screenshot 2024-12-12 at 11 28 47 AM" src="https://github.com/user-attachments/assets/a93c8008-46a2-4b0e-bf93-e8eb3b293fce" />

1. **Upload Food Image**: Upload an image of food items you want to analyze.  
2. **Ask Questions**: Type a question like "Tell me the total calories" or "What are the food items?"  
<img width="689" alt="Screenshot 2024-12-12 at 11 33 09 AM" src="https://github.com/user-attachments/assets/440e410c-e9e9-4dd5-b2dd-25063c6ca78d" />

3. **AI Response**: Get an instant response with the details of each food item and their calorie counts.
<img width="604" alt="Screenshot 2024-12-12 at 11 33 23 AM" src="https://github.com/user-attachments/assets/e5498b9f-b44c-4e89-b5cd-71bc2f7e8401" />

## 🌟 Features  
- **📸 Food Image Recognition**: Upload food images (JPEG, PNG, JPG).  
- **🍎 Calorie Counting**: Get the total calorie count and detailed calorie information for each food item.  
- **🤖 AI Nutritionist**: Leverages **Gemini** AI to identify food items and calculate calories.  
- **💻 Interactive UI**: Simple, intuitive interface built with **Streamlit**.  

## 🛠️ Technologies Used  
- **Gemini**: For image and content analysis.  
- **Python**: The core programming language.  
- **Streamlit**: For the web interface.  
- **Pillow**: For image handling.  
- **dotenv**: To manage environment variables securely.  

## 📥 Installation Guide  
Make sure you have **Python 3.7+** and **pip** installed.

### Step 1: Clone the Repository  
Clone the repository to your local machine:  
`git clone https://github.com/mohanganesh3/HEALTHAPP.git`  
`cd HEALTHAPP`  

### Step 2: Set Up a Virtual Environment  
It’s recommended to use a virtual environment to manage dependencies:  
`python3 -m venv venv`  
`source venv/bin/activate`  # On Windows, use `venv\Scripts\activate`  

### Step 3: Install Required Dependencies  
Install the necessary Python libraries by running:  
`pip install -r requirements.txt`  

### Step 4: Set Up Environment Variables  
Make sure to set up the required **Google API key** for **Gemini**. You can add it to a `.env` file in the root of your project:  
`GOOGLE_API_KEY=<your_google_api_key>`  

### Step 5: Run the Application  
Start the application using **Streamlit**:  
`streamlit run app.py`  
This will open the app in your default browser. You can upload an image of food and get the total calorie count.

## 💡 Usage  
1. **Upload Image**: Choose a food image in JPEG, PNG, or JPG format.  
2. **Enter Prompt**: Input a brief description or question about the food items.  
3. **Get Calorie Information**: Click the button to calculate total calories and receive detailed breakdowns of each food item.

## ⚙️ How It Works  
1. **Image Processing**: The system reads the uploaded food image.  
2. **Food Item Identification**: Using **Gemini**, the image is analyzed to identify food items.  
3. **Calorie Counting**: The AI calculates the total calories and provides a detailed list of items and their individual calorie count.  
4. **User Interaction**: The user inputs the prompt and receives the result directly in the app.

## 📝 Example  
### Sample Interaction:  
1. **Upload Image**: Upload an image of a plate with food.  
2. **Input Prompt**: “Tell me the total calories”  
3. **Response**:  
