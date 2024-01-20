!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Site-creations-GRT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        form {
            max-width: 600px;
            margin: 0 auto;
        }

        label, input {
            display: block;
            margin-bottom: 10px;
        }

        button {
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <h1>Création de sites web pour entreprises</h1>

    <form id="websiteForm">
        <label for="companyName">Nom de l'entreprise :</label>
        <input type="text" id="companyName" name="companyName" required>

        <label for="websiteType">Type de site web :</label>
        <select id="websiteType" name="websiteType" required>
            <option value="static">Site statique</option>
            <option value="dynamic">Site dynamique</option>
        </select>

        <label for="features">Fonctionnalités souhaitées :</label>
        <textarea id="features" name="features" rows="4"></textarea>

        <button type="button" onclick="submitForm()">Envoyer la demande</button>
    </form>

    <script>
        function submitForm() {
            var companyName = document.getElementById('companyName').value;
            var websiteType = document.getElementById('websiteType').value;
            var features = document.getElementById('features').value;

            // Ici, vous pouvez envoyer ces données au backend pour traitement
            // Par exemple, en utilisant Ajax pour envoyer une requête au serveur
            // ou en utilisant un formulaire qui pointe vers un script de traitement

            // Dans un cas réel, vous devriez utiliser une solution backend appropriée
            // pour gérer les données, les stocker dans une base de données, etc.
        }
    </script>
</body>
</html>
