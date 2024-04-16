# Ata_pythonHelloInput.html
<!DOCTYPE html>
<html lang="en">
<head>
<link rel="stylesheet" herf="https://pyscript.net/latest/pyscript.css" />
<script defer src="https://pyscript.net/latest/pyscript.js"></script>
<style>
lable{
display:block;
}
</style>
</head>
<body>
<form>
<label for="operandOne">x:</label><input name="operandOne" id="operandOne" vslue="10">

<label for="total">Result:</label><div name="total"></div>
</form>
<py-script>
input_box = Element("operandOne")
operandOne = float(input_box.value)
result = Element("total")
result.write("Hello! The input says:" + str(operandOne))

</py-script>
</body>
</html>
