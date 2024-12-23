# Egypt Metro

## Overview

**Egypt Metro** is an integrated metro system management platform designed to improve the commuting experience. The platform provides a seamless and efficient way for passengers to plan trips, track trains, and manage tickets, all while leveraging AI for crowd management and optimized routing. The project is composed of three main components: the frontend (Flutter), the backend (Django), and AI models (TensorFlow).

## Features

- **Route and Trip Planning**: Plan your trip, view metro lines, stations, and ticket prices.
- **Train Schedules**: Get real-time updates on train arrivals and locations.
- **Crowd Management**: Predict and visualize crowded train cars using AI.
- **User Profiles**: Create and manage profiles, including monthly/student pass options.
- **QR Code Ticketing**: Generate and scan QR codes for tickets.
- **Chatbot Support**: Assist users with FAQs and navigation.
- **Fault Reporting**: Report issues and track resolutions in real time.
- **Multiple Payment Methods**: Secure payment options for tickets and subscriptions.
- **Admin Dashboard**: Track revenue, sales, and station performance in real time.

## Features Breakdown

1. **Metro Route and Trip Planning**
   - Shows all metro lines, routes, and connections.
   - Provides trip duration, number of stops, and ticket prices.
   - Suggest the best routes for efficient travel.

2. **Train Schedules**
   - Real-time schedules with arrival times.
   - Tracks train locations using GPS.
   - Indicates if trains are air-conditioned.

3. **Crowd Management**
   - Shows real-time crowd levels on each train car.
   - Uses AI to predict congestion, especially during peak hours.
   - Helps users find less crowded spaces on the train.

4. **User Profiles & Subscriptions**
   - Allows users to create profiles and manage their accounts.
   - Provides monthly or student passes and subscription renewals.
   - Offers secure payment options for tickets and subscriptions.
  
5. **Ticket Scanning with QR Codes**
   - Generates a unique QR code for each ticket purchase.
   - Allows users to scan their QR code at metro entrances for quick access.
   - Supports contactless entry, enhancing convenience and reducing physical interaction.

6. **Chatbot Support**
   - Answers common questions and guides users through the app.
   - Connects users to customer service for help when needed.
   - Available 24/7 for quick assistance.

7. **Fault Reporting**
   - Let users report issues or suggest improvements.
   - Allows feedback to enhance service quality.
   - Admins respond to reports and update users on issue status.

8. **Multiple Payment Methods**
   - Offers secure online payment options for tickets and passes.
   - Supports a range of payment options for convenience.
   - Enables contactless transactions for a safer experience.


## Technologies Used

- **Backend:**
  - **Python** with **Django**: Backend logic and API management.

- **Frontend:**
  - **Flutter**: Cross-platform mobile app development.

- **Database:**
  - **PostgreSQL** or **MySQL**: Data storage and management.

- **AI and Machine Learning:**
  - **TensorFlow** or **PyTorch**: Crowd management and ticket validation.

- **Payment Processing:**
  - **Stripe** or **PayPal**: Secure online payment handling.

- **Real-Time Data:**
  - **WebSockets**: For live updates.

- **Development Tools:**
  - **Git**: Version control.
  - **Docker**: Containerization.
  - **Postman**: API testing.

- **Project Management:**
  - **Trello**: Task tracking.
  - **Microsoft Teams**: Team communication.

- **Testing:**
  - **Selenium**: Automated frontend testing.
  - **pytest** and **PHPUnit**: Backend testing.
 
- **Documentation:**
  - **Notion**: Project Documentation.

## Architecture

The project follows a **modular architecture**:
- **Frontend**: Flutter-based mobile/web app (see `egypt-metro-flutter`).
- **Backend**: Django API (see `egypt-metro-backend`).
- **AI**: TensorFlow models for congestion prediction and route optimization (see `egypt-metro-ai`).

## Repositories

- [Frontend (Flutter)](https://github.com/egypt-metro/egypt-metro-flutter)
- [Backend (Django)](https://github.com/egypt-metro/egypt-metro-backend)
- [AI Models](https://github.com/egypt-metro/egypt-metro-ai)

## Installation

Clone the repositories and follow the respective setup instructions for each component:

1. **Frontend**:
   - [Frontend Setup Instructions](https://github.com/egypt-metro/egypt-metro-flutter)
2. **Backend**:
   - [Backend Setup Instructions](https://github.com/egypt-metro/egypt-metro-backend)
3. **AI Models**:
   - [AI Setup Instructions](https://github.com/egypt-metro/egypt-metro-ai)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
