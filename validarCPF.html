<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Validador de CPF</title>
  
</head>
<body>

  <h1> Validar de CPF</h1>
  <input type="text" id="cpf" placeholder="Digite o CPF (somente números)" maxlength="11">
  <button onclick="validarCPF()">Validar</button>
  <div id="resultado"></div>

  <script>
    function validarCPF() {
      const cpf = document.getElementById('cpf').value;

      if (!/^\d{11}$/.test(cpf)) {
        document.getElementById('resultado').textContent = "❌ CPF deve conter 11 números.";
        return;
      }

      if (/^(\d)\1+$/.test(cpf)) {
        document.getElementById('resultado').textContent = "❌ CPF inválido (números repetidos).";
        return;
      }

      let soma = 0;
      for (let i = 0; i < 9; i++) {
        soma += parseInt(cpf.charAt(i)) * (10 - i);
      }

      let digito1 = 11 - (soma % 11);
      if (digito1 > 9) digito1 = 0;

      if (parseInt(cpf.charAt(9)) !== digito1) {
        document.getElementById('resultado').textContent = "❌ CPF inválido.";
        return;
      }

      soma = 0;
      for (let i = 0; i < 10; i++) {
        soma += parseInt(cpf.charAt(i)) * (11 - i);
      }

      let digito2 = 11 - (soma % 11);
      if (digito2 > 9) digito2 = 0;

      if (parseInt(cpf.charAt(10)) !== digito2) {
        document.getElementById('resultado').textContent = "❌ CPF inválido.";
        return;
      }

      document.getElementById('resultado').textContent = "✅ CPF válido!";
    }
  </script>

</body>
</html>
