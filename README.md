caderno digital com informações adicionais do html 😂

## Extensões vs code
- html preview

## Comentários,tags e atributos
~~~HTML
<!--comentatios-->
<h2>Tag de titulo</h2>
<img src='' alt='atributo de infor'> 
~~~
- Normal Elements. Esses elementos são abertos com uma tag e fechados com
outra tag.
- Void Elements. Esses elementos não possuem
conteúdo. Na sintaxe HTML, esses elementos são abertos e fechados com apenas uma
tag com ou sem o caractere “/”. Um exemplo de Void Element é o elemento br

# Informações extras
- o atributo booleano disabled desativa alguma ação da tag
~~~html
<input type='text' disabled>
~~~
- o atributo global contenteditable permite editar o conteúdo mas não é salva
~~~html
<h2 contenteditable='true'>edite</h2>
~~~
- o atributo tabindex faz o usuário navegar pelos itens com o teclado
~~~html
<div tabindex='2'>edite</h2></div>
<div tabindex='1'>edite</h2></div>
~~~
- o atributo title na tag aparece quando passa o mouse
~~~html
<div title='edite 1'>edite</h2></div>
<div title='edite 2'>edite</h2></div>
~~~
[atributos globais mozilla](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Global_attributes)

---
- atributo abbr com title cria uma abreviação do conteúdo da tag
~~~html
<div> <abbr title='ola'>esse </abbr> edite</h2></div>

~~~
- tag address é onde se coloca infor de contato do autor do documento
~~~html
<address></address>
~~~
- lista de descrição
~~~html
<dt>
  <dt>olá</dt>
  <dd>descrição</dd>
</dl>
~~~
- meta favicon

existem vários modos de adicionar esse ícone,até frameworks para adicionar diversos ao html.

- meta para SEO
~~~html
<meta name="author" content='denise r'>
<title> titulo do site e pesquisa</title>
<meta name="description" content="descrição visivel a pesquisa do google">
<meta name="robots" content="index,follow">comandos para robô google
~~~

- meta rede sociais: existem metas personalizados
