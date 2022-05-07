# Lembrar
## Escreva títulos inteligentes
- significativos
- palavras-chave (buscas)

## Metatags
- charset: Acentuação e caracteres especiais
- description: `<meta name="description" content="">`  
É possível incluir uma "description" do site, assim, quando procuramos o mesmo no google, aparece uma descrição dele.
- viewport: permite a adaptação de diversos dispositivos

## Não utilizar propriedade Style
- Não utilizar a propriedade `style` dentro da tag html.
- Usar código css separado do arquivo html.
- Código sujo
- Especificidade x !important

## Importação de CSS e de JS
### Importação de CSS
Para importação do CSS separado, podemos fazer da seguinte maneira:
```css
<head>
   <link rel="stylesheet" href="style.css">
</head>
```
### Importação de JavaScript
Para importação do JavaScript separado, podemos fazer da seguinte maneira:
```html
<head>
   <script src="script.js" async/defer></script>
   <body>


      <script src="script.js"></script>
   </body>
</head>
```
## Atributos de Acessibilidade
- img:alt: assim que preenchido, o leitor de tela irá ler a imagem, útil para quem não pode enxergar
- title: Mostra uma caixa de dica com o texto configurado
- aria
- tabindex: Quando pressionado a tecla "tab" é possível navegar pelos campos de um formulário em ordem.

## Escrita
- letras minúsculas
- fechamento de tags
- formatação e limpeza de código
  - prettier

## Formulários
- fieldset + legend
- label + input

## Compress HTML
- Diminui o tamanho do arquivo
- Automatizado vs manual
  - Online Tool
  - Gulp (or webpack?)

## Validar o HTML
- Verificar os padrões
- Alertas e erros
- Lighthouse(DevTools)
- https://validator.w3.org
