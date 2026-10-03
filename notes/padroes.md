# Padrões e Usos de Projeto

## Rastreabilidade e Autoria
Saber quem fez o quê é crucial na equipe! Rastreie a documentação através destes padrões:

1. **Histórico de Versão (Tabelas):** O arquivo DEVE terminar com uma tabela documentando as edições e com o link do seu perfil (ex: `[Seu Nome](link)`).
2. **Links cruzados:** Use âncoras para rastrear requisitos nos textos (ex: o texto tem um `[RF59](#)` para conectar uma frase à lista oficial de requisitos).

## Template de Documentos
Copie e cole este modelo ao iniciar um documento novo:

```markdown
---
title: Nome do Componente
---

# Dimensionamento do [Componente]

## 1. Modelagem e Cálculos

$$
V = R \cdot I
$$
/// caption
Fonte: Elaborado pelo autor.
///

## 2. Resultados (Tabela)
| Parâmetro | Valor Nominal | Unidade |
| --- | --- | --- |
| Torque | 19 | N·m |

/// caption
Fonte: Elaborado pelo autor.
///

## 3. Anexos e Imagens

![Texto alternativo](../assets/imagem.png){: .center}
/// caption
Figura 1: Título da imagem. Fonte: Elaborado pelo autor.
///

## Histórico de versão
| Data | Versão | Descrição | Autor | Revisor |
| --- | --- | --- | --- | --- |
| DD/MM/2026 | 1.0 | Criação do doc | [Seu Nome](link) | [Nome] |
```
