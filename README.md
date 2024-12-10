# index.html <!DOCTYPE html>
<html lang="et">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Auto Hinnad</title>
    <style>
        /* Põhistiilid */
        body {
            background-color: #1BA098; /* Roheline taust */
            color: #DEB992; /* Beež tekst */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            background-color: #147C6A;
            padding: 20px;
            color: white;
        }
        table {
            width: 80%;
            margin: 30px auto;
            border-collapse: collapse;
            background-color: white;
            color: black;
            text-align: left;
        }
        th, td {
            padding: 15px;
            border: 1px solid #ddd;
        }
        th {
            background-color: #1BA098;
            color: white;
        }
        tr:hover {
            background-color: #f1f1f1;
        }
        footer {
            text-align: center;
            padding: 10px;
            background-color: #147C6A;
            color: white;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Pealkirja osa -->
    <header>
        <h1>Auto Hinnad</h1>
        <p>Ülevaade erinevate autode mudelite hindadest</p>
    </header>

    <!-- Tabel -->
    <table>
        <thead>
            <tr>
                <th>Mudel</th>
                <th>Tootja</th>
                <th>Aasta</th>
                <th>Hind (€)</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Model 3</td>
                <td>Tesla</td>
                <td>2024</td>
                <td>45,000</td>
            </tr>
            <tr>
                <td>XC60</td>
                <td>Volvo</td>
                <td>2023</td>
                <td>48,000</td>
            </tr>
            <tr>
                <td>Golf</td>
                <td>Volkswagen</td>
                <td>2022</td>
                <td>25,000</td>
            </tr>
            <tr>
                <td>Civic</td>
                <td>Honda</td>
                <td>2024</td>
                <td>28,500</td>
            </tr>
            <tr>
                <td>A6</td>
                <td>Audi</td>
                <td>2023</td>
                <td>55,000</td>
            </tr>
        </tbody>
    </table>

    <!-- Jalus -->
    <footer>
        <p>&copy; 2024 Auto Hinnad | Kõik õigused kaitstud</p>
    </footer>
</body>
</html>
