Padrões para HTML Semântico - Estrutural - Outline - HTML5
===============================================================================

## Problema
Como fazer a estrutura hierárquica da informação contida em um documento HTML5?

## Contexto
Além da aparência de estilo puramente visual, uma marcação HTML que respeita
uma estrutura hierárquica beneficia máquinas na associação de ao que
o conteúdo está relacionado. Isso afeta, em especial:

- Leitores de tela
- Processadores automáticos de HTML (ex.: mecanismos de busca)

Mesmo que estrutura semelhante possa ser atingida usando microformatos, o uso
de cabeçalhos (h1, h2, h3, h4, h5) é mais simples de implementar e
universalmente reconhecido para casos não muito específicos.

## Solução

Usar `h1`, `h2`, `h3`, `h4`, `h5` e `h6` de forma apropriada, com cuidado especial
aos efeitos na alteração de outline pelas tags seccionantes 
`article`, `aside`, `nav` e `section` Ver exemplos.

## Exemplos

Ver arquivo *exemplo.html* para exemplo e arquivo outline.md para estrutura 
resultante.

## Informação adicional

- http://www.w3.org/html/wg/drafts/html/master/sections.html#outlines
- http://www.w3.org/html/wg/drafts/html/master/dom.html#sectioning-content-0

## Padrões Relacionados