/* Styles généraux */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    color: #333;
    line-height: 1.6;
}

/* Header */
header {
    background-color: #007BFF;
    color: white;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header nav {
    margin-top: 10px;
}

header nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-weight: bold;
}

header nav a:hover {
    text-decoration: underline;
}

/* Section produits */
.container {
    max-width: 1200px;
    margin: 20px auto;
    padding: 0 15px;
}

.products {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    justify-content: center;
}

.product-card {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 5px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    width: 300px;
    padding: 15px;
    text-align: center;
    transition: transform 0.3s, box-shadow 0.3s;
}

.product-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}

.product-card img {
    max-width: 100%;
    border-radius: 5px;
}

.product-card h3 {
    font-size: 1.2em;
    margin: 10px 0;
}

.product-card p {
    color: #555;
    font-size: 0.9em;
}

.product-card .price {
    font-size: 1.5em;
    color: #007BFF;
    margin: 10px 0;
}

.product-card button {
    background-color: #007BFF;
    color: white;
    border: none;
    border-radius: 5px;
    padding: 10px 20px;
    cursor: pointer;
    font-size: 1em;
    transition: background-color 0.3s;
}

.product-card button:hover {
    background-color: #0056b3;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 15px 0;
    margin-top: 20px;
}

footer p {
    margin: 0;
    font-size: 0.9em;
}![1000019638](https://github.com/user-attachments/assets/ed3cae3a-87a6-478f-9943-c3dc916a3278)
![1000019639](https://github.com/user-attachments/assets/08b398d9-1c83-4ccd-bca9-e9686f6f4741)
buttons.forEach(button => {
    button.addEventListener("click", () => {
        alert("Produit ajouté au panier !");
    });
});document.addEventListener("DOMContentLoaded", () => {
    const buttons = document.querySelectorAll(".btn-add");
    
    buttons.forEach(button => {
        button.addEventListener("click", () => {
            alert("Produit ajouté au panier !");
        });
    });
});<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Moderne</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Mon E-Commerce</div>
        <nav>
            <ul>
                <li><a href="#accueil">Accueil</a></li>
                <li><a href="#produits">Produits</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="accueil" class="hero">
            <h1>Bienvenue sur notre boutique en ligne</h1>
            <p>Découvrez nos produits modernes et de qualité.</p>
            <a href="#produits" class="btn">Voir les produits</a>
        </section>
        
        <section id="produits" class="products">
            <h2>Nos Produits</h2>
            <div class="product-list">
                <!-- Exemple de produit -->
                <div class="product-item">
![1000019638](https://github.com/user-attachments/assets/6ae23f64-b045-4248-8dda-44b1730595e8)
![1000019639](https://github.com/user-attachments/assets/c623132c-aeb4-4146-b670-54af67e914b2)
                    <img src="https://via.placeholder.com/150" alt="Produit">
                    <h3>Produit 1</h3>
                    <p>Prix : 50€</p>
                    <button class="btn-add">Ajouter au panier</button>
                </div>
            </div>
        </section>
    </main>
    
    <footer>
        <p>© 2024 Mon E-Commerce - Tous droits réservés</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>2024![1000019638](https://github.com/user-attachments/assets/3f4591de-735e-4b8c-bf51-b6d325f598b7)
![1000019639](https://github.com/user-attachments/assets/dd2dbd0c-953d-4ebc-b127-4a07c386cd9c)
