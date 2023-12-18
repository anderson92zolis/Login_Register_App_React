## Register Login App


![Login](https://github.com/anderson92zolis/Login_Register_App_React/blob/main/photo/Login.jpg)
![Register](https://github.com/anderson92zolis/Login_Register_App_React/blob/main/photo/register.jpg)


<br>


### Instructions

<br>

> Challenge: Without moving the userIsRegistered variable,
1. Show Login as the button text if userIsRegistered is true.
> Show Register as the button text if userIsRegistered is false.

2. Only show the Confirm Password input if userIsRegistered is false.
> Don't show it if userIsRegistered is true.

<br>


### Conditional Rendering 

Conditional rendering is a fundamental concept in React that allows you to show different components depending on a particular condition, we will learn how to use conditional rendering to:

> Show the login screen if the user is registered, and the register screen if the user is not registered.
> Show the confirm password input if the user is registering, and not show it if the user is logging in.

**Step 1: Passing Props**

The first step is to pass a prop called isRegistered from the App.js component to the form.jsx component. This prop will be used to determine whether to show the login or register screen.

**Step 2: Using the AND Operator**

The second step is to use the AND operator to check whether the isRegistered prop is equal to false inside the Form.jsx component. If it is, then the confirm password input will be shown. Otherwise, it will not be shown.

Alternative Approach: Ternary Operator

An alternative approach to using the AND operator is to use a ternary operator. The ternary operator is a concise way to evaluate a condition and return one value if the condition is true, and another value if the condition is false.

Shortest Possible Way

> !props.isRegistered is equivalent to props.isRegistered === false. This allows you to write the entire conditional rendering statement in one line.

Conclusion

Conditional rendering is a powerful tool that can be used to create dynamic and responsive user interfaces. By learning how to use conditional rendering, you can build more sophisticated React applications.

