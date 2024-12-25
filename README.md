# matrimonial-app-simulator

**Matrimonial App Simulator**

This repository contains an iOS app that simulates the functionality of a matrimonial app, inspired by platforms like Shaadi.com. The app is built using SwiftUI and incorporates a modern, user-friendly interface for displaying match cards. It demonstrates key concepts in iOS development such as fetching data from an API, offline persistence, and interactive UI elements

**Features**
1. Match Cards - The app displays user profiles in a card-based layout, similar to Shaadi.com's match cards. Cards are developed entirely in SwiftUI, leveraging its declarative syntax for a seamless UI.
2. API Integration - Fetches user data from the provided API. Displays the data dynamically in a SwiftUI List, ensuring real-time updates.
3. User Interactions - Users can accept or decline matches with simple, intuitive gestures or buttons. Decisions are visually reflected on the card for better user experience.
4. Offline Persistence - User decisions (accept/decline) are stored persistently using Swift Data. Decisions remain intact even in offline mode or after the app is relaunched.

**Technology Stack**
SwiftUI: For building a declarative and responsive user interface.
Combine: For managing asynchronous tasks and data flow.
Swift Data: For offline storage of user decisions.
URLSession: For API integration and data fetching.

**Installation**
1. Clone the repository:
    git clone https://github.com/yourusername/matrimonial-app-simulator.git
2. Open Project in Xcode
    cd matrimonial-app-simulator
    open MatrimonialAppSimulator.xcodeproj
3. Build and run the app on the simulator or a physical device.


**How It Works**
Fetching Data: The app sends a request to the provided API to fetch user profiles. Data is parsed and displayed in a SwiftUI List and match card format.
User Decisions: Users interact with match cards to accept or decline matches. Each decision is saved persistently, ensuring offline availability.
Offline Support: Even if the device goes offline, users can still view their past decisions. The app syncs data with the server when the connection is restored (if applicable).

**Screenshots**
Match Cards - 
![Simulator Screenshot - iPhone SE (3rd generation) - 2024-12-25 at 11 46 31](https://github.com/user-attachments/assets/f8dd9951-0d5c-4662-aee8-0dfb03b28cfd)


User Decisions - 

![Simulator Screenshot - iPhone SE (3rd generation) - 2024-12-25 at 11 46 37](https://github.com/user-attachments/assets/e2e0ab88-b660-4cc9-b963-95c9167f6b68)


![Simulator Screenshot - iPhone SE (3rd generation) - 2024-12-25 at 11 46 34](https://github.com/user-attachments/assets/66b7f678-7529-4d7f-938b-6b2375f829fc)
