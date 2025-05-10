Group Chat App 

Overview :

    The Group Chat App is a mobile application built using Flutter for the front-end and Firebase for the back-end. This app allows users to engage in real-time group chats, send messages, and manage user authentication. The app uses Firebase services such as Firestore, Firebase Authentication, Firebase Storage, and Cloud Firestore to handle data storage, user authentication, and photo uploads. 

Features :

    User Authentication: Secure login and signup with Firebase Authentication using email/password or social media logins. 
    
    Profile Photo Upload: Users can upload a profile photo during sign-in via Firebase Storage. 
    
    Real-Time Messaging: Send and receive messages instantly using Firebase Cloud Firestore for real-time updates. 
    
    Group Chats: Create and join group chats, where multiple users can interact in the same conversation. 
    
    Profile Management: Users can set up and update their profile with images and personal details. 

Technologies Used 

    Flutter: Cross-platform mobile application framework for building the front-end. 

    Firebase: 

      Firebase Authentication: For handling user sign-up, login, and authentication. 
      
      Firebase Firestore: For real-time database storage of messages, user profiles, and group data. 
      
      Firebase Storage: For storing user profile images. 
      
      Firebase Cloud Messaging (FCM): For sending push notifications to users. 

    Dart: Programming language used for Flutter development. 

Prerequisites :

  To run this project locally, you’ll need to set up a few tools: 

    Flutter SDK: Install the Flutter SDK from flutter.dev. 
    
    Firebase Account: Create a Firebase project on the Firebase Console. 
    
    Firebase Configuration: Set up Firebase for both Android and iOS and add the necessary configuration files (google-services.json for Android, GoogleService-Info.plist for iOS). 
    
    Android Studio or VS Code: Use either Android Studio or VS Code with the Flutter plugin to run the app. 

Setup Instructions: 

  Step 1: Clone the Repository 

    git clone https://github.com/your-username/group-chat-app.git 
    cd group-chat-app 
      

  Step 2: Install Dependencies 

    Ensure that you have Flutter and Dart installed. Then, run the following command in your terminal to install the necessary packages: 
    
    flutter pub get 
      

  Step 3: Firebase Configuration 

    Create a Firebase Project: Go to the Firebase Console and create a new project. 
    
    Add Firebase to your Flutter App: Follow the instructions to add Firebase to your Flutter app for both Android and iOS: 
    
    Firebase setup for Android 
    
    Firebase setup for iOS 

    Download Configuration Files: 

    For Android: Download google-services.json and place it in the android/app directory. 
    
    For iOS: Download GoogleService-Info.plist and place it in the ios/Runner directory. 
    
    Enable Firebase Services: Enable Firestore, Firebase Authentication, and Firebase Storage in the Firebase Console. 

  Step 4: Run the App 

    Now you’re ready to run the app! Use the following command to launch the app on an emulator or physical device: 
    
    flutter run 
      

  Step 5: Firebase Authentication 
    
    Users can sign up using email/password or any social media login option you configure (e.g., Google, Facebook). 
    
    During sign-in, users can upload a profile photo using Firebase Storage. 
    
    Authentication is handled by Firebase Authentication. 

  Step 6: Sending and Receiving Messages 

    Firestore stores messages in real time. 

Messages are grouped by chat rooms (groups) and displayed in real-time as they are sent. 

Future Enhancements 

Push Notifications: Integrate Firebase Cloud Messaging to notify users when they receive a new message. 

Voice & Video Calls: Implement voice and video calling features using services like Firebase or third-party services. 

Group Management: Add functionality to manage group members, such as adding/removing users or changing group settings. 
