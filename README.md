<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>Script Hub Demo</title>
<style>
body {
    background: #0b0b0b;
    font-family: Arial;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}
#box {
    background: #151515;
    padding: 20px;
    width: 320px;
    border-radius: 10px;
}
button {
    width: 100%;
    margin-top: 8px;
    padding: 10px;
    border: none;
    border-radius: 6px;
    background: #2b6cff;
    color: white;
    cursor: pointer;
}
button:hover {
    background: #4a86ff;
}
pre {
    background: #000;
    padding: 10px;
    height: 120px;
    overflow: auto;
}
</style>
</head>

<body>
<div id="box">
    <h3>Script Hub (Demo)</h3>

    <button onclick="loadScript(1)">Script 1</button>
    <button onclick="loadScript(2)">Script 2</button>
    <button onclick="loadScript(3)">Script 3</button>

    <pre id="log">Aguardando...</pre>
</div>

<script>
function loadScript(id){
    document.getElementById("log").textContent =
        "Script " + id + " carregado (demo).";
}
</script>
</body>
</html>

DOWLOAD:http://www.youtube.com/@Wilgamer244
