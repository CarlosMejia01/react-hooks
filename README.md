# React Hooks Collection

A collection of useful and reusable custom React hooks that can be integrated into any project. These hooks help manage common logic in React applications, reducing boilerplate code and improving maintainability.

1. **useCounter**  
   A custom hook to manage a counter state with the ability to increment, decrement, and reset the counter.

**Features**:
- Increment: Increases the counter by a specified value (default is 1).
- Decrement: Decreases the counter by a specified value (default is 1), with a safeguard to prevent going below 0.
- Reset: Resets the counter to its initial value.

2. **useFetch**  
   A custom hook to fetch data from an API, with caching support and automatic loading and error handling.

**Features**:
- Fetches data: Automatically fetches data from the provided URL.
- Loading state: Provides a loading state while the fetch request is being processed.
- Error handling: Handles errors in the fetch request and stores the error message.
- Caching: Caches the response data in localCache to prevent multiple requests to the same URL.

3. **useForm**  
   A custom hook to manage form state, handle input changes, and reset the form state.

**Features**:
- Form state management: Tracks and updates the form values in the component's state.
- Input change handling: Handles changes for each form input, updating the respective field in the state.
- Form reset: Resets the form back to its initial state.

4. **useTodo**  
   A custom hook to manage todos with functionality for adding, deleting, and toggling completion. It also persists the todos in localStorage to maintain state across sessions.

**Features**:
- Todo management: Add, remove, and toggle completion of todos.
- Persistence: Todos are saved in localStorage so they persist across page reloads.
- Counts: Provides the total number of todos and the number of pending todos.
- State management: Utilizes useReducer for state management to handle complex state changes.

### Customizing:

- If your hooks have different names, be sure to update them in both the list and the example usage.
- Update any URLs to point to your actual API or project pages if needed.
