# 🚚 TradeFlow Driver App

A premium, high-performance Flutter application designed for logistics drivers. This app features a clean white-themed interface with vibrant green accents, providing a professional and user-friendly experience for managing shipments, tracking earnings, and navigating routes.

## ✨ Key Features

### 📊 Driver Dashboard
- **Live Status Toggle**: Easily switch between online/offline modes.
- **Real-time Stats**: Track weekly earnings and jobs completed today at a glance.
- **Current Job Overview**: A focused view of your active shipment with an integrated map preview and quick navigation button.

### 📋 My Jobs Management
- **Active & Completed Tabs**: Organized view of all assigned tasks.
- **Detailed Shipment Cards**: View pickup/drop-off locations, status (In Transit, Pending), and estimated earnings for every job.

### 🔔 Smart Job Alerts
- **Timed Offers**: Real-time countdown timer for accepting new job invitations.
- **Job Preview**: Detailed cargo information including container type, weight, and volume before you accept.
- **Earnings Breakdown**: Transparent view of total earnings including fuel and toll inclusions.

### 🗺️ Active Navigation & Tracking
- **Live Job Tracking**: Interactive map view for active shipments.
- **Status Progress**: A detailed checklist to track milestones: Job Accepted → Reached Pickup → Cargo Loaded → In Transit.
- **Quick Communication**: One-tap buttons to chat or call for support.

### 👤 Driver Profile
- **Performance Metrics**: View your ratings, total jobs completed, and experience level.
- **Document Management**: Quick access to licenses and transport documents.
- **Settings**: Personalized app configurations.

## 🛠️ Technology Stack
- **Framework**: [Flutter](https://flutter.dev/)
- **Language**: [Dart](https://dart.dev/)
- **UI Architecture**: Modular Component-Based Design
- **Theme**: Custom White & Green Material 3 Design
- **Maps API**: Integrated Map View Components

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (Latest Stable Version)
- Dart SDK
- Android Studio / VS Code with Flutter extension

### Installation
1.  **Clone the repository**:
    ```bash
    git clone https://github.com/poornima2006188/DriverAppTrackEye.git
    ```
2.  **Navigate to the project directory**:
    ```bash
    cd "driver ui"
    ```
3.  **Install dependencies**:
    ```bash
    flutter pub get
    ```
4.  **Run the application**:
    ```bash
    flutter run
    ```

## 📂 Project Structure
```text
lib/
├── main.dart                # App entry point & Theme configuration
└── screens/
    ├── home_screen.dart     # Driver Dashboard
    ├── my_job_screen.dart   # Job List & History
    ├── job_details_screen.dart # Job Alerts & Acceptance
    ├── active_job_map_screen.dart # Live Navigation & Tracking
    └── profile_screen.dart  # User Profile & Stats
```

## 🎨 Theme Guidelines
The app utilizes a specialized design system:
- **Primary Color**: `#22C55E` (Vibrant Green)
- **Background**: `#F8FAFC` (Slate White)
- **Text (Primary)**: `#1E293B` (Dark Slate)
- **Text (Secondary)**: `#64748B` (Cool Gray)

---

Developed with ❤️ for the Modern Logistics Industry.
