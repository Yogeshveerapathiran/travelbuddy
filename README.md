Travel Buddy App Full Specification

🏠 Home Page

About the app: Introduction and purpose.

Navigation links: Travel History, Upcoming Travel, Chat, Profile.

👤 Authentication

Login Page

User Registration

Admin Login (separate interface)

🌍 Core Travel Listing Features

Default Starting Point: Saveetha

Default End Point: Chettiped

Default Mode of Transport: Walk

Default Time format: PM

Travel Listing Details

Mode of transport: Car (limit 2 or 3), Bike (1 or 2), Walk

Departure time

Return time (optional)

Description (e.g., "after shopping") if return time not specified

Pick-up location

Drop-off location

You can join from (optional joining point)

Destination: Dropdown list with Module, CIA, SA, Movie, Shopping, Other (text box appears)

Note box:

Travel full time

You can leave anytime

🔍 Explore & Join Trips

Show all upcoming trips

If occupancy is full: show "Full Capacity"

Join button to send request to join travel

Withdraw join request button

Cancel travel (if you're the creator)

Auto-delete all completed travels of the day, or at week end

Suggest other users travelling at the same time

📅 Travel Management

All Trip List

Upcoming Trips

Travel History

💬 Communication

Chat with travel partner

Cost Split info

👥 Profile

Name (option to hide)

Gender (option to hide)

Gender Preference (e.g., Female Preferred)

Male/Female selection

Follow specific travelers

Profile page with user details

⚖️ Admin Portal

Login (exclusive for admin)

View all travel listings

Delete any travel or profile

Manage reported users/travels

Moderate chat or flagged content

📂 Database Collections

Users: name, email, password, gender, preferences, profile visibility

Travels: starting point, end point, mode, occupancy, time, return time, notes, gender preference, creatorId, etc.

JoinRequests: userId, travelId, status

Messages: senderId, receiverId, message, timestamp

Admin: credentials, permissions

☑️ Hosting

Hosting on Railway for backend and database

React frontend deployed on Netlify or also via Railway

Let me know when you're ready to start building the components step-by-step — I can generate React components, Express backend, and database schema for each section.

