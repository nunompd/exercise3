# Exercise 3

### Level: Medior and Senior

- The company’s todo list app is growing and some structural refactors are needed:

  - Add routing for the dashboard and todo list features.
    - The routes should be as follow: /dashboard and /todo
  - You should add buttons in the app.component to direct the user to each individual route
    - A button redirecting to the home page “/” should also be available for the user
  - Use lazy loading to load each feature module
  - Todo items are now also comming from an integrated external app (function _getTodoItemsFromExternalApp_ on the todo.service is responsible for making these items available). All todo items must be unified and displayed to the user.

- This exercise explores:
  - General typescript/javascript concepts
  - Feature module and lazy loading
  - RxJS operators
  - Routing

---

### original readme

- The company’s todo list app is growing and some structural refactors are needed:
  - Add routing for the todo component
    - The route should be: /todo
  - Add 2 buttons in the app.component directing to:
    - The todo component (/todo route)
    - The app component (a way to clear the router-outlet and going back to the main route)
  - The routes should be rendered below the buttons inside the app.component
  - Create a feature module for the todo functionality and load it using lazy load
  - Todo items are now also comming from an integrated external app (function _getTodoItemsFromExternalApp_ on the todo.service is responsible for making these items available). All todo items must be unified and displayed to the user.
