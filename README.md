# selling-Android-App
Mobile Selling Application(Phonely)
Objective:
To build a user-friendly mobile application that provides personalized phone recommendations based on user preferences and financial data. The app predicts credit risk scores to help users manage their payment reliability and offers installment plan options for purchasing phones. Admins can efficiently manage users, phone inventory, credit risk reports, and installment plans. Integrated AI chatbot support enhances user experience by providing instant assistance and information.
Features:
•	Admin side 
o	Authentication via firebase Authentication
o	Add , Update , Delete  phones in SQLITE database and firebase Store
o	Comapre 2 phones in slipt window with AI based Analysis and recommendation
o	Add Installment plans
•	Customer side
o	Account creation and Authentication
o	View , Search Phones
o	Compare phones
o	View and avail Installement plan
•	Multipe installment planes

API:
ImgBB API:
User uploads an image (e.g., phone photo) → ImgBB API receives the image and stores it on its servers → returns a direct image URL for future use (e.g., displaying or saving in Firebase).
Input: Image file (e.g., from Android app)
Output:URL to include in firebase
Firebase API :
User data or app events sent to Firebase → Firebase handles authentication, database, and storage → returns success/failure or data updates in real time.
Input: User action data (e.g., user login, saving phone preferences)
Output: Confirmation messages or updated data from Firebase (e.g., login success, saved preferences)
App Flow:
•	User logs in or signs up using Firebase Authentication.
•	Admin accesses dashboard to manage phones, installment plans, and track customer payments.
•	Customer views and searches phones, or chats with the AI chatbot for recommendations.
•	Customer compares two phones 
•	Customer views and avails flexible installment plans.
•	Installment status and alerts are shown, with credit risk predicted from user data.

Screens(Refrence images):
1. Login Screen
•	Unified login for both Admin and Customer using Firebase Authentication.
•	Role-based redirection to respective dashboards after successful login.
 
2. Admin Dashboard (Fragments)
•	Phone Inventory Management Fragment
Add, update, or delete phone models and specifications.
•	Credit Risk Score Fragment
Displays customers’s credit risk score with simple visualization.
•	View all Customers purchase and status
The activity would help to view details of all customers
Phone inventory Management 


3. Customer Dashboard (Fragments)
•	Home/Recommendation Fragment
Shows personalized phone recommendations based on user preferences.
•	User Profile Fragment
Allows editing of personal info and phone preferences.
•	View List
To check Phones and their  details in another activity
•	Compare Phone
Compare 2 phones in split window

Profile View 

View Phones Fragment 
Select installment plans  
Split Screen to Comapre Phones  
View details Plan in Progress  

Conclusion:
This application simplifies the phone buying experience by offering smart recommendations and flexible installment options based on user data. It empowers users with insight into their credit risk while maintaining ease of use through a clean interface. Admin tools ensure smooth management of users, products, and analytics. The integrated AI chatbot further enhances accessibility and user support. Overall, the app bridges technology, finance, and convenience for both users and admins.


