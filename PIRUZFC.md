# piruzfc
PIRUZFC
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PIRUZ - Time de Amigos</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(to bottom, yellow, black);
            color: white;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: black;
        }
        header h1 {
            color: yellow;
            margin: 0;
        }
        nav {
            display: flex;
            gap: 20px;
        }
        nav a {
            color: yellow;
            text-decoration: none;
            font-weight: bold;
        }
        .dropdown {
            position: relative;
        }
        .dropdown-content {
            display: none;
            position: absolute;
            top: 25px;
            left: 0;
            background-color: black;
            border: 1px solid yellow;
            padding: 10px;
            list-style: none;
            text-align: left;
        }
        .dropdown:hover .dropdown-content {
            display: block;
        }
        .dropdown-content li {
            color: yellow;
        }
        .dropdown-content li.cross:before {
            content: "✝ ";
            color: red;
        }
        #main-content {
            padding: 20px;
            text-align: center;
        }
        .game-schedule {
            background-color: yellow;
            color: black;
            padding: 20px;
            border-radius: 10px;
            margin: 20px auto;
            width: 60%;
            box-shadow: 0 0 10px black;
        }
        .history {
            background-color: black;
            color: yellow;
            padding: 20px;
            margin-top: 20px;
            border-radius: 10px;
        }
        img {
            width: 80px;
            height: 80px;
        }
    </style>
</head>
<body>
    <header>
        <h1>PIRUZ</h1>
        <nav>
            <div class="dropdown">
                <a href="#">ATLETAS</a>
                <ul class="dropdown-content">
                    <li>Gabriel</li>
                    <li>Lucas</li>
                    <li>Kaio Henrique</li>
                    <li>Dudu</li>
                    <li>Rafael</li>
                    <li>Vine</li>
                    <li>Junior</li>
                    <li>Melki</li>
                    <li>Afonso</li>
                    <li class="cross">Nick</li>
                    <li class="cross">Gregg</li>
                </ul>
            </div>
            <a href="#">Desde 2010</a>
            <a href="#">Time de Amigos de Infância</a>
        </nav>
        <img src="https://via.placeholder.com/80?text=Peru" alt="Peru Raivoso">
    </header>
    <div id="main-content">
        <div class="game-schedule">
            <h2>Agenda de Jogos</h2>
            <table border="1" style="width: 100%; text-align: center; border-collapse: collapse;">
                <tr>
                    <th>Data</th>
                    <th>Adversário</th>
                    <th>Placar</th>
                </tr>
                <tr>
                    <td>10/12/2024</td>
                    <td>Time X</td>
                    <td>3 - 2</td>
                </tr>
                <tr>
                    <td>15/12/2024</td>
                    <td>Time Y</td>
                    <td>2 - 2</td>
                </tr>
            </table>
        </div>
        <div class="history">
            <h2>História do Time</h2>
            <p>O PIRUZ foi fundado em 2010 por um grupo de amigos de infância apaixonados por futebol. Desde então, o time tem promovido união, diversão e competições emocionantes.</p>
        </div>
    </div>
</body>
</html>
