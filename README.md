# my-project https://vercel.com/jonatas2021/alura-my-project
## Iniciar um projeto novo, utilizando TypeScript e Vue3;
aprendi como instalar e utilizar o vue cli para construir um novo projeto, customizando inclusive as dependências que teremos.

## Importar o Bulma;
Fazendo uma única importação, no index.html, passei a ter disponível todos as facilidades desse framework CSS.

## Criar componentes; 
para cada novo componente criei um arquivo Vue com as seguintes sessões: template, para o html. script, para o comportamento e style para o visual.
Escutar eventos de clique;

## O Vue
nos ajuda a trabalhar com eventos, basta utilizarmos a sintaxe @NOMEDOEVENTO direto no elemento que queremos ouvir.
Trabalhar com intervalos.

## O setInterval
é perfeito para nosso cenário, de incrementar o tempo decorrido a cada segundo.

## Refatorar componentes em componentes menores;
é muito fácil atribuir funcionalidades demais a um componente existente. Quando isso aconteceu, aprendi a refatorar o componente em componentes menores e mais coesos.

## Formatar a exibição de X segundos em HH:mm:ss;
podemos construir um objeto Date passando em seu construtor a quantidade de microsegundos decorridos. Depois, fatiamos a string para pegarmos somente as horas, minutos e segundos.

## Emitir eventos customizados;
utilizei o $emit para criar eventos utilizados na comunicação entre componentes.
Ouvir eventos customizados é tão simples quanto ouvir eventos HTML, como o click por exemplo.

## Renderizar listas com o v-for;
utilizei um mecanismo de repetição para renderizar N vezes uma tarefa, onde N é o tamanho da lista. Isso faz com que nossa lista seja dinâmica.
Condicionais com v-if / v-else;

## Como esconder ou exibir um componente;
dado um estado específico utilizando a diretiva v-if.Fallback de conteúdo com o operador || (OU);
Utilizei o operador OU para exibir um texto padrão, caso a tarefa não possua uma descrição. 

## Slots;
Aprendi a lidar com o slot quando criamos um componente para representar o Box. Assim, conseguimos exibir os elementos filhos dentro do nosso Box.

## Uso de variáveis CSS para temas (claro/escuro);
utilizando essas variáveis, nós podemos facilmente controlar o tema do nosso Alura Tracker, alterando a cor de fundo e a cor do texto de acordo com o tema aplicado.

## Adicionar e remover classes baseado num estado do componente;
 condicionalmente utilizando a diretiva :class.

## Estilos via objetos.
uma nova forma de aplicar estilos a um elemento, utilizando um objeto que representa as propriedades e seus valores.

## Depurar a aplicação usando o Vue Devtools;
visualizar o estado de cada componente, o que nos ajuda a entender como as coisas estão funcionando por baixo dos panos.

## Gerar um build manual da aplicação;
rodar o script que faz a construção da nossa aplicação, assim podemos publicar manualmente em algum servidor web caso seja necessário.

## Publicar a aplicação no Vercel;
Aprendi a configurar o Vercel para integrar com o nosso github e publicar nossa aplicação de forma contínua!


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
