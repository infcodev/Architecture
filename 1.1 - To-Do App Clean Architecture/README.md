# 1.1 To-Do App with Clean Architecture

This project is a practical exercise to apply and understand Clean Architecture principles by building a cross-platform to-do app.

## Learning Goals (Detailed)

1. **UI Implementation**
   - Build a native iOS app using SwiftUI for the to-do list.
   - Build a web app using React with the same features and similar structure.
   - Focus on clean separation between UI, logic, and data layers.

2. **Backend for Sync**
   - Create a simple backend (Node.js) to store and sync tasks.
   - Expose REST APIs for CRUD operations.
   - Handle user sessions or basic authentication if possible.

3. **Offline Mode**
   - Implement local storage for tasks in both apps (Core Data/SQLite for iOS, IndexedDB/LocalStorage for web).
   - Enable the app to work without internet and sync changes when back online.

4. **Layered Architecture & Diagrams**
   - Draw diagrams showing the architecture (layers, modules, data flow).
   - Document each layer: UI, Use Cases, Domain, Data, Infrastructure.

5. **Modules & Responsibilities**
   - Split code into clear modules: UI, business logic, data access, networking.
   - Write a README section or diagram explaining what each module does.

6. **Mocks & Real Repos**
   - Create mock repositories for testing (in-memory or fake data).
   - Swap between mock and real repositories easily (dependency injection or similar).

7. **DTOs vs Models**
   - Define DTOs (Data Transfer Objects) for communication with backend.
   - Define domain models for business logic.
   - Map between DTOs and models explicitly and document the difference.

---

**Extra:**
- Try TDD for at least one module.
- Document problems, decisions, and learnings in a journal or as comments.
- Keep everything as simple as possible, but clear!
