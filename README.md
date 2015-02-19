#StringToBinary
Classe que tem como objetivo simplificar a conversão de textos para conteúdo binário(```0001111```) e vice-versa.
##Uso:
Primeiramente se cria uma instancia da classe(```var bs = new StringToBinary();```), após isso você já pode utilizar os métodos da classe que são extremamente simples: **convert** e **reverse**. Veja o uso da cada um a seguir: 
###convert:
```javascript
//recebe como parametro apenas o string a ser convertido
bs.convert('abc');
//retornara um array com o codigo binario de cada caractere EX: [0000111, 0000111, 0000111]
```

###revert:
```javascript
//recebe como parametro apenas o string com o codigo binario
bs.revert('000100010001000100010001');
//retornara o string correspondente ao código binário EX: 'adc'
```

***Importante:***
O classe realizar apenas a conversão de bites completos ou seja com 8 dígitos

[por Douglas Santos](http://douglas.com.br)
