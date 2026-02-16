/* style.css */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #0f0f1a;
    color: #fff;
}

header {
    background: linear-gradient(90deg, #ff0055, #7700ff);
    padding: 20px;
    text-align: center;
    font-size: 32px;
    font-weight: bold;
}

nav {
    display: flex;
    justify-content: center;
    background: #1a1a2e;
    padding: 12px;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: 0.3s;
}

nav a:hover {
    color: #ff0055;
}

.container {
    padding: 40px;
    text-align: center;
}

h2 {
    margin-bottom: 20px;
    font-size: 28px;
    border-bottom: 2px solid #7700ff;
    display: inline-block;
    padding-bottom: 5px;
}

.cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background: #1f1f2e;
    width: 220px;
    border-radius: 10px;
    overflow: hidden;
    transition: transform 0.3s, background 0.3s;
}

.card img {
    width: 100%;
    height: 300px;
    object-fit: cover;
}

.card h3 {
    padding: 10px;
    font-size: 20px;
}

.card p {
    padding: 0 10px 10px;
    font-size: 14px;
    color: #ccc;
}

.card:hover {
    transform: scale(1.05);
    background: #292940;
}

footer {
    background: #1a1a2e;
    text-align: center;
    padding: 15px;
    margin-top: 40px;
    font-size: 14px;
}

@media(max-width: 768px) {
    .cards {
        flex-direction: column;
        align-items: center;
    }
}
