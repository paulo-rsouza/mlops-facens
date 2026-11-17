# Desafio 1: relatório

**Aluno(a):**

## 1. Versões dos dados

Rode o comando abaixo e complete a tabela com os 8 primeiros caracteres de cada md5:

```bash
for tag in dados-v1 dados-v2 dados-v3; do
  echo "$tag $(git show $tag:data/raw/bike.csv.dvc | awk '/md5/{print $3}')"
done
```

| Tag | md5 (8 primeiros caracteres) | Período |
|---|---|---|
| `dados-v1` | `fc7d423a` | 01/01/2011 a 31/12/2011 |
| `dados-v2` | | 01/01/2011 a 30/06/2012 |
| `dados-v3` | | 01/01/2011 a 31/12/2012 |

## 2. Comparação no mesmo teste

Copie os números de `reports/comparacao.json`.

**Período do teste:** ___ a ___ (___ linhas)

| Alias | Versão | RMSE | MAE | R² |
|---|---|---|---|---|
| `@champion` | | | | |
| `@challenger` | | | | |

## 3. Decisão

**Promovido ou rejeitado?**

**Justificativa (2 a 3 frases):**

## 4. O que cada ferramenta fez nesse projeto?

**Pergunta 01:**
Com suas palavras, quais os dois usos do DVC nesse projeto?


**Pergunta 02:**
Com suas palavras, para que serve o MLflow nesse projeto?

