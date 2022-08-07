# vedanti.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Glassmorphism Calculator UI</title>
    <link rel="stylesheet" href="Glassmorphism Calculator.css">
</head>
<body>
    <div class="container">
        <form action="" name="calc" class="calculator">
            <input type="text" readonly class="value" name="txt">
            <span class="num clear" onclick="calc.txt.value = ''">c</span>
            <span class="num" onclick="document.calc.txt.value +='/'">/</span>
            <span class="num" onclick="document.calc.txt.value +='*'">*</span>
            <span class="num" onclick="document.calc.txt.value +='7'">7</span>
            <span class="num" onclick="document.calc.txt.value +='8'">8</span>
            <span class="num" onclick="document.calc.txt.value +='9'">9</span>
            <span class="num" onclick="document.calc.txt.value +='-'">-</span>
            <span class="num" onclick="document.calc.txt.value +='4'">4</span>
            <span class="num" onclick="document.calc.txt.value +='5'">5</span>
            <span class="num" onclick="document.calc.txt.value +='6'">6</span>
            <span class="num plus" onclick="document.calc.txt.value +='+'">+</span>
            <span class="num" onclick="document.calc.txt.value +='1'">1</span>
            <span class="num" onclick="document.calc.txt.value +='2'">2</span>
            <span class="num" onclick="document.calc.txt.value +='3'">3</span>
            <span class="num" onclick="document.calc.txt.value +='0'">0</span>
            <span class="num" onclick="document.calc.txt.value +='00'">00</span>
            <span class="num" onclick="document.calc.txt.value +='.'">.</span>
            <span class="num" onclick="document.calc.txt.value =eval(calc.txt.value)">=</span>

        </form>
    </div>
</body>
<script type="text/javascript" src="Glassmorphism Calculator.js"></script>
<script type="text/javascript">
    VanillaTilt.init(document.querySelector(".container"), {
        max: 25,
        speed: 400,
        glare: true,
        "max-glare": 0.5
    });
    VanillaTilt.init(document.querySelectorAll(".yout"));
</script>
</html>
