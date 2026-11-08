# T2 — Previsão do vencedor de uma corrida de F1 (EMA9824, 2026/2)

Autores: Gustavo Salmazo da Silva · Gustavo Henrique Baliero Lima

## Reproduzir a figura do M2
1. Abrir `T2_M2_baseline.ipynb` no Google Colab (CPU basta).
2. `Runtime > Run all`. O notebook baixa os dados da fonte original (Kaggle `rohanrao/formula-1-world-championship-1950-2020`), treina o baseline e gera `m2_baseline.png` e `m2_metrics.json`.

## Ambiente
Colab (CPU), Python 3.x; pacotes em `requirements.txt` (já presentes no Colab). Sementes: 0–4 (5 execuções). Nenhum dado é versionado neste repositório.

## Divisão (temporal)
Treino 1950–2018 · Validação 2019–2021 · Teste 2022–2024 (**não avaliado no M2**; consultado uma única vez no M3).

## Arquivos
- `T2_M2_baseline.ipynb` — notebook do M2 (limpo, para executar no Colab)
- `T2_M2_baseline_executed_local.ipynb` — execução de referência (local, CPU)
- `results/` — figura e métricas da execução de referência
- `M2_relatorio.md` — figura + parágrafo do M2
