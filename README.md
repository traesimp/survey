<!DOCTYPE html>
<html lang="tl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Survey para kay Crush</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffe6f2;
            padding: 20px;
        }
        form {
            background: white;
            padding: 20px;
            max-width: 400px;
            margin: auto;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        input, textarea, select {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background-color: #ff66b2;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #ff3385;
        }
    </style>
</head>
<body>
    <h2>Survey para kay Crush 💖</h2>
    <form action="traelam22@gmail.com" method="POST">
        <label>Pangalan mo:</label>
        <input type="text" name="name" required>
        
        <label>Favorite Color mo:</label>
        <input type="text" name="color" required>
        
        <label>Hobbies mo:</label>
        <input type="text" name="hobbies" required>
        
        <label>May gusto ka bang sabihin? 😘</label>
        <textarea name="message" rows="4" required></textarea>
        
        <label>Do you like me too? 😳</label>
        <select name="confession" required>
            <option value="yes">Yes, I like you too! 💖</option>
            <option value="maybe">Maybe... 😳</option>
            <option value="no">Sorry, just friends! 😅</option>
        </select>
        
        <button type="submit">Ipadala 💌</button>
    </form>
    <p>Thx for answering the question! 💕</p>
</body>
</html>
