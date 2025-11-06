⚛️ React State & Props Exercise
🎯 Goal

Practice using React state and props by building a simple app that displays and manages user profiles.

🧩 Instructions
1. Create data in App.js

Create an array containing five person objects.

Each object should include:

firstName

lastName

age

hobby

2. Create a Profile component

The component should receive a person object as a prop.

It will be responsible for displaying that person’s information.

3. Display profiles dynamically

Render five Profile components, each receiving a different person object as props.

Use a loop (e.g., map()) to generate them.

Show/Hide behavior:

Initially, only show each person’s first name.

Add a button labeled "Show more".

When clicked:

Display all the person’s details (last name, age, hobby) below the first name.

Change the button text to "Show less".

When "Show less" is clicked:

Hide the additional details again.

Change the button text back to "Show more".

4. Add Dark Mode functionality

Create a “Dark Mode” toggle button that changes:

Background color → dark

Text color → light

The same button should toggle back to light mode (light background, dark text).

Use state to manage the mode.

🌟 Extra Challenge

Create a component named <AddProfile /> that includes:

Input fields for adding new people (first name, last name, age, hobby).

Functionality to insert the new person into the array of profiles.

💡 Tips

Use useState to manage both the profiles and dark mode.

Use conditional rendering for the show/hide logic.

Apply conditional classes or inline styles to switch between light and dark themes.