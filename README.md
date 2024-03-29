<!DOCTYPE html>
<html lang="fr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: "Poppins", sans-serif;
            background-color: #e6f7ff;
            color: #336699;
        }

        /* Navbar */
.navbar {
    display: flex;
    align-items: center;
    padding: 20px;
    background-color: #005580;
    color: #fff;
}

nav {
    flex: 1;
    text-align: right;
}

nav ul {
    list-style-type: none;
    margin: 0;
}

nav ul li {
    display: inline-block;
    margin-right: 20px;
}

nav ul li:last-child {
    margin-right: 0;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
    font-size: 16px;
    transition: color 0.3s ease;
}

nav ul li a:hover {
    color: #66c2ff;
}


        p {
            color: #336699;
        }

        .container {
            max-width: 1300px;
            margin: auto;
            padding-left: 25px;
            padding-right: 25px;
        }

        .header {
            background: radial-gradient(#ccf2ff, #99e6e6);
        }

        .header .row {
            margin-top: 70px;
        }

        .col-2 h1 {
            font-size: 50px;
            line-height: 60px;
            margin: 25px 0;
            color: #336699;
        }

        .col-2 p {
            color: #336699;
        }

        .btn {
            display: inline-block;
            background: #005580;
            color: #fff;
            padding: 8px 30px;
            margin: 30px 0;
            border-radius: 30px;
            transition: background 0.3s ease;
        }

        .btn:hover {
            background: #003366;
        }

        .categories {
            margin: 70px 0;
        }

        .col-3 img {
            width: 100%;
        }

        .small-container {
            max-width: 1080px;
            margin: auto;
            padding-left: 25px;
            padding-right: 25px;
        }

        .title {
            text-align: center;
            margin: 0 auto 80px;
            position: relative;
            line-height: 60px;
            color: #336699;
        }

        .title::after {
            content: "";
            background: #005580;
            width: 80px;
            height: 5px;
            border-radius: 5px;
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translate(-50%);
        }

        .offer {
            background: radial-gradient(#ccf2ff, #99e6e6);
            margin-top: 80px;
            padding: 30px 0;
        }

        small {
            color: #336699;
        }

        .footer {
            background: #005580;
            color: #99ccff;
            font-size: 14px;
            padding: 60px 0 20px;
        }

        .footer p {
            color: #99ccff;
        }

        .footer h3 {
            color: #fff;
            margin-bottom: 20px;
        }

        ul {
            list-style-type: none;
        }

        .footer hr {
            border: none;
            background: #99ccff;
            height: 1px;
            margin: 20px 0;
        }

        .copyright {
            text-align: center;
        }

        @media only screen and (max-width: 800px) {
            nav ul {
                position: absolute;
                top: 70px;
                left: 0;
                background: #003366;
                width: 100%;
                overflow: hidden;
                transition: max-height 0.5s;
            }

            nav ul li {
                display: block;
                margin-right: 50px;
                margin-top: 10px;
                margin-bottom: 10px;
            }

            nav ul li a {
                color: #fff;
            }
        }
    </style>
</head>

<body>
    <div class="header">
        <div class="container">
            <div class="navbar">
                <nav>
                    <ul id="MenuItems">
                        <li>Accueil</li>
                        <li>Produits</li>
                        <li>À propos</li>
                        <li>Contact</li>
                        <li>Compte</li>
                    </ul>
                </nav>
            </div>
            <div class="row">
                <div class="col-2">
                    <h1>
                        Donnez un nouveau style <br />
                        à votre entraînement !
                    </h1>
                    <p>
                        Le succès n'est pas toujours une question de grandeur. C'est une question de régularité.
                        Le travail acharné constant mène au succès. La grandeur viendra.
                    </p>
                    <a href="#" target="_blank" rel="noopener noreferrer" class="btn">Explorer maintenant →</a>
                </div>
            </div>
        </div>
    </div>

    <!-- Catégories en vedette -->
    <div class="categories">
        <div class="small-container">
            <div class="row">
                <div class="col-3">
                    <img src="https://i.ibb.co/sqnY1pG/category-1.jpg" alt="" />
                </div>
                <div class="col-3">
                    <img src="https://i.ibb.co/GCJLQRQ/category-2.jpg" alt="" />
                </div>
                <div class="col-3">
                    <img src="https://i.ibb.co/wYsXqP5/category-3.jpg" alt="" />
                </div>
            </div>
        </div>
    </div>

    <!-- Produits en vedette -->
    <div class="small-container">
        <h2 class="title">Produits en vedette</h2>
        <div class="row">
            <!-- Les autres produits en vedette vont ici... -->
        </div>
        <h2 class="title">Derniers produits</h2>
        <div class="row">
            <!-- Les autres derniers produits vont ici... -->
        </div>

        <div class="row">
            <!-- Plus de produits vont ici... -->
        </div>
    </div>
    <!-- Offre -->
    <div class="offer">
        <div class="small-container">
            <div class="row">
                <div class="col-2">
                    <img src="https://i.ibb.co/HF5TncZ/exclusive.png" alt="" class="offer-img" />
                </div>
                <div class="col-2">
                    <p>Exclusivement disponible sur RedStore</p>
                    <h1>Smart Band 4</h1>
                    <small>Le Mi Smart Band 4 dispose d'un écran couleur AMOLED tactile complet 39,9 % plus grand (que le Mi Band 3) avec luminosité réglable, pour une clarté optimale.</small>
                    <br />
                    <a href="#" class="btn">Acheter maintenant →</a>
                </div>
            </div>
        </div>
    </div>

    <script>
        var MenuItems = document.getElementById('MenuItems');
        MenuItems.style.maxHeight = '0px';

        function menutoggle() {
            if (MenuItems.style.maxHeight == '0px') {
                MenuItems.style.maxHeight = '200px';
            } else {
                MenuItems.style.maxHeight = '0px';
            }
        }
    </script>
</body>

</html>
