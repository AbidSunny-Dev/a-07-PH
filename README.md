# 👥 KeenKeeper — Keep Your Friendships Alive

**KeenKeeper** is a specialized Personal Relationship Management (PRM) application designed to prevent "friendship fade." It helps users maintain meaningful connections through goal-setting, automated status tracking, and interaction logging.


## 🛠️ Technical Stack
- **Framework:** React.js / Next.js
- **Styling:** Tailwind CSS (Mobile-first design)
- **Navigation:** React Router DOM / Next App Router
- **Charts:** Recharts (Data Visualization)
- **Notifications:** React Hot Toast / Toastify
- **Data Source:** Local JSON (friends.json)

### 1. Smart Dashboard & Navigation
- **Figma-Perfect Navbar:** Includes a responsive logo, navigation links (Home, Timeline, Stats) with integrated icons, and active state highlighting.
- **Dynamic Friend Grid:** A 4-column layout (on desktop) that displays friend cards with real-time status indicators (**Overdue**, **Almost Due**, **On-Track**).
- **Banner Analytics:** A centered hero section with a call-to-action and 4 summary cards for quick insights.

### 2. Interaction Management
- **Detailed Profiles:** A two-column layout featuring profile bios, relationship tags, and contact stats.
- **Quick Check-In:** Functional Call, Text, and Video buttons that automatically:
  - Add entries to the global Timeline.
  - Trigger instant Toast notifications for user feedback.

### 3. Friendship History (Timeline)
- A chronological feed of all past interactions.
- Each entry displays the specific date, a category-specific icon, and the friend's name.

### 4. Robust UX/UI
- **Custom 404 Page:** Graceful handling of invalid routes.
- **Loading States:** Smooth animations while fetching friend data.
- **Deployment Ready:** Configured to handle page refreshes without errors.


- **C1. Friendship Analytics:** A dedicated Stats page featuring a **Recharts Pie Chart** that visualizes the distribution of your communication methods (Call vs. Text vs. Video).
- **C2. Timeline Filtering:** Advanced filtering logic allowing users to sort their interaction history by type.
- **C3. Professional Documentation:** This comprehensive README.md file.

## 📂 Project Structure
```text
├── public/
│   └── friends.json      # Realistic friend profiles
├── src/
│   ├── components/       # Navbar, Footer, FriendCard, StatsCard
│   ├── pages/            # Home, Detail, Timeline, Stats, NotFound
│   ├── App.js            # Routing logic
│   └── index.css         # Tailwind & Custom styles
└── README.md

