# Interactive-Quiz-Application

# Interactive Quiz Application

## Observations and Learnings

1. **State Management with `useState`**: This project helped me understand how to effectively manage and update the component state using the `useState` hook in React. I learned how to define multiple state variables (`currentQuestion`, `score`, and `showScore`) and update them based on user interactions.

2. **Conditional Rendering**: Depending on whether the quiz has been completed or not, the component renders either the quiz questions or the final score section. This conditional rendering was achieved using a ternary operator and the `showScore` state variable.

3. **Handling User Input**: The application demonstrates how to handle user input, such as selecting an answer option from the radio buttons. The `handleAnswerSelect` function updates the score and moves to the next question based on the user's selection.

4. **Iterating Over Arrays**: The `map` function was used to render the list of answer options for each question dynamically. This showcases how to iterate over arrays and create dynamic components in React.

Overall, this assignment provided a solid understanding of state management, conditional rendering, handling user input, iterating over arrays, component lifecycle, event handling, and styling in React components. Building an interactive application like this quiz helped me gain practical experience in using the `useState` hook and managing component state effectively.