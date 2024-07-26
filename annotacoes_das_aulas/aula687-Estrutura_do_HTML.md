# Estrtura do HTML
Todo e qualquer site que voce utiliza usa HTML. É a triáde HTML, CSS e javascript.
O HTML é como um arquivo de texto, par entender melhor vamos criar um arquivo  html chamado de index.html
- html é case insensitive, ou seja, não faz diferença pro HTML se voce está escrevendo açgo com letra maiúscula ou minúscula


### Tags
- são identificadas com os sinais <></> e podem ter corpo como podem não ter.
- as tags possuem atributos que são colocados dentro delas e esse atributos reccebem valores
~~~html
<escreve atributo="valor1 valor2"> 
    <algumaoutratag>
        <naotemcorpo atributo="valor1 valor2">
    </algumaoutratag>
</escreve>
~~~

### tag !DOCTYPE html
- vai especificar pro nosso navegador que estamos utilizando a versão HTML5 

~~~html
<!DOCTYPE>
~~~

### tag html
- nela podemos definir a linguagem do nosso arquivo
~~~html
<html>

</html>
~~~

### tag head
- define os metadados do nosso arquivo HTML
~~~html
<head></head>
~~~

### tag title
- Tag de título da sua página
~~~html
<title></title>
~~~

### tag meta
- define a codificação dos caracteres
~~~html
<meta charset="utf-8">
~~~

Até aqui todas as tags citadas acia são utilizadas dentro da tag *head*

### tag body
- Tudo que você vê em um site, está na tag body
~~~html
    <body>
        
    </body>
~~~
- A tag body não é necessária para validar um arquivo html, porém é fortemente recomendado que se utilize essa tag em todo arquivo html.