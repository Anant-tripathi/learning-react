### Creating First Component

- The first letter is always capital in the component function name
- Must return something

#### JSX Rules

- Return single elements

  - React Fragment - It is used to group different elements into one before
    returning

  ```js
  return <React.Fragment> ...rest of the return code </React.Fragment>;
  /// shorthand for the above is:
  return <> ...rest of the return code </>;
  ```

- Camel case property naming convention
- className insted of class
- close every element
- If not using parentheses then make sure that the opening tag is in the same
  line as the return statement
