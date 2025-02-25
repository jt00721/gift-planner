# gift-planner
The Gift Planner Web App will help users track gift ideas for different occasions and people. Users will be able to add, edit, and organize gifts, set budgets, and mark gifts as purchased.

## Core Goals:

- Add, edit, and delete gift ideas.
- Associate gifts with recipients and occasions (e.g., birthdays, Christmas).
- Track gift budgets and spending.
- Mark gifts as purchased or pending.
- Build a clean and simple UI for easy navigation.

## Project Breakdown by Day
### Define Scope & Set Up Project

✅ Goals:

    Plan out the Gift Planner’s features & functionality.
    Initialize the project folder structure.
    Set up the Go project with dependencies (go mod init).

✅ Tasks:

    Define the database schema (Gifts, Recipients, Occasions).
    Sketch a rough UI wireframe (gift list, budget tracker, status toggles).
    Set up main.go and install necessary dependencies (gin for backend, gorm for database).

📌 Deliverable: Project is initialized & scope is well-defined.

### Set Up Database & Models

✅ Goals:

    Design the relational database schema using SQLite/PostgreSQL.

✅ Tasks:

    Create models for Gifts, Recipients, and Occasions.
    Define relationships (one recipient can have multiple gifts, one occasion can have multiple gifts).
    Implement database migrations & seed some test data.

📌 Deliverable: Database schema is set up and structured properly.

### Implement Backend Logic (CRUD Operations)

✅ Goals:

    Build backend functionality for adding, editing, deleting, and retrieving gifts.

✅ Tasks:

    Create API endpoints for handling gift data:
        POST /gifts → Add a new gift
        GET /gifts → Fetch all gifts
        PUT /gifts/:id → Edit a gift
        DELETE /gifts/:id → Remove a gift
    Implement validation checks (e.g., prevent empty gift names, ensure budgets are positive numbers).

📌 Deliverable: Backend logic fully functional with CRUD operations.

### Build the UI & Connect to Backend

✅ Goals:

    Create HTML templates & frontend layout.
    Connect UI to backend API.

✅ Tasks:

    Build frontend layout with a table to display gift lists.
    Create form pages for adding/editing gifts.
    Implement AJAX fetch requests to interact with the Go backend.

📌 Deliverable: Users can view and add gifts via the UI.

### Implement Budget Tracking & Gift Status

✅ Goals:

    Track total spending vs. budget.
    Allow users to mark gifts as purchased or pending.

✅ Tasks:

    Add a budget column to the Gifts table.
    Implement a toggle button for setting a gift’s status (purchased or pending).
    Display budget progress bar (e.g., "You’ve spent $50 out of $200").

📌 Deliverable: Users can track gift spending & manage gift status.

### Testing, Debugging & UI Enhancements

✅ Goals:

    Ensure everything is working smoothly & improve the UI.

✅ Tasks:

    Test adding, editing, deleting gifts & budget calculations.
    Fix bugs & responsiveness issues.
    Apply CSS improvements to refine the UI.

📌 Deliverable: A clean, polished, and fully working Gift Planner.

### Final Testing & Project Wrap-Up

✅ Goals:

    Perform final testing & optimizations.
    Record content for social media.

✅ Tasks:

    Stress-test the app (e.g., add multiple gifts, test edge cases).
    Ensure database queries are optimized.
    Record a recap video showing how the Gift Planner works.

📌 Deliverable: Final working Gift Planner ready for deployment & content creation.
