/* Reset basic styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #ffffff; /* White background */
    color: #333333; /* Dark text color for contrast */
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    background-color: #ffffff; /* White container */
    padding: 2rem;
    border-radius: 8px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1); /* Subtle shadow for depth */
    max-width: 400px;
    width: 100%;
    border: 1px solid #e0e0e0; /* Light border for definition */
    text-align: center;
}

h1 {
    font-size: 1.75rem;
    margin-bottom: 1.5rem;
    color: #333333; /* Dark text for readability */
}

form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}

label {
    font-size: 1rem;
    color: #666666; /* Lighter gray for labels */
    text-align: left;
}

input[type="text"] {
    padding: 0.75rem;
    border: 1px solid #cccccc; /* Light border */
    border-radius: 4px;
    font-size: 1rem;
    width: 100%;
    background-color: #f9f9f9; /* Light gray background for inputs */
    color: #333333;
}

button {
    background-color: #007bff; /* Blue button */
    color: white;
    border: none;
    padding: 0.75rem;
    border-radius: 4px;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #0056b3; /* Darker blue on hover */
}

.result {
    margin-top: 1.5rem;
    text-align: center;
}

.result h2 {
    font-size: 1.25rem;
    color: #333333;
}

.result p {
    font-size: 1.5rem;
    color: #007bff;
    margin-top: 0.5rem;
}
