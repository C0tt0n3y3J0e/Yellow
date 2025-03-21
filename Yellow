<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALL MY LOVE 💛</title>
    <style>
        body {
            text-align: center;
            background-color: #fff8dc;
            font-family: 'Arial', sans-serif;
        }
        h1 {
            color: #ffcc00;
        }
        #bouquet {
            display: none;
            margin-top: 20px;
            position: relative;
            width: 300px;
            height: 300px;
            margin: auto;
        }
        .flower-tile {
            width: 60px;
            height: 60px;
            background-size: cover;
            background-position: center;
            display: inline-block;
            margin: 2px;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            background-color: #ffcc00;
            border: none;
            cursor: pointer;
            border-radius: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>For My Beautiful Love; Because you light up my world; today I give you these yellow flowers that imitate your brightness ✨🌞</h1>
    <p>Click the button to receive your yellow flower collage! 🌼</p>
    <button onclick="showFlowers()">Click Here</button>
    <div id="bouquet"></div>
    <script>
        function showFlowers() {
            const bouquet = document.getElementById('bouquet');
            bouquet.innerHTML = '';
            bouquet.style.display = 'block';
            
            const flowerImages = [
                'https://elcomercio.pe/resizer/v2/AOQDT56U2BCMHOTGKDCVX4SOUE.jpg?auth=ebea9d96aa07e27c32d1849ed1aedde87830d93043f8ed52b3fca29addd7e376&width=980&height=528&quality=75&smart=true',
                'https://www.nmas.com.mx/_next/image/?url=https%3A%2F%2Fstatic-live.nmas.com.mx%2Fnmas-news%2Fstyles%2Fcorte_16_9%2Fcloud-storage%2F2025-03%2Fflores-amarillas-regalo-21-marzo-opciones.jpg%3Fh%3D920929c4%26itok%3DGEHqbzdI&w=1920&q=80',
                'https://img.emisorasunidas.com/upload/2022/09/17161D564C434D6D17150F54584946781F121F18564645741012-1200x800.webp',
                'https://elcomercio.pe/resizer/v2/ALZKARMRNNAQ7OXP5KORG2RLZY.jpg?auth=3848ef2d214adbdb600d80db96b1610a109d2f3f75640a2e474cca737202f3b9&width=980&height=528&quality=75&smart=true',
                'https://media.admagazine.com/photos/658b40cdc6ed181cc9ffdc33/1:1/w_2250,h_2250,c_limit/flores-amarillas-en-ano-nuevo.jpg'
            ];
            
            for (let i = 0; i < 25; i++) {
                let tile = document.createElement('div');
                tile.classList.add('flower-tile');
                tile.style.backgroundImage = `url(${flowerImages[Math.floor(Math.random() * flowerImages.length)]})`;
                bouquet.appendChild(tile);
            }
        }
    </script>
</body>
</html>
