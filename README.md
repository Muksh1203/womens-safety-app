# EmpowerSafe Platform

A comprehensive women's safety platform with real-time emergency response, wellness tracking, and community support.

## Features

- **Emergency SOS**: One-tap emergency alerts with live location sharing
- **Smart Contacts**: Manage emergency contacts with quick actions
- **Wellness Tracker**: Step counter and health monitoring
- **Safety Rewards**: Earn points and badges for safety habits
- **Real-time Location Services**: GPS tracking and nearby police stations
- **Voice Alerts**: Record and send emergency voice messages
- **Shake Detection**: Emergency activation through device motion
- **Safety Tips & Legal Rights**: Educational content and resources

## Technology Stack

- **Frontend**: Next.js 14, React 18, TypeScript
- **Styling**: Tailwind CSS, Radix UI Components
- **Icons**: Lucide React
- **Sensors**: Device Motion API, Geolocation API
- **Storage**: Local Storage for offline functionality

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
\`\`\`bash
git clone <repository-url>
cd empowersafe-platform
\`\`\`

2. Install dependencies:
\`\`\`bash
npm install
\`\`\`

3. Run the development server:
\`\`\`bash
npm run dev
\`\`\`

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Building for Production

\`\`\`bash
npm run build
npm start
\`\`\`

## Project Structure

\`\`\`
empowersafe-platform/
├── app/                    # Next.js App Router pages
│   ├── contacts/          # Emergency contacts management
│   ├── dashboard/         # Main dashboard
│   ├── nearby/           # Police stations locator
│   ├── onboarding/       # User registration flow
│   ├── profile/          # User profile management
│   ├── safety-tips/      # Safety education content
│   ├── wellness/         # Health and step tracking
│   ├── globals.css       # Global styles
│   ├── layout.tsx        # Root layout
│   └── page.tsx          # Landing page
├── components/            # Reusable UI components
│   ├── ui/               # Shadcn/ui components
│   └── theme-provider.tsx
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
└── public/               # Static assets
    └── images/           # Background images
\`\`\`

## Key Features Implementation

### Real-time Step Tracking
- Uses Device Motion API for accelerometer-based step detection
- Calculates calories, distance, and active minutes in real-time
- Offline functionality with local storage persistence

### Emergency Alert System
- SMS integration with live GPS coordinates
- Multiple contact support with priority settings
- Shake detection for hands-free emergency activation

### Location Services
- Real-time GPS tracking
- Nearby police stations with directions
- Google Maps integration

### Gamification System
- Points and badges for safety activities
- Courage score tracking
- Progress levels and achievements

## Browser Compatibility

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Permissions Required

- **Location**: For GPS tracking and emergency alerts
- **Motion**: For step counting and shake detection
- **Microphone**: For voice message recording

## Contributing

This is an academic project developed by:

- **Project Type**: Minor Project
- **Department**: B.Tech in Information Technology
- **Year**: 3rd Year | **Semester**: 6th | **Section**: IT/3AY
- **Team Members**:
  - Muksh Saha (Roll: 46)
  - Suvecchha Paul (Roll: 10)
  - Arthi Saha (Roll: 67)
  - Ayush Tiwari (Roll: 49)
  - Pratasna Mondal (Roll: 50)

## License

This project is developed for educational purposes.

## Support

For technical support or questions about the project, please contact the development team.
