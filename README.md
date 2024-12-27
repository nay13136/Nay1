document.addEventListener("DOMContentLoaded", () => {
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
