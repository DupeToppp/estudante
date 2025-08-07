<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  color: #333;
  background-color: #f4f4f9;
  margin: 0;
}

h1, h2, h3 {
  color: #2c3e50;
}

.header {
  background-color: #3498db;
  color: white;
  padding: 20px;
  text-align: center;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
}

.menu {
  float: left;
  width: 20%;
  text-align: center;
  background-color: #ecf0f1;
  padding: 10px;
  box-shadow: 2px 0 5px rgba(0,0,0,0.1);
}

.menu a {
  background-color: #bdc3c7;
  padding: 12px;
  margin-top: 10px;
  display: block;
  width: 100%;
  color: #2c3e50;
  text-decoration: none;
  border-radius: 5px;
  transition: background-color 0.3s;
}

.menu a:hover {
  background-color: #95a5a6;
}

.main {
  float: left;
  width: 60%;
  padding: 20px;
}

.right {
  background-color: #ecf0f1;
  float: left;
  width: 20%;
  padding: 15px;
  text-align: center;
  box-shadow: -2px 0 5px rgba(0,0,0,0.1);
}

.footer {
  background-color: #34495e;
  color: white;
  text-align: center;
  padding: 15px;
  margin-top: 20px;
  clear: both;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  background-color: #fff;
  border: 1px solid #ddd;
  margin-top: 8px;
  padding: 10px;
  border-radius: 5px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
}

.materia-info {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 100%;
}

.descricao {
  font-size: 0.9em;
  color: #7f8c8d;
  margin-top: 5px;
}

.nota {
  font-weight: bold;
  color: #27ae60;
  background-color: #e8f6f3;
  padding: 5px 10px;
  border-radius: 3px;
}

li a {
  color: #2c3e50; /* Cor do link da matéria */
  text-decoration: none;
}

@media only screen and (max-width: 620px) {
  .menu, .main, .right {
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  <h1>PÁGINA DO ESTUDANTE - Higor Vinicius de Mattos</h1>
</div>

<div style="overflow:auto">
  <div class="menu">
    <a href="#">Sobre Mim</a>
    <a href="#">Matérias</a>
    <a href="#">Notas</a>
    <a href="#">Horários</a>
  </div>

  <div class="main">
    <h2>Bem-vindo à minha página!</h2>
    <p>Olá! Meu nome é **Higor Vinicius de Mattos**. Sou estudante do ensino médio no período noturno e estou sempre em busca de aprender e me aprimorar. Esta página é um espaço para organizar meus estudos e compartilhar meu progresso.</p>
    
    <h3>Minhas Matérias (Ensino Médio)</h3>
    <ul>
      <li>
        <div class="materia-info">
          <span><a href="matematica.html">Matemática</a></span><span class="nota">9.5</span>
        </div>
        <p class="descricao">Ótimo desempenho em cálculos e raciocínio lógico.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="portugues.html">Português</a></span><span class="nota">9.2</span>
        </div>
        <p class="descricao">Sempre com ótimos resultados na escrita e interpretação.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="fisica.html">Física</a></span><span class="nota">10.0</span>
        </div>
        <p class="descricao">Excelente! Nota máxima e matéria favorita.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="quimica.html">Química</a></span><span class="nota">8.8</span>
        </div>
        <p class="descricao">Compreensão sólida dos conceitos, me dedicando mais.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="biologia.html">Biologia</a></span><span class="nota">9.0</span>
        </div>
        <p class="descricao">Facilidade em entender a vida e seus processos.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="historia.html">História</a></span><span class="nota">9.3</span>
        </div>
        <p class="descricao">Gosto de analisar os fatos e contextos do passado.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="geografia.html">Geografia</a></span><span class="nota">8.9</span>
        </div>
        <p class="descricao">Entendendo bem a dinâmica do mundo e da sociedade.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="comp-computacional.html">Pensamento Computacional</a></span><span class="nota">9.7</span>
        </div>
        <p class="descricao">Ótima lógica para resolver problemas complexos.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="ed-fisica.html">Educação Física</a></span><span class="nota">9.1</span>
        </div>
        <p class="descricao">Participativo e com bom desempenho nas atividades.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="ed-financeira.html">Educação Financeira</a></span><span class="nota">8.5</span>
        </div>
        <p class="descricao">Aprendendo a importância de gerenciar meu dinheiro.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="ingles.html">Inglês</a></span><span class="nota">9.8</span>
        </div>
        <p class="descricao">Dominando a língua para me comunicar cada vez melhor.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="filosofia.html">Filosofia</a></span><span class="nota">8.6</span>
        </div>
        <p class="descricao">Aberto a novas ideias e com boa argumentação.</p>
      </li>
      <li>
        <div class="materia-info">
          <span><a href="proj-vida.html">Projeto de Vida</a></span><span class="nota">9.4</span>
        </div>
        <p class="descricao">Planejando o futuro e definindo objetivos claros.</p>
      </li>
    </ul>

    <h3>Horário de Aulas (Período Noturno)</h3>
    <p>Meu horário de aulas é focado no período da noite, o que me permite dedicar o dia para outras atividades e estudos complementares.</p>
  </div>

  <div class="right">
    <h2>Destaques</h2>
    <p>Tenho obtido **boas notas** em diversas matérias, o que reflete meu esforço e dedicação. A matéria que mais me desafia (e me motiva) é a Física!</p>
  </div>
</div>

<div class="footer">
  &copy; 2023 - Higor Vinicius de Mattos | Todos os direitos reservados.
</div>

</body>
</html>
