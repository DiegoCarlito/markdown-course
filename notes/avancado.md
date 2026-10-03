# Markdown Avançado

## Fórmulas Matemáticas
O Markdown suporta equações matemáticas formatadas nativamente, úteis para cálculos e fórmulas!

- **Na mesma linha (Inline):** Use um cifrão `$`.
  - Escrito: `A tensão é $V = R \cdot I$`
  - Resultado: A tensão é $V = R \cdot I$
- **Em bloco:** Use dois cifrões `$$`.
  ```markdown
  $$
  I_{stall} = \frac{V_{efetiva}}{R_a}
  $$
  ```

## Tabelas
Tabelas organizam o histórico de versão, cronogramas e dados de benchmark.

**Como criar:** Use barras verticais (`|`) para separar colunas e hífens (`-`) abaixo do cabeçalho.

```markdown
| Data | Versão | Descrição |
| --- | --- | --- |
| 02/10 | 1.0 | Criação |
| 03/10 | 1.1 | Ajuste |
```

## Adicionando Imagens e Diagramas
Para adicionar imagens ao Markdown, use um `!` antes dos colchetes do link:

```markdown
![Legenda da Imagem](./assets/caminho-da-imagem.png)
```

*Dica:* Se precisar alterar o tamanho de uma imagem grandona, você pode usar a tag do HTML direto no Markdown:
```html
<img src="./assets/foto.jpg" width="400">
```
