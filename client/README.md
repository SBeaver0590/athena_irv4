
# React Client Project

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Root Folder Layout

The root folder contains the following items:

* `public` - Contains the React application's `favicon.ico` and `index.html` files
* `src` - The source code for the React application
* `.gitignore` - The `.gitignore` file generated by the Create React App tooling
* `package-lock.json` - Generated by npm to describe the application's exact dependency tree
* `package.json` - The npm configuration file generated by the Create React App tooling
* `README.md` - The README file that you're currently reading

### `src` Folder Layout

The `src` folder contains the following items:

* `components` - Contains the components for the React application
  * `CourseCard.js` - Renders a course card on the "Courses" page
  * `CourseDetail.js` - Renders the "Course Detail" page
  * `Courses.js` - Renders the "Courses" page
  * `CreateCourse.js` - Renders the "Create Course" page
  * `Forbidden.js` - Renders the "Forbidden" page that displays when a user attempts to browse to a page in the React application that they don't have permissions to view
  * `Form.js` - Renders a form
  * `FormField.js` - Renders a form field
  * `Header.js` - Renders the React application's header
  * `NewCourseCard.js` - Renders the "New Course" card on the "Courses" page
  * `NotFound.js` - Renders the "Not Found" page that displays when a user browses to a page that doesn't exist
  * `UnhandledError.js` - Renders a generic "Error" page that displays when an unhandled error occurs in the React application
  * `UpdateCourse.js` - Renders the "Update Course" page
  * `UserSignIn.js` - Renders the "Sign In" page
  * `UserSignOut.js` - Renders the "Sign Out" page
  * `UserSignUp.js` - Renders the "Sign Up" page
* `styles` - Contains the CSS styles for the React application
  * `global.css` - CSS file compiled from the original Sass files
  * `new.css` - Various CSS tweaks since the last compilation of the Sass files
* `App.js` - The main component for the React application that contains the React Router configuration
* `App.test.js` - Placeholder test file generated by the Create React App tooling
* `config.js` - Simple configuration file for the React application
* `Context.js` - Renders a React Context Provider component and defines a function that returns a higher-order component that wraps the a component in a React Context Consumer component
* `Data.js` - Defines a JavaScript class that includes methods for interacting with the Express REST API
* `index.js` - The entry point or root of the React application
* `PrivateRoute.js` - Renders a component for defining a React Router route that requires the user to be authenticated in order to view the route's associated component