# Store Folder

This folder contains the application's global state management logic.  
You can use Zustand, Redux Toolkit, here.

### ✅ If using Zustand:

- `bookStore.js` → Manages books' state.
- `userStore.js` → Manages users' state.

### ✅ If using Redux Toolkit:

- `bookSlice.js` → Manages book-related actions.
- `userSlice.js` → Manages user-related actions.
- `index.js` → Combines all reducers into a store.

Use `store/index.js` as the main entry point for Redux.
