# POCKnockoutJSPROD
POC KnockoutJS

# Descrição da Tecnologia

KnockoutJs é uma biblioteca escrita em JavaScript e contribui na criação de interfaces ricas e responsivas com modelo de dados limpo. A qualquer momento é possível ter seções da interface com o usuário que atualizam dinamicamente dependendo das ações do usuário ou quando sources externos sofrem alterações. O KnockoutJs veio para ajudar na implementação mais simples e melhorar a manutenibilidade do frontend.

### Principais características:
 - Elegant dependency tracking - automaticamente atualiza as partes necessárias da interface no momento em que o modelo de dados sofre alteração.
 - Bindings declarativos - um jeito simples e claro de conectar as partes da interface com o modelo de dados. Você constrói uma interface dinâmica e complexa utilizando bindings entre contextos.
 - Extensível - implementação de comportamentos customizados como novos bindings declarativos para um jeito fácil de reuso em poucas linhas de código


### Benefícios adicionais:

 - Biblioteca JavaScript Pura - funciona com qualquer tecnologia server or client-side
 - Pode ser adicionado junto a aplicações já existentes sem qualquer maiores mudanças arquiteturais
 - Compacto - em torno de 13kb com gzip
 - Trabalha com os principais browser (IE 6+, Firefox 2+, Chrome, Safari, Edge, outros)

### Como o Knockout é diferente?

As operações são mais fácis com o Knockout (KO). Ele deixa você escalar a complexidade sem medo algum de introduzir inconsistências. Apenas represente os itens como arrays JavaScript, e utilize foreach para os bindings, os transformando em tabelas ou um grupo de divs. Quando o array sofre mudanças, a interface muda para equalizar, o desenvolvedor não precisa descobrir quando injetar novas linhas ou onde. Por exemplo, é possível declarar um bind de um SPAN para exibir o número de itens:

```sh
There are <span data-bind="text:myItems().length"></span> items
```
Apenas isso! Não há a necessidade de escrever código que atualize isso, ele atualiza sozinho quando o array myItems muda. Similar, para adicionar um botão, por exemplo, que habilite ou desabilite dependendo do número de linhas, basta escrever o seguinte:


```sh
<button data-bind="enable: myItems().length < 5">Add</button>
```

### Tecnologías Relacionadas


* AngularJs
* EmberJS
* BackboneJS

Todas as tecnologias citadas acima, tem o mesmo cunho que o KnockoutJS, elas possuem especificidades maiores, são bem mais complexas. KnockoutJs veio para implementar o pattern MVVM, facilitando os modelos de dados que transitam na interface do usuário, veio com o propósito de resolver problemas decorrentes de modelos de dados e não trazer consigo um canhão de funcionalidades.

### Referências para o aprendizado

http://www.asp.net/single-page-application/overview/introduction/knockoutjs-template
http://blog.stevensanderson.com/2014/06/11/architecting-large-single-page-applications-with-knockout-js/
http://knockoutjs.com/documentation/observables.html#mvvm_and_view_models
