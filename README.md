React Redux Bank App – Financial Dashboard

A banking application that allows users to manage account balances, perform transactions, and track financial activity through a dynamic, state-driven interface.
This project focuses on global state management with Redux, predictable data flow, and building a real-world financial application UI.

Features:
* Deposit and withdraw money
* Real-time balance updates
* Transaction tracking
* Global state synchronization across components
* Multi-page navigation (if implemented)
* Responsive user interface

Tech Stack:
* Frontend: React
* State Management: Redux / Redux Toolkit
* Routing: React Router (if used)
* Styling: CSS / Tailwind
* Tooling: Vite / Create React App

Architecture & Key Concepts:

* Centralized State with Redux:
All account data (balance, transactions) is managed in a global store for predictable updates.

* Action-Based Updates:
User actions (deposit, withdraw) dispatch actions that update state through reducers.

* Separation of Concerns:
UI components, state logic, and business rules are clearly separated.

* Unidirectional Data Flow:
Ensures consistent and traceable state changes across the app.

* Scalable Structure:
Organized in a way that can support additional features like multiple accounts or authentication.
