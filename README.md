# React_aula10

<h2>MeuComponent.js</h2>
<h3>Quais os imports utilizados?</h3>
<p>React: Possuí todos os componentes básicos do react.</p>
<p>UseState: Gerencia os estado dos dados, ele contém o valor atual, podendo ser alterado com o tempo, ele faz isso através de um componente que retorna um array contendo o valor atual e uma função para atualizar o valor .</p>
<h3>Há componentes? o que fazem?</h3>
<p>Existe o componente menu, esse componente irá exibir os pratos.</p>
<h3>Para que serve o onDishSelect no projeto?</h3>
<p>Nessa função, quando o usuário clicar no prato(dish) em questão e atualiza o estado do componente "selectedDish"</p>
<h3>Para que serve o renderDish?</h3>
<p>Recebendo o prato(dish) como argumento,essa função, caso o valor de prato
não seja nulo, irá retornar um componente "card" contendo a imagem juntamente com as demias informações desse prato</p>
<h3>Para que serve o props.dishes.map?</h3>
<p>Essa função itera sobre cada prato no array e retornará um novo componente para cada prato. Ao clicar na imagem para um "div" abaixo dos demais card, um card contendo a imagem e as demais informações dos pratos</p>
<h3>Quais as propriedades?</h3>