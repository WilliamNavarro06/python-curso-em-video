<h1> 🐍 Desafios Python Curso em Vídeo - Guanabara 🚀  </h1>
<hr>
<p>Resoluções dos exercícios do curso de Python do Curso em Vídeo, organizado por aula. Um guia para outros estudantes e para minha jornada de aprendizado! ✨</p>
<title>Resumo sobre If e Else em Python para GitHub README</title>
</head>
<body>
    <h2>Condições em Python: `if` e `else`</h2>
    <p>Em Python, as estruturas condicionais <code>if</code> e <code>else</code> são fundamentais para a tomada de decisões dentro do seu código. Elas permitem que diferentes blocos de código sejam executados dependendo se uma condição é verdadeira ou falsa.</p>

    <h3><code>if</code> (Se)</h3>
    <p>A instrução <code>if</code> avalia uma condição. Se essa condição for <code>True</code>, o bloco de código indentado abaixo do <code>if</code> é executado.</p>
    <pre><code>
idade = 20
if idade >= 18:
    print("Você é maior de idade.")
    </code></pre>

    <h3><code>else</code> (Senão)</h3>
    <p>Opcionalmente, você pode usar a instrução <code>else</code> após um bloco <code>if</code>. O código dentro do bloco <code>else</code> será executado somente se a condição do <code>if</code> for <code>False</code>.</p>
    <pre><code>
nota = 6
if nota >= 7:
    print("Aprovado!")
else:
    print("Reprovado.")
    </code></pre>

    <h3><code>elif</code> (Senão Se)</h3>
    <p>Para verificar múltiplas condições em sequência, utilize o <code>elif</code> (abreviação de "else if"). Ele é avaliado somente se a condição do <code>if</code> anterior (ou outro <code>elif</code>) for falsa.</p>
    <pre><code>
temperatura = 25
if temperatura > 30:
    print("Está muito quente!")
elif temperatura > 20:
    print("A temperatura está agradável.")
else:
    print("Está um pouco frio.")
    </code></pre>

    <p>Em resumo, <code>if</code>, <code>else</code> e <code>elif</code> fornecem a lógica essencial para controlar o fluxo de execução do seu programa Python, permitindo que ele se comporte de maneira diferente em diversas situações.</p>
</body>
</html>
