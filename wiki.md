# Project Summary
The project is a comprehensive Human Resources (HR) management application tailored for Prosh International, focusing on streamlining HR processes such as employee management, payroll tracking, leave requests, and performance evaluations. This application features a fully localized Arabic version, ensuring a right-to-left (RTL) layout and user-friendly navigation for Arabic-speaking HR professionals.

# Project Module Description
The application consists of several key functional modules:
- **Dashboard**: Displays key metrics and statistics.
- **Employee Management**: Manage employee profiles, including adding, editing, and viewing details.
- **Department Management**: Organize employees by departments and manage department details.
- **Leave Management**: Handle leave requests and track leave balances.
- **Payroll Management**: Manage payroll records and salary processing.
- **Performance Reviews**: Conduct and manage employee performance evaluations.
- **Reports**: Generate and view various HR reports.
- **Settings**: Configure application settings and user permissions.
- **Authentication**: Secure login and user management features.

# Directory Tree
```
shadcn-ui/
├── README.md
├── components/
│   ├── dashboard/
│   │   └── ArabicDashboard.tsx
│   ├── departments/
│   │   ├── ArabicDepartmentList.tsx
│   ├── employees/
│   │   ├── ArabicEmployeeList.tsx
│   ├── leaves/
│   │   └── ArabicLeaveManagement.tsx
│   ├── payroll/
│   │   └── PayrollManagement.tsx
│   ├── performance/
│   │   └── PerformanceReviews.tsx
│   ├── reports/
│   │   └── Reports.tsx
│   ├── settings/
│   │   └── ArabicSettings.tsx
│   ├── auth/
│   │   └── LoginPage.tsx
│   ├── layout/
│   │   ├── ArabicHeader.tsx
│   │   └── ArabicSidebar.tsx
│   └── ui/
├── data/
│   ├── arabicData.ts
│   └── PROSH_DATA.json
├── hooks/
│   └── use-toast.ts
├── types/
│   └── index.ts
├── App.css
├── App.tsx
├── index.html
├── package.json
├── postcss.config.js
└── vite.config.ts
```

# File Description Inventory
- **README.md**: Project documentation and overview.
- **components/**: Contains all UI components for different modules.
- **data/PROSH_DATA.json**: Contains sample data for employees, departments, leave requests, and payroll records.
- **data/arabicData.ts**: Contains Arabic data for use in the application.
- **hooks/use-toast.ts**: Custom hook for managing toast notifications.
- **types/index.ts**: TypeScript interfaces for various data structures used in the application.
- **App.css**: Main CSS styles for the application.
- **App.tsx**: Main application component that integrates all modules.
- **index.html**: Entry point HTML file.
- **package.json**: Project dependencies and scripts.
- **postcss.config.js**: Configuration for PostCSS.
- **vite.config.ts**: Configuration for Vite, the build tool.
- **INITIATE.md**: Installation and setup guide for the Arabic version.

# Technology Stack
- **Frontend**: React, TypeScript, Tailwind CSS, Shadcn-UI
- **Build Tool**: Vite
- **State Management**: React hooks
- **Styling**: Tailwind CSS for responsive design

# Usage
To get started with the project, follow these steps:
1. Install dependencies:
   ```bash
   pnpm install
   ```
2. Run linting to ensure code quality:
   ```bash
   pnpm run lint
   ```
3. Start the development server:
   ```bash
   pnpm run dev
   ```
