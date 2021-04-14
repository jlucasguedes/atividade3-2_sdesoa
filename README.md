20211035304A-Sistemas Distribuídos e SOA-4-Noturno

<h3>Chamadas Assíncronas em JavaScript</h3>

<p>1. Qual problema percebeu ao realizar tais alterações;</p>
 <p><b>Resposta:</b> A div com o conteúdo <b>&lt;h2>Dados obtidos do servidor!&lt;/h2></b> é exibida antes dos dados serem obtidos.</p>
 
<p>2. Explique porque o problema ocorreu e o qual a relação com chamadas assíncronas;</p>
<p><b>Resposta:</b> A função <b>request();</b> de obtenção dos dados é assíncrona ou seja ela não bloqueia o restante da execução do script que chama a função que insere o conteúdo na div antes do término da função request().</p>
  
<p>3. Altere o código para resolver o problema.</p>
<p><b>Resposta:</b> Foi feita alteração e comitada no github, a função de inserção de conteudo na nova div foi inserida dentro da função request() no final da mesma.</p>
