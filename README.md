# test
<!DOCTYPE html>
<html>
<body>

<h1>LYZ抽奖</h1>

<p>点击按键获取lyz的兄弟数</p>

<button onclick="LHZNB()">LHZ死几个兄弟</button>

<script>
function LHZNB() {
  document.getElementById("demo").innerHTML =Math.floor(Math.random() * 30);
}
</script>

<p id="demo"></p>

</body>
</html>
