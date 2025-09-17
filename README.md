# Exerc-cios-de-Switch-TPA
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="utf-8">
</head>
<body>
  <h1>Explicação dos exercícios do repositório "Exercícios de Switch - TPA"</h1>

  <p>Resumo: cada programa ilustra o uso da estrutura <code>switch</code> em Java. Abaixo está a descrição de cada arquivo e a função de seus trechos principais.</p>

  <h2>1. Bilhete</h2>
  <p><strong>Entrada:</strong> inteiro representando o tipo de bilhete (ex.: 1, 2, 3).<br>
  <strong>Função:</strong> lê a opção com <code>Scanner</code>, usa <code>switch(opcao)</code> para determinar qual mensagem ou preço imprimir. Cada <code>case</code> trata um tipo de bilhete; o <code>default</code> lida com opções inválidas.</p>

  <h2>2. ClassificadorFaixaEtaria</h2>
  <p><strong>Entrada:</strong> idade (inteiro).<br>
  <strong>Função:</strong> valida a idade (não negativa), define a categoria (criança, adolescente, adulto, idoso) — possivelmente por intervalos — e usa <code>switch</code> sobre essa categoria para imprimir a classificação. O programa pode usar condicionais antes do <code>switch</code> para mapear a idade à categoria.</p>

  <h2>3. Frutas</h2>
  <p><strong>Entrada:</strong> nome da fruta (string).<br>
  <strong>Função:</strong> aplica <code>fruta.toLowerCase()</code> e faz <code>switch</code> sobre a string para mostrar preço, descrição ou disponibilidade para cada fruta conhecida. Há um <code>default</code> para fruta não cadastrada.</p>

  <h2>4. JogosSwitch</h2>
  <p><strong>Entrada:</strong> número do menu que representa um jogo.<br>
  <strong>Função:</strong> exibe um menu (1, 2, ...), usa <code>switch</code> para imprimir o nome/descrição do jogo escolhido ou chamar a função que o inicia. Geralmente há um loop para permitir repetir escolhas e uma opção para sair.</p>

  <h2>5. SimuladorBanco</h2>
  <p><strong>Entrada/Estado:</strong> saldo (double) e opções de menu.<br>
  <strong>Função:</strong> dentro de um laço (<code>do/while</code> ou <code>while</code>) exibe opções: depositar, sacar, ver saldo, sair. O <code>switch</code> trata cada ação:
    <ul>
      <li><strong>case 1:</strong> ler valor e somar ao saldo (depósito).</li>
      <li><strong>case 2:</strong> ler valor, verificar saldo e subtrair (saque) ou informar saldo insuficiente.</li>
      <li><strong>case 3:</strong> imprimir saldo atual.</li>
      <li><strong>default:</strong> opção inválida.</li>
    </ul>
  Ao escolher sair, o laço termina e o programa encerra.</p>

  <h2>6. SwitchSemana</h2>
  <p><strong>Entrada:</strong> número de 1 a 7.<br>
  <strong>Função:</strong> <code>switch(numero)</code> mapeia para os dias da semana: 1→Domingo, 2→Segunda, ... 7→Sábado. <code>default</code> para valores fora do intervalo.</p>

  <h2>Padrões comuns</h2>
  <ul>
    <li>Uso de <code>Scanner</code> para ler dados do usuário.</li>
    <li>Menus simples com opções númericas ou strings.</li>
    <li><code>switch</code> para direcionar o fluxo conforme a entrada.</li>
    <li><code>default</code> para validar entradas inválidas.</li>
    <li>Em programas interativos, uso de laços para repetir operações até o usuário sair.</li>
  </ul>
</body>
</html>
