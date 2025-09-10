
/* Reset default styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

/* Body */
body {
    line-height: 1.6;
    color: #fff; /* white text for contrast */
    background-color: #ff0000; /* bright red background */
}

/* Header */
header {
    background: #b20000; /* darker red for header */
    color: white;
    padding: 20px 0;
}
header h1 {
    text-align: center;
    margin-bottom: 10px;
}
nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 20px;
}
nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}
nav a:hover {
    text-decoration: underline;
}

/* Hero Section */
#hero {
    background: #ff4d4d; /* lighter red for hero */
    padding: 100px 20px;
    text-align: center;
}
#hero .btn {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 25px;
    background: #800000; /* dark red button */
    color: white;
    text-decoration: none;
    border-radius: 5px;
}
#hero .btn:hover {
    background: #660000;
}

/* Sections */
section {
    padding: 60px 20px;
}
.container {
    max-width: 900px;
    margin: auto;
}
h2 {
    text-align: center;
    margin-bottom: 20px;
}

/* Form */
form {
    display: flex;
    flex-direction: column;
    gap: 15px;
}
input, textarea {
    padding: 10px;
    border: 1px solid #fff;
    border-radius: 5px;
    background: #ff6666;
    color: #fff;
}
input::placeholder, textarea::placeholder {
    color: #ffe6e6; /* light placeholder text */
}
button {
    padding: 10px;
    background: #800000;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}
button:hover {
    background: #660000;
}

/* Footer */
footer {
    background: #b20000;
    color: white;
    text-align: center;
    padding: 20px 0;
}
