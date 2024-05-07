Breakdown of the code:

- **State Initialization**: The `constructor` initializes the state with a random quote and author from the `quotes` array. If the array is empty, it defaults to the first quote.
- **Color Change**: The `handleChange` method changes the background color of the page to a random color using the `getRandomColor` function.
- **Quote Update**: The same method also updates the state with a new random quote and author whenever the "New Quote" button is clicked.
- **Social Media Links**: The component includes social media buttons that allow users to share the current quote on Twitter and Tumblr.
- **Rendering**: The `render` method returns JSX that displays the quote, author, and social media buttons, and includes the "New Quote" button to trigger a new quote.
