This project looks to focus on the inner working of a Reux store. I have chosen to keep the UI quite simple but still elegant with plain HTML, CSS and JavaScript used. However, I have implemented a store that with facilities that allow the user to:
1. Retrieve the state of the application at any time.
2. Change the state by performing an event which triggers our pure function, the reducer.
3. Listening to changes in the state by means of a subscribe function which registers listeners that are called once the state changes.

These facilities are to ensure that the Todos app - any app - can have its state centrally located and predictable when it changes.
