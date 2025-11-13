# spoton1
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>SpotOn - Inicio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            max-width: 900px;
            margin: 20px auto;
            padding: 0 15px;
            color: #222;
            background: #fff;
        }
        h1, h2, h3 {
            color: #1a1a1a;
        }
        section {
            margin-bottom: 40px;
        }
        .perfil {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
        }
        .perfil img {
            max-width: 150px;
            margin-right: 20px;
            border-radius: 8px;
        }
        .instagram-link {
            margin: 20px 0;
        }
        .instagram-link a {
            text-decoration: none;
            color: #e4405f;
            font-weight: bold;
        }
        form {
            background: #f7f7f7;
            padding: 20px;
            border-radius: 8px;
            max-width: 450px;
        }
        label {
            display: block;
            margin-bottom: 8px;
            margin-top: 15px;
            font-weight: bold;
        }
        input, textarea {
            width: 100%;
            padding: 8px;
            font-size: 14px;
            border-radius: 4px;
            border: 1px solid #ccc;
            box-sizing: border-box;
        }
        button {
            margin-top: 15px;
            background-color: #1a73e8;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #135abf;
        }
    </style>
</head>
<body>
    <h1>SpotOn</h1>
    <p><em>Beleef een unieke ervaring</em></p>

    <section>
        <h2>Over SpotOn</h2>

        <div class="perfil">
            <img src="https://via.placeholder.com/150?text=Anouk" alt="Anouk" />
            <div>
                <h3>Anouk</h3>
                <p>Anouk is de levendige stem en ziel van SpotOn. Haar betoverende podiumprésence en artistieke expressiviteit brengen elk nummer tot leven en maken een diepe connectie met het publiek. Met een gedegen opleiding en een aangeboren passie voor muziek, brengt Anouk warmte en energie in elke uitvoering, zich aanpassend aan verschillende stijlen en sferen om te garanderen dat elk evenement speciaal en onvergetelijk is. Haar charisma en professionaliteit maken haar de emotionele motor van de groep, waardoor de muzikale ervaring van SpotOn naar een uniek niveau wordt gebracht.</p>
            </div>
        </div>

        <div class="perfil">
            <img src="https://via.placeholder.com/150?text=Rufly" alt="Rufly" />
            <div>
                <h3>Rufly</h3>
                <p>Ruffly is de virtuoze gitarist van SpotOn, bekend om zijn onberispelijke techniek en veelzijdige stijl die varieert van zachte ritmes tot energieke melodieën. Zijn muzikaal talent en creativiteit brengen diepte en dynamiek in elke uitvoering, en vullen de stem van Anouk en de pulserende bas van Sandy perfect aan. Ruffly beheerst niet alleen zijn instrument met meesterschap, maar brengt ook passie en emotie in elke noot over, waardoor elke voorstelling uniek en onvergetelijk wordt. Zijn vermogen om zich aan te passen aan verschillende genres en sferen maakt hem een fundamentele pijler binnen de groep.</p>
            </div>
        </div>

        <div class="perfil">
            <img src="https://via.placeholder.com/150?text=Sandy" alt="Sandy" />
            <div>
                <h3>Sandy</h3>
                <p>Sandy is de ritmische ziel van SpotON, de bassist die de stevige basis en het energieke ritme levert die elk muziekstuk draagt. Met een veelzijdige stijl en precieze techniek past Sandy zich moeiteloos aan verschillende genres aan en brengt intensiteit en diepte in de uitvoeringen van de groep. Zijn vermogen om perfect samen te werken met Ruffly en Anouk creëert een unieke harmonie die de aandacht van het publiek vasthoudt. Zijn professionaliteit en toewijding zijn duidelijk zichtbaar in elke optreden, waardoor SpotOn krachtig en samenhangend klinkt op elk evenement.</p>
            </div>
        </div>
    </section>

    <section class="instagram-link">
        <h2>Volg ons op Instagram</h2>
        <a href="https://www.instagram.com/spoton" target="_blank" rel="noopener noreferrer">@SpotOn</a>
    </section>

    <section>
        <h2>Contact</h2>
        <form action="https://formspree.io/f/your-form-id" method="POST">
            <label for="name">Naam:</label>
            <input type="text" id="name" name="name" required />

            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required />

            <label for="message">Bericht:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Verzenden</button>
        </form>
    </section>
</body>
</html>
