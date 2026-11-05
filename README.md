/* --- Global Reset & Base Styles --- */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

/* --- Centered Layout Background --- */
body {
    background-color: #f4f7f6;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

/* --- Card Container --- */
.registration-container {
    background-color: #ffffff;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 400px;
}

/* --- Typography --- */
h2 {
    text-align: center;
    margin-bottom: 24px;
    color: #333333;
}

/* --- Form Elements --- */
.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    margin-bottom: 8px;
    color: #666666;
    font-size: 14px;
}

.form-group input {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-size: 14px;
    outline: none;
    transition: border-color 0.2s ease;
}

/* --- Input Focus State --- */
.form-group input:focus {
    border-color: #2ecc71;
}

/* --- Submit Button --- */
.btn-submit {
    width: 100%;
    padding: 12px;
    background-color: #2ecc71;
    border: none;
    border-radius: 4px;
    color: white;
    font-size: 16px;
    font-weight: bold;
    cursor: pointer;
    transition: background-color 0.2s ease;
}

.btn-submit:hover {
    background-color: #27ae60;
}

/* --- Bottom Link Navigation --- */
.login-link {
    text-align: center;
    margin-top: 20px;
    font-size: 14px;
    color: #666666;
}

.login-link a {
    color: #2ecc71;
    text-decoration: none;
}

.login-link a:hover {
    text-decoration: underline;
}

