Perform the following actions inside of the `src/setupTest.js` file:
1. Import the `configure` method from the `enzyme` package.
2. Import the `Adapter` class from `enzyme-adapter-react-16`.
3. Configure the `enzyme` adapter to be the default adapter in our project.
   1. Invoke the `configure` method.
   2. Pass it an object with a **key** of `adapter`, and its **value** should be a new instantiated instance of the `Adapter` class that was imported earlier.