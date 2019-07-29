# ReactJS Refactoring

Run the following command to get a basic ReactJS application setup:

```
npx create-react-app my-app
cd my-app
yarn start
```

1. Create an state object inside my-app/src/App.js with a dummy person's first name, last name, address, phone number, email address, and last login date.

2. Build a form with input fields that allow you to modify each of the attributes of the state object, adding separate onChange handlers for each input field.

3. Create a separate JS file and move the initial state object into the other file.

4. Create a component named Input.js that has the following features:

* render function that takes in the value and name from props and applies it to an input field.

* onChange event handler that takes in an onChange from props and calls it with the name and the newest value in the event.

5. Replace all off the input fields added to App.js with the Input.js component you created.

6. Create a single generic onChange function that accepts a name and value, which changes the state of the name to the value. Use this for all of the input fields.

After you have completed all of the exercises, commit your changes with the following command:

```
git commit -am "ReactJS Refactoring Examples"
```
