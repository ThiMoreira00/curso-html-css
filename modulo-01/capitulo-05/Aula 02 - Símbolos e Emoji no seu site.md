Vídeo: https://youtu.be/nhMdFe3WwYc
Material em PDF: https://github.com/gustavoguanabara/html-css/blob/master/aulas-pdf/05%20-%20Caracteres%2C%20par%C3%A1grafos%20e%20quebras%20de%20linha.pdf

---

## Tags utilizadas

| **TAG**               | **SIGNIFICADO**                             |
| --------------------- | ------------------------------------------- |
| \<p>\</p>             | Parágrafo *(Paragraph)*                     |
| \<hr>                 | Linha horizontal *(Horizontal row)*         |
| \<br>                 | Quebra de linha *(Break row)*               |
| \&lt;                 | Menor que *(Less than)*                     |
| \&gt;                 | Maior que *(Greater than)*                  |
| &#x[código];          | Emoji                                       |
| \&reg;                | Caractere de marca registrada *(Copyright)* |
| \&trade;              | Caractere de *Trade Mark*                   |
| \&euro;               | Caractere da moeda Euro                     |
| \&pound;              | Caractere da moeda Pound                    |
| \&yen;                | Caractere da moeda Yen                      |
| \&cent;               | Caractere do Cent                           |
| \&Delta;              | Caractere Delta                             |
| \&uparrow; \| \&uarr; | Caractere de seta para cima                 |

## Ferramentas

* **Emojipedia**
*Site para visualizar todos os emojis possíveis.*
https://emojipedia.org/


## Código criado

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Parágrafos</title>
</head>
<body>
    <h1>Parágrafos e quebras de linha</h1>
    <hr>
    <p>Você pode escrever
        um parágrafo de
        qualquer jeito.
        Basta colocar tudo
        no meio do par de tags
        &lt;p&gt; e &lt;/p&gt; <!-- lt = Less Than (Menor que) | gt = Greater Than (Maior que) -->
    </p>
    <p>Se precisar quebrar
        o texto em algum lugar
        específico <br> como esse,
        você pode usar a tag &lt;br&gt;.
    </p>
    <p>
        Vamos adicionar alguns símbolos especiais:
        &reg; <!-- Marca registrada -->
        &copy; <!-- Copyright -->
        &trade; <!-- Trade Mark -->
        &euro; <!-- Euro -->
        &pound; <!-- Libra (Pound) -->
        &yen; <!-- Yen -->
        &cent; <!-- Cent -->
        &Delta; <!-- Delta (é diferente do "delta" em minúsculo) -->
        &uparrow; | &uarr; <!-- Seta para cima -->
    </p>
    <p>
        Vamos adicionar alguns emoji:
        &#x1F596; <!-- Vulcan Salute -->
        &#x1F913; <!-- Nerd Face -->
    </p>
</body>
</html>
```


![[modulo-01/capitulo-05/imagens/aula02-codigo-html.png]]
*Fonte: O autor. Acesso em: 05 mar. 2025.*