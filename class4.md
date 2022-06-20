#Questions 
1. What is a ‘Controlled Component’?
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
3. How do we target what the user is entering if we have an event handler on an input field?

1. A controlled component is an input form element whose value is controlled by React. It also has mutable state and can only be updated with set state.
2. We dont have a choice. The form re-renders anytime the state changes. If the user is inputting data, it will be rerendered without us stopping it unless we change how the component handles the information. This is more convenient in a controlled component because you only need to update it in one place.
3.  handleChange(event) {
    this.setState({value: event.target.value});
  }
  
  
1. Why would we use a ternary operator?
2. Rewrite the following statement using a ternary statement:

1.WTF. It is basically a one line if statement that outputs the else. If something condition is true, do whatever.
x===y = (true ? 'Yes' : 'No';)


## Things I want to know more about
components
