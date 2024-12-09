# Trustfall - Privacy-Focused Safety Application

## Overview
Trustfall is a web-based safety application that provides location sharing capabilities with a strong focus on user privacy. The application allows users to share their location only during emergency situations, ensuring personal safety without compromising daily privacy.

## Features
- User authentication system
- Privacy-focused location tracking
- Emergency alert system
- Friend management
- Profile customization
- Interactive dashboard
- Smart location sharing

## Technical Stack
- Frontend: HTML, CSS
- Backend: Back4App (Parse Server)
- Database: MongoDB (via Back4App)
- Maps Integration: Google Maps API

## Setup Instructions

### Prerequisites
- Back4App account
- Node.js and npm installed
- Web browser with JavaScript enabled

### Back4App Configuration
1. Create a new Back4App application
2. Import the provided `_User` schema
3. Configure application keys and IDs in your environment

### Local Development
1. Clone the repository
2. Install dependencies
3. Configure environment variables:
   ```
   BACK4APP_APP_ID=your_app_id
   BACK4APP_JS_KEY=your_javascript_key
   BACK4APP_SERVER_URL=https://parseapi.back4app.com
   ```
4. Run the development server

## Project Structure
```
trustfall/
├── html/
│   ├── trustfall.html    # Landing page
│   ├── login.html        # Authentication page
│   └── user_dashboard.html # User interface
├── css/                  # Stylesheets
├── js/                   # JavaScript files
└── schemas/
    └── _User.json        # Back4App user schema
```

## Security Features
- Authentication required for all sensitive operations
- Location data only shared during active tracking
- Privacy-first approach to personal data
- Friend-based access control

## License
This project is licensed under the MIT License - see the LICENSE file for details.