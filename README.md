/* Global Styles */
body {
    font-family: 'Roboto', sans-serif; /* Use a clean, modern font */
    background-color: #f4f4f4; /* Light gray background */
    color: #333333; /* Dark gray text */
    margin: 0;
    padding: 0;
}

/* Navigation Menu */
nav {
    background-color: #000000; /* Black navigation background */
    padding: 1rem;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-around;
}

nav ul li {
    margin: 0;
}

nav ul li a {
    color: #ffffff; /* White text */
    text-decoration: none;
    font-size: 1.1rem;
    padding: 0.5rem 1rem;
    transition: color 0.3s;
}

nav ul li a:hover {
    color: #ffd700; /* Gold hover effect */
}

/* Headers */
h1, h2, h3 {
    color: #000000; /* Black headers */
}

/* Button Styles */
button {
    background-color: #000000; /* Black button */
    color: #ffd700; /* Gold text */
    border: none;
    padding: 0.75rem 1.5rem;
    font-size: 1rem;
    cursor: pointer;
    transition: background-color 0.3s;
}

button:hover {
    background-color: #333333; /* Dark gray on hover */
}

/* Footer */
footer {
    background-color: #000000; /* Black footer */
    color: #ffffff; /* White text */
    text-align: center;
    padding: 1rem 0;
    margin-top: 2rem;
}

/* Page-Specific Content */
.page-banner {
    background-color: #ffd700; /* Gold banner */
    color: #000000; /* Black text */
    padding: 2rem;
    text-align: center;
    margin-bottom: 1rem;
}
