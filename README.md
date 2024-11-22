Observações sobre o Código:

Importação Necessária:

O código importa a biblioteca re, que é utilizada para trabalhar com expressões regulares em Python.

Definição da Função:

A função verificar_ordem_letras recebe duas entradas: palavra e frase.
Dentro da função, o padrão é gerado a partir da palavra utilizando '.*'.join(list(palavra)), o que cria um padrão que verifica se cada letra da palavra aparece na frase na mesma ordem, mas não necessariamente contígua.

A função utiliza re.search para verificar se o padrão está presente na frase.


Testes da Função:

A função é testada com duas frases (frase1 e frase2).
O resultado é impresso, indicando se as letras da palavra_fornecida aparecem na mesma ordem nas frases fornecidas.


![image](https://github.com/user-attachments/assets/8731445f-8147-4874-b26a-c39d3c72c725)
