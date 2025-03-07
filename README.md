<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tabela de Estudante</title>
    <style>
        /* Estilo geral da página */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f9;
            margin: 0;
            padding: 0;
        }
        h2 {
            text-align: center;
            color: #333;
            padding: 20px;
            background-color: #4CAF50;
            color: white;
            margin-bottom: 40px;
            font-size: 24px;
        }

        /* Estilo da tabela */
        table {
            width: 60%;
            margin: 0 auto;
            border-collapse: collapse;
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        th, td {
            padding: 12px 20px;
            text-align: left;
            font-size: 16px;
        }
        th {
            background-color: #4CAF50;
            color: white;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        td {
            border-bottom: 1px solid #ddd;
        }
        td:first-child {
            font-weight: bold;
        }
        /* Efeito de hover nas linhas */
        tr:hover {
            background-color: #f1f1f1;
        }
        /* Estilo de botões, se desejar adicionar algum botão futuramente */
        .btn {
            display: inline-block;
            padding: 10px 15px;
            background-color: #4CAF50;
            color: white;
            border-radius: 4px;
            text-decoration: none;
            font-size: 16px;
            transition: background-color 0.3s;
        }
        .btn:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<h2>Tabela de Estudante</h2>

<table>
    <tr>
        <th>Nome</th>
        <td>Maria Cabita</td>
    </tr>
    <tr>
        <th>Número</th>
        <td>16</td>
    </tr>
    <tr>
        <th>Sala</th>
        <td>Turma BNI</td>
    </tr>
    <tr>
        <th>Curso</th>
        <td>Informática de Gestão</td>
    </tr>
</table>

</body>
</html>
