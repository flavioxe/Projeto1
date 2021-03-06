<h1>Desafio de HTML, CSS e JS da NewTab Academy.</h1>

# Sobre o projeto
Seu objetivo é criar uma SPA (Single Page Application) seguindo o layout que está nesta url: https://goo.gl/yMrCaf.

No layout original vocês vão ver que existem itens no menu sem utilidade. Vamos alterar e criar funcionalidades pra eles? 🙂

# Durante o desenvolvimento portanto, vocês devem:

<ul>
  <li>Alterar o link “Resumo” para “Cadastro de transações”.</li>
  <li>Alterar o link “Dashboard” para “Limpar dados”.</li>
  <li>Alterar o link “Configurações” para “Salvar no servidor”.</li>
</ul>
  
<h2> O que sua aplicação deverá fazer </h2>
<ul>
  <li>Incluir transações de compra ou venda de mercadoria.</li>
  <li>Criar um extrato das transações incluídas. As transações deverão ser mostradas na ordem em que foram incluídas.</li>
  <li>Mostrar o saldo final e destacar se houve lucro ou prejuízo.</li>
  <li>A aplicação deverá ser responsiva e estar de acordo com o layout fornecido.</li>
  <li>Persistir as transações no Local Storage.</li>
  <li>Ter a opção de salvar os dados em um servidor.</li>
</ul>

<h2> Outros requisitos </h2>

<h2> HTML: </h2>

<ul>
  <li> As opções do campo “Tipo de transação” são: Compra e Venda. </li>
  <li> Caso não exista nenhuma transação cadastrada, adicione a mensagem “Nenhuma transação cadastrada.” na lista do Extrato. </li>
</ul>

<h2> CSS: </h2>

<ul>
<li> Testar em smartphones, tablets (modos portrait e landscape) e monitores a partir de 1024px até 1900px. (Através do inspecionar elemento no navegador)</li>
<li> A fonte utilizada é a Lato.</li>
<li> A largura máxima do conteúdo é 1100px.</li>
</ul>
  
<h2> Javascript: </h2>

<ul>
<li>Validar o formulário para que todos os campos sejam preenchidos.</li>
<li>Adicionar uma máscara no campo “Valor” para que apenas números sejam preenchidos e com a formatação correta. (Padrão: 10,90)</li>
<li>Ao adicionar uma nova transação, persistir no Local Storage e já atualizar a lista com o extrato. Atualizar também o cálculo apresentado.</li>
<li>Ao clicar no link “Limpar dados”, apresentar uma mensagem de confirmação e em seguida apagar as informações, atualizando a lista.</li>
<li>Ao clicar no link “Salvar no servidor”, você deve realizar uma chamada para a API do Airtable:</li>
<li>Documentação: https://airtable.com/appRNtYLglpPhv2QD/api/docs#curl/table:historico:list</li>
<li>Valores:</li>
  <ul>
    <li>Aluno: os 4 últimos números do seu CPF.</li>
    <li>Json: Json com todas as transações armazenadas no Local Storage.</li>
  </ul>
<li>Métodos: primeiramente listar os registros para buscar o “id” referente ao seu registro. Em seguida, realizar o update do valor do “Json”.</li>
</ul>
