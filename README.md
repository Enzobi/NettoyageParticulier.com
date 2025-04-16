<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Devis - NettoyageParticulier.com</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      background-color: #f4f8fb;
      color: #333;
      line-height: 1.6;
    }
    header {
      background-color: #008cba;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    .container {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.08);
    }
    h2 {
      font-size: 2em;
      color: #007b9e;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, textarea {
      padding: 10px;
      font-size: 1em;
      border-radius: 6px;
      border: 1px solid #ccc;
    }
    button {
      background-color: #007b9e;
      color: white;
      padding: 10px 20px;
      border-radius: 6px;
      font-size: 1.1em;
      cursor: pointer;
    }
    button:hover {
      background-color: #005f78;
    }
  </style>
</head>
<body>
  <header>
    <h1>Demandez un devis personnalisé</h1>
    <p>Complétez le formulaire ci-dessous et nous vous enverrons un devis adapté à vos besoins.</p>
  </header>

  <div class="container">
    <h2>Formulaire de demande de devis</h2>
    <form action="#">
      <label for="nom">Nom :</label>
      <input type="text" id="nom" name="nom" required>

      <label for="email">Email :</label>
      <input type="email" id="email" name="email" required>

      <label for="message">Description du service souhaité :</label>
      <textarea id="message" name="message" rows="4" required></textarea>

      <button type="submit">Envoyer la demande</button>
    </form>
  </div>
</body>
</html>
