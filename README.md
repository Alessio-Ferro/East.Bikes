<!DOCTYPE html>
<html lang="de">
<head>
    <title>East-Bikes Motorradshop</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
    <style>
        body {
            padding-top: 3.5rem;
        }
        .produkt {
            margin-bottom: 2rem;
        }
        .produkt img {
            width: 100%;
            height: auto;
        }
        .kategorie {
            margin-top: 2rem;
            margin-bottom: 2rem;
        }
    </style>
</head>
<body>

    <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
        <a class="navbar-brand" href="#">East-Bikes</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarCollapse" aria-controls="navbarCollapse" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarCollapse">
            <ul class="navbar-nav mr-auto">
                <li class="nav-item active"><a class="nav-link" href="#home" data-toggle="collapse" data-target=".multi-collapse">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#motorräder" data-toggle="collapse" data-target=".multi-collapse">Motorräder</a></li>
                <li class="nav-item"><a class="nav-link" href="#roller" data-toggle="collapse" data-target=".multi-collapse">Roller</a></li>
                <li class="nav-item"><a class="nav-link" href="#atvs" data-toggle="collapse" data-target=".multi-collapse">ATV/Quads</a></li>
                <li class="nav-item"><a class="nav-link" href="#kontakt" data-toggle="collapse" data-target=".multi-collapse">Kontakt</a></li>
            </ul>
        </div>
    </nav>

    <main role="main" class="container">
        <div id="home" class="mt-3 multi-collapse collapse show kategorie">
            <h1>Willkommen bei East-Bikes!</h1>
            <p class="lead">Dein vertrauenswürdiger Fahrzeugshop für GTA5 RP.</p>
        </div>

        <div id="motorräder" class="multi-collapse collapse kategorie">
            <h2>Unsere Motorräder</h2>
            <div class="row">
                <!-- Füge hier die einzelnen Motorräder hinzu -->
                <div class="col-md-4 produkt">
                    <img src="motorrad1.jpg" alt="Motorrad 1" class="img-thumbnail">
                    <h3>Motorrad 1</h3>
                    <p>Beschreibung für Motorrad 1...</p>
                </div>
                <div class="col-md-4 produkt">
                    <img src="motorrad2.jpg" alt="Motorrad 2" class="img-thumbnail">
                    <h3>Motorrad 2</h3>
                    <p>Beschreibung für Motorrad 2...</p>
                </div>
            </div>
        </div>

        <div id="roller" class="multi-collapse collapse kategorie">
            <h2>Unsere Roller</h2>
            <div class="row">
                <!-- Füge hier die einzelnen Roller hinzu -->
                <div class="col-md-4 produkt">
                    <img src="roller1.jpg" alt="Roller 1" class="img-thumbnail">
                    <h3>Roller 1</h3>
                    <p>Beschreibung für Roller 1...</p>
                </div>
                <div class="col-md-4 produkt">
                    <img src="roller2.jpg" alt="Roller 2" class="img-thumbnail">
                    <h3>Roller 2</h3>
                    <p>Beschreibung für Roller 2...</p>
                </div>
            </div>
        </div>

        <div id="atvs" class="multi-collapse collapse kategorie">
            <h2>Unsere ATV/Quads</h2>
            <div class="row">
                <!-- Füge hier die einzelnen ATV/Quads hinzu -->
                <div class="col-md-4 produkt">
                    <img src="atv1.jpg" alt="ATV 1" class="img-thumbnail">
                    <h3>ATV 1</h3>
                    <p>Beschreibung für ATV 1...</p>
                </div>
                <div class="col-md-4 produkt">
                    <img src="atv2.jpg" alt="ATV 2" class="img-thumbnail">
                    <h3>ATV 2</h3>
                    <p>Beschreibung für ATV 2...</p>
                </div>
            </div>
        </div>

        <div id="kontakt" class="multi-collapse collapse kategorie">
            <h2>Kontaktiere uns</h2>
            <p>Telefon: 123-456-7890</p>
            <p>E-Mail: info@east-bikes.de</p>
        </div>
    </main>

    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
</body>
</html>

