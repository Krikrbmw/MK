<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Montage & Reparatur - Fenster, Türen, Rollläden</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0; padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
        }
        main {
            max-width: 900px;
            margin: 20px auto;
            padding: 0 20px;
        }
        h1, h2 {
            color: #004080;
        }
        section {
            background: white;
            padding: 15px 20px;
            margin-bottom: 20px;
            border-radius: 5px;
            box-shadow: 0 0 8px rgba(0,0,0,0.1);
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
        img {
            max-width: 100%;
            border-radius: 5px;
            margin-top: 10px;
        }
        form {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }
        label {
            font-weight: bold;
        }
        input, textarea {
            padding: 8px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1em;
            resize: vertical;
        }
        button {
            background-color: #004080;
            color: white;
            border: none;
            padding: 12px;
            font-size: 1em;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #003060;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #004080;
            color: white;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <h1>Montage & Reparatur von Fenstern, Türen, Rollläden und Innentüren</h1>
        <p>Ihr zuverlässiger Partner für professionelle Handwerksarbeiten</p>
    </header>
    <main>
        <section>
            <h2>Unsere Dienstleistungen</h2>
            <ul>
                <li>Montage von Fenstern und Türen</li>
                <li>Reparatur und Wartung von Rollläden</li>
                <li>Austausch und Instandsetzung von Innentüren</li>
                <li>Notfallservice bei Tür- und Rollladenproblemen</li>
            </ul>
            <img src="https://images.unsplash.com/photo-1581090700227-d42a89b5b6af?auto=format&fit=crop&w=900&q=80" alt="Fenster Montage" />
        </section>
        <section>
            <h2>Warum uns wählen?</h2>
            <p>Wir bieten Ihnen langjährige Erfahrung, zuverlässigen Service und schnelle Ausführung. Unser Team arbeitet sorgfältig und verwendet nur hochwertige Materialien.</p>
            <img src="https://images.unsplash.com/photo-1519222970733-f546218fa6d7?auto=format&fit=crop&w=900&q=80" alt="Handwerker bei der Arbeit" />
        </section>
        <section>
            <h2>Kontaktieren Sie uns</h2>
            <p>Für ein unverbindliches Angebot oder Beratung erreichen Sie uns unter:</p>
            <p><strong>Telefon:</strong> 01234 567890<br />
            <strong>E-Mail:</strong> info@montage-reparatur.de</p>
            <form action="mailto:info@montage-reparatur.de" method="post" enctype="text/plain">
                <label for="name">Name</label>
                <input type="text" id="name" name="Name" required />

                <label for="email">E-Mail</label>
                <input type="email" id="email" name="fensterundturenmk@gmail.com" required />

                <label for="message">Nachricht</label>
                <textarea id="message" name="Nachricht" rows="5" required></textarea>

                <button type="submit">Senden</button>
            </form>
        </section>
    </main>
    <footer>
        &copy; 2025 Montage & Reparatur GmbH | Alle Rechte vorbehalten
    </footer>
</body>
</html>
