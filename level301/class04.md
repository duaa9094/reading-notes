## React Docs - Forms

1. What is a ‘Controlled Component’?

A Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.

3. How do we target what the user is entering if we have an event handler on an input field?

using event.target.name

## The Conditional (Ternary) Operator Explained

1. Why would we use a ternary operator?

to simplify your if-else statements that are used to assign values to variables. The ternary operator is commonly used when assigning post data or validating forms.


2. Rewrite the following statement using a ternary statement:

    if(x===y){
    console.log(true);
    } else {
    console.log(false);
    }

    x===y? true
             : false

