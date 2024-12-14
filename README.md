

# MyAuthApp  

## Project Overview  
MyAuthApp is a simple React Native application for user authentication. It includes **Sign Up** and **Login** screens with basic functionality like validating inputs and navigating between screens.  

---

## How to Run the Project  

1. **Clone the Repository**  
   ```bash  
   git clone <repository-url>  
   cd MyAuthApp  
   ```  

2. **Install Dependencies**  
   Ensure you have Node.js and npm installed. Then run:  
   ```bash  
   npm install  
   ```  

3. **Run the Project**  
   Start the Metro Bundler:  
   ```bash  
   npm start  
   ```  
   - To test on an emulator or device:  
     - For Android: Press **'a'** to open the Android emulator.  
     - For iOS: Press **'i'** to open the iOS simulator (MacOS required).  

---

## Design Choices Made  

1. **Navigation**  
   Used React Navigation for smooth navigation between screens (Sign Up, Login, and Home).  

2. **State Management**  
   Local state was managed using `useState` hooks to handle user inputs and feedback messages.  

3. **Validation**  
   Basic input validation was implemented to ensure passwords match during sign-up and to check credentials during login.  

4. **Feedback**  
   Visual feedback messages are shown for successful/failed login and signup attempts.  

5. **Reusable UI Components**  
   Buttons, inputs, and message feedback were styled consistently to improve user experience.  

---

## Assumptions  

1. **User Credentials**  
   The email and password provided during signup are stored temporarily in memory (state) and used for login validation. No backend or database is connected.  

2. **Basic Validation Only**  
   Input validation checks are minimal and do not include advanced checks (e.g., email format validation).  

3. **Single User Flow**  
   The app assumes a single user flow for testing and demonstration purposes, without persistent storage.
