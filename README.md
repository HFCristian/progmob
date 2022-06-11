# progmob

@anakarinafacom

Cristian Haas Fretes
201719060525
Gustavo Redua de Oliveira
202119050535

<h2>Visão Geral </h2>
O aplicativo será destido a cantinas e estudantes da ufms. Estudantes que utilizam as cantinas da ufms, poderão conferir o cardapio em tempo real e quando novos salgados ficarem prontos.

<h2>Papéis </h2>
-Cantinas: Cadastraram o cardápio e atualizam conforme novos
-Estudantes: Utilizam utilizam o app para verificar o cardapio e comprar itens

<h2>Requisitos Funcionais </h2>
<h4>Cadastro de usuários: "O cadastro de usuários permite aos usuários utilizarem o sistema"</h4>
-Aluno</br>
 ->Nome</br>
 ->RGA</br>
 ->Senha</br>
Saida: Sistema Verifica se todos os dados foram preenchidos </br>
               realiza o cadastro, caso contrário emite uma mensagem de erro</br>
</br>
-Cantina</br>
 ->Nome</br>
 ->Localidade</br>
Saida: Sistema Verifica se todos os dados foram preenchidos</br>
               realiza o cadastro, caso contrário emite uma mensagem de erro</br>
</br>
<h3>Cadastro de Cardapio: "O cadastro de cardápio proporciona aos usuários saberem o que vende na cantina, qual seu valor, e se ainda possui"</h3>
 ->Nome</br>
 ->Quantidade</br>
 ->Valor</br>
Saida: Sistema Verifica se todos os dados foram preenchidos </br>
               Verifica se a quantidade é maior que 0</br>
               realiza o cadastro, caso contrário emite uma mensagem de erro</br>

<h3>Adicionar saldo: "O aplicativo deve permitir adicionar saldo na carteira do aplicativo, o saldo é comprado presencialmente, obtendo uma hash"</h3>
  ->Hash</br>
Saida: Sistema Verifica se todos os dados foram preenchidos </br>
               Verfica se a hash é válida</br>
               adiciona o saldo a carteira, caso contrario emite uma mensagem de erro</br>
  
<h3>Realizar compra: "O aplicativo deve permitir ao usuário aluno realziar a compra de qualquer item da cantina"</h3>
  ->Produto</br>
  ->Quantidade</br>
Saida: Sistema Verifica se todos os dados foram preenchidos </br>
               Verfica se a quantidade do produto é maior que 0</br>
               efetua a compra e debita o valor da compra do saldo da carteira, caso contrario emite uma mensagem de erro</br>
  

  

