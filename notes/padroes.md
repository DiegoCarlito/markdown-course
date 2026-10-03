# Padrões e Usos de Projeto

## Rastreabilidade e Autoria
Saber quem fez o quê é crucial na equipe! Rastreie a documentação através destes padrões:

1. **Histórico de Versão (Tabelas):** O arquivo DEVE terminar com uma tabela documentando as edições e com o link do seu perfil (ex: `[Seu Nome](link)`).
2. **Coautoria nos Commits:** Trabalhou em dupla? Adicione `Co-authored-by: Nome <email>` na mensagem do commit para os dois ganharem crédito.
3. **Links cruzados:** Use âncoras para rastrear requisitos nos textos (ex: o texto tem um `[RF59](#)` para conectar uma frase à lista oficial de requisitos).

## Padrões de Merge Request
Ao submeter alterações, sua postagem deve obrigatoriamente seguir este template:

```markdown
### Descrição
Descreva objetivamente o que foi adicionado ou modificado.

### Motivação e contexto
Explique por que a mudança foi necessária.

### Como validar
Liste os passos para testar e validar a alteração.
```

## Template de Documentos
Copie e cole este modelo ao iniciar um documento novo:

```markdown
---
title: Nome do Componente
---

# Dimensionamento do [Componente]

## 1. Modelagem e Cálculos
[Insira as memórias de cálculo e referências aqui]

$$
V = R \cdot I
$$
<center>Fonte: Elaborado pelo autor.</center>

## 2. Resultados (Tabela)
| Parâmetro | Valor Nominal | Unidade |
| --- | --- | --- |
| Torque | 19 | N·m |

<center>Fonte: Elaborado pelo autor.</center>

## 3. Anexos e Imagens

**Forma 1 (Padrão MkDocs com Markdown):**
![Texto alternativo](../assets/imagem.png){: .center}
/// caption
Figura 1: Título da imagem. Fonte: Elaborado pelo autor.
///

**Forma 2 (Usando HTML puro):**
<figure>
  <figcaption><b>Figura 2</b> — Título da imagem.</figcaption>
  <img src="../assets/imagem.png" alt="Texto alternativo">
  <figcaption>Fonte: Elaborado pelo autor.</figcaption>
</figure>

## Histórico de versão
| Data | Versão | Descrição | Autor | Revisor |
| --- | --- | --- | --- | --- |
| DD/MM/2026 | 1.0 | Criação do doc | [Seu Nome](link) | [Nome] |
```
