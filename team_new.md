# TEAM

## MEMBERS

| Member   | Role                              | Task |
| -------- | -----------------------           | ---- |
| Sizzart  | Core Itinerary Engine             | TBD  |
| suchThat | Expense Tracking & Budget         | TBD  |
| yohan    | Activity Discovery & External API | TBD  |
| Peanut   | Frontend & Shareable Timeline     | TBD  |

## PROJECT

### Problem: 
Users struggle to organize multi-city trips, track dynamic expenses, and visualize schedules efficiently.

### Tech Stack: 

To build the **Travel & Itinerary Planner** quickly and efficiently with a 4-member team, a unified JavaScript/TypeScript ecosystem minimizes context switching and allows code reuse across the stack.

- **Frontend**: **React** or **Next.js** with **Tailwind CSS**
  - *Why*: Fast component setup, excellent UI libraries (like Shadcn UI or Material Tailwind), and smooth drag-and-drop integration for timelines.
- **Backend**: **Node.js** with **Express.js**
  - *Why*: Lightweight, rapid API scaffolding, and shared language syntax (`JavaScript`/`TypeScript`) with the frontend team.
- **Database & ORM**: **MongoDB** with **Mongoose** (or **PostgreSQL** with **Prisma**)
  - *Why*: Flexible JSON-like document structures for complex, nested multi-city itineraries and dynamic expense records.
- **State & Utilities**: **Zustand** or **Redux Toolkit** for state management, and **Axios** for API calls.

## TASKS

### Team Ownership Mapping

- **Member 1 (Itinerary Engine)**: Owns `server/src/models/trip.js`, `server/src/controllers/itineraryController.js`, and `client/src/features/itinerary/`.
- **Member 2 (Expense Tracker)**: Owns `server/src/models/expense.js`, `server/src/controllers/expenseController.js`, and `client/src/features/expenses/`.
- **Member 3 (Activity Discovery & APIs)**: Owns `server/src/services/mapsService.js`, `server/src/controllers/activityController.js`, and `client/src/features/discovery/`.
- **Member 4 (Frontend Architecture & Shareable Timelines)**: Owns `client/src/components/`, `client/src/store/`, and public routing views for shared itineraries.

## FOLDER STRUCTURE 
```
travel-planner/
├── .github/                  # CI/CD workflows and issue templates
├── client/                   # Frontend Application (React / Next.js)
│   ├── public/               # Static assets & icons
│   └── src/
│       ├── assets/           # Images, fonts, styles
│       ├── components/       # Shared UI components (Buttons, Modals, Cards)
│       ├── features/         # Feature-based modules
│       │   ├── itinerary/    # Timeline views, drag-and-drop schedule components
│       │   ├── expenses/     # Budget charts, expense list & forms
│       │   └── discovery/    # Activity search bars, maps, recommendation grids
│       ├── hooks/            # Custom React hooks
│       ├── services/         # API client functions (Axios / Fetch)
│       ├── store/            # State management (Zustand / Redux / Context)
│       ├── utils/            # Helper functions & formatters
│       ├── App.jsx
│       └── main.jsx
├── server/                   # Backend Application (Node.js / Express)
│   └── src/
│       ├── config/           # Database & third-party service configurations
│       ├── controllers/      # Route controllers (Itinerary, Expense, Activity)
│       ├── middleware/       # Auth, error handling, validation
│       ├── models/           # Database schemas (Mongoose / Prisma / Sequelize)
│       ├── routes/           # API endpoint definitions
│       ├── services/         # Business logic & external API wrappers
│       ├── utils/            # Server helpers
│       └── server.js
├── .env.example              # Environment variables template
├── .gitignore
├── package.json
└── README.md
```

### IN PROGRESS


## IMPORTANT DECISIONS

-

## FILES BEING WORKED ON

-