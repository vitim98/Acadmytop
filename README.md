body {
    font-family: sans-serif;
    background-color: #f4f4f4;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    background-color: #fff;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 400px;
}

h1 {
    color: #333;
    text-align: center;
    margin-bottom: 10px;
}

p {
    text-align: center;
    margin-bottom: 20px;
    color: #666;
}

.form-group {
    margin-bottom: 15px;
}

label {
    display: block;
    margin-bottom: 5px;
    color: #333;
}

input, select {
    width: 100%;
    padding: 10px;
    border: 1px solid #ddd;
    border-radius: 4px;
    box-sizing: border-box; /* Garante que o padding não aumente a largura total */
}

button {
    width: 100%;
    padding: 10px;
    background-color: #ff4500; /* Cor laranja energética */
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 16px;
}

button:hover {
    background-color: #e03e00;
}
