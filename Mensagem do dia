<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Mensagem do Dia</title>
  <style>
    * {
      box-sizing: border-box;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
    }

    body {
      background: linear-gradient(135deg, #ffafbd, #ffc3a0);
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    .card {
      background: white;
      padding: 2rem;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
      max-width: 400px;
      text-align: center;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.02);
    }

    .message {
      font-size: 1.3rem;
      color: #333;
      margin-bottom: 1.5rem;
      min-height: 60px;
      transition: opacity 0.5s ease;
    }

    button {
      padding: 0.8rem 1.5rem;
      background-color: #ff6f61;
      color: white;
      border: none;
      border-radius: 10px;
      font-size: 1rem;
      cursor: pointer;
      transition: background-color 0.3s;
    }

    button:hover {
      background-color: #e85a4f;
    }
  </style>
</head>
<body>

  <div class="card">
    <div class="message" id="message">
      Clique no botão para receber sua mensagem!
    </div>
    <button onclick="showMessage()">Nova Mensagem</button>
  </div>

  <script>
    const messages = [
      "Acredite no seu potencial!",
      "Hoje é um ótimo dia para começar algo novo.",
      "Você é mais forte do que pensa.",
      "Sorria! A vida retribui com coisas boas.",
      "Confie no processo. Tudo tem seu tempo.",
      "Faça o seu melhor hoje. O amanhã agradece.",
      "Você ilumina o mundo com sua presença!",
      "Cada passo importa. Continue caminhando."
    ];

    function showMessage() {
      const msgElement = document.getElementById("message");
      msgElement.style.opacity = 0;

      setTimeout(() => {
        const randomIndex = Math.floor(Math.random() * messages.length);
        msgElement.textContent = messages[randomIndex];
        msgElement.style.opacity = 1;
      }, 500);
    }
  </script>

</body>
</html>
