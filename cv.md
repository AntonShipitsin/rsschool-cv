# Anton Shipitsin

## Contact information:
* **Location:** Kazakhstan, Almaty 
*  **Tel:** +77012233515
*  **Mail:** antonshipitsin@gmail.com
*  **GitHub:** [AntonShipitsin](https://github.com/AntonShipitsin) 

## About me:
Hi. My name is Anton. I am from Almaty - most beautiful city in Kazakhstan.I like travel, listen and play music
and recently i like to  programming and to  understand  how is tech staff  works. I am responsible and diligent and ready to learn
something new to be a good developer in near future.

## Skill:
- HTML (basic level)
- SCC (basic level)
- JavaScript (basic level)
- Figma 
 
 
```
<body>
    <div class="wrapper">
        <div class="inputs">
            <form>
                <a>Размер платформы (mm):</a>
                <input id="plate" type="number" value="180" placeholder="0">
            </form>
            <form>
                <a>Ширина пачки (mm):</a>
                <input id="box" type="number" placeholder="0">
            </form>
            <form>
                <a>Скорость (m/min):</a>
                <input id="speed" type="number" value="25" placeholder="0">
            </form>
            <button class="calculate" onclick="addition();">Calculate</button>
            <div class="result">RING BUFFER:</div>
            <div class="value" id="calc"></div>
        </div>
    <script>
        function addition() {
    let a = parseFloat(document.getElementById('plate').value);
    let b = parseFloat(document.getElementById('box').value);
    let c = parseFloat(document.getElementById('speed').value);
    let result = ((a - b) / 2) * 60 / c;
    document.getElementById('calc').innerHTML = result
}
 </script>
</body>
```