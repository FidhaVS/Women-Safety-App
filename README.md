# Women-Safety-App


## Basic Details
### Team Members
- Member 1: Fidha V S - SCMS School of Engineering and Technology
- Member 2: Fathima Mehar P S - SCMS School of Engineering and Technology
- Member 3: Farhan Abdulla M J - SCMS School of Engineering and Technology
- Member 4: Eshan James - SCMS School of Engineering and Technology


### Project Description
Guardia – Women’s Safety Web App is a full-stack application developed to ensure real-time security and emergency assistance for women. It combines emergency alerts, geofencing, real-time tracking, legal/self-defense resources, and community safety reporting into a unified, user-friendly platform. This solution emphasizes fast help, local safety info, and secure user management, built using a modern JavaScript/TypeScript-based stack.

### The Problem statement
Despite the availability of women’s safety apps, many lack critical features like immediate response, geofencing, or integration with emergency resources. In high-risk or panic situations, traditional communication methods may fail. There's a need for a fast, discreet, and reliable web application that empowers women to call for help, access support, and alert communities in real time.

### The Solution
Guardia provides:

One-click SOS activation via web interface.

Real-time location tracking using WebSockets.

Geofencing alerts if the user exits safe zones.

Panic alarm activation with siren sounds.

Emergency contact alerts through Firebase functions.

Access to legal aid and curated self-defense videos.

Nearby police/hospital/shelter discovery via Google Maps API.

Community alerts for user-reported local incidents.

Integration of Avrde AI agent (planned) to auto-generate incident reports.

Firebase-secured authentication with local-only dataset storage.


## Technical Details
### Technologies/Components Used
For Software:

Technologies/Components Used :
  Frontend: React , TypeScript , Tailwind CSS , Radix UI , Wouter
  
  Backend: Node.js , Express.js , WebSocket (ws) , Drizzle ORM
  
  Database: PostgreSQL (with Drizzle ORM), local dataset storage
  
  Authentication:	Firebase Auth (Client + Admin SDK only)

  Map Services:	Google Maps API

Frameworks & Libraries Used :

  Frontend :
  
       React + TypeScript

       Tailwind CSS, Radix UI

       Wouter (routing), Framer Motion

       React Hook Form + Zod

       Lucide-react (icons), Toast notifications
    
  Backend :

        Express.js (Node)

        WebSocket (ws) for live location/SOS

        Drizzle ORM + PostgreSQL

        Firebase Admin SDK

        Express-session (optional, if using session



### Implementation
For Software:
# Installation
Follow these steps to set up the project on your system:

 1. Clone the Repository (if applicable)

     git clone <repo-url>
     cd guardia

 2. Install Required Dependencies
  
    npm install
    
    cd client && npm install
    
    cd ../server && npm install

 3. Create & Activate a Virtual Environment

     VITE_FIREBASE_API_KEY=your_firebase_api_key
    
     VITE_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
    
     VITE_FIREBASE_PROJECT_ID=your_project_id
    
     VITE_GOOGLE_MAPS_API_KEY=your_google_maps_key


# Run
npm run dev     # Or use Replit run button with a combined script


### Project Documentation
For Software:

# Screenshots 
![Home Screen](https://github.com/user-attachments/assets/a866a933-acd0-4532-9dbf-76263436670a)
Home Screen

![Profile](https://github.com/user-attachments/assets/c501cf4b-26a7-431c-aa62-f67d8bc9db14)
Profile

![SOS button when clicked(before alert is sent)](https://github.com/user-attachments/assets/001abe79-1e88-4cfa-b154-3f55e8a07edf)
SOS button when clicked(before alert is sent)

![SOS alert is sent](https://github.com/user-attachments/assets/b5150e69-d42c-45d5-b8db-08bd45c5bfde)
SOS alert is sent

![To add Emergency contact](https://github.com/user-attachments/assets/b95c4d19-8086-4617-8dd0-2a867e284c2b)
To add Emergency contact

![Public emergency contact numbers](https://github.com/user-attachments/assets/f08bf4fb-4902-467d-9a25-1d77313615fe)
Public emergency contact numbers

![Legal Resources Page](https://github.com/user-attachments/assets/3636877e-6811-4f14-a176-7fb7f52df44d)
Legal Resources Page

![When clicked on a resource](https://github.com/user-attachments/assets/a6abe69b-fc23-42c4-b9ad-9cdc9753d103)
When clicked on a resource

![Self defence training videos](https://github.com/user-attachments/assets/272f8397-2e3a-4aa3-be74-4192b3cfe869)
Self defence training videos

![When clicked on a video ](https://github.com/user-attachments/assets/50ab089d-9fa7-443c-b15d-4ff4ea395b03)
When clicked on a video

![Nearby Safety Resourcess](https://github.com/user-attachments/assets/38592780-e1b5-438c-83a1-c8d955fdad97)
Nearby Safety Resources

![Nearby Hospitals](https://github.com/user-attachments/assets/279f16fe-2fe1-48f5-9919-cb8454d8ee88)
Nearby Hospitals

![Nearby Police Stations](https://github.com/user-attachments/assets/7643fe39-582d-4843-a8d1-d5507248ae59)
Nearby Police Stations

![When clicked on get direction redirects to the google maps page with destination set to the required location](https://github.com/user-attachments/assets/2ea9b7e4-1dae-4a24-93d7-b0dfe64de644)
When clicked on get direction redirects to the google maps page with destination set to the required location

![Community Alerts](https://github.com/user-attachments/assets/7f965f6b-5d06-4f6d-9a66-d5b67f7befd9)
Community Alerts

# Diagrams
![WhatsApp Image 2025-06-03 at 20 29 18_99188b53](https://github.com/user-attachments/assets/aa025979-79fb-4a33-8151-2abd65167cba)
System Architecture

![WhatsApp Image 2025-06-03 at 20 29 19_92b80599](https://github.com/user-attachments/assets/68606e15-64fb-4bca-a917-772c5834beb1)
Flowchart

![WhatsApp Image 2025-06-03 at 20 29 19_21a6a95a](https://github.com/user-attachments/assets/7d1f62c4-69cc-4298-b57c-dea8d313bf8b)
Database Collections

### Project Demo
# Video
https://drive.google.com/file/d/1MGFJobLbLZGGmi90KlZZXTLxCL5DYl7R/view?usp=drivesdk

This video explains the working and the features we provided in the app.
