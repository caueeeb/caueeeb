# Olá, eu sou o Cauê Buzolin

**Estudante de Análise e Desenvolvimento de Sistemas (Fatec Taquaritinga) · Machine Learning e AI Engineering**

Construo projetos de machine learning com foco em **avaliação honesta** e em **engenharia ao redor do modelo**: dados reais, validação cronológica, APIs, testes automatizados e documentação das limitações. Estou buscando minha primeira oportunidade de estágio em IA / ML.

[LinkedIn](https://www.linkedin.com/in/caue-buzolin/) · [Portfólio](https://github.com/caueeeb/ai-engineering-portfolio) · [Hugging Face](https://huggingface.co/caueeb)

## Projetos em destaque

### Previsão de atrasos de entrega — Olist
[**delivery-prediction-ml**](https://github.com/caueeeb/delivery-prediction-ml)

Classificação de pedidos entregues após a data estimada (96.470 pedidos, 26 atributos, seis tabelas integradas).

- Separação cronológica treino/validação/teste; threshold escolhido na validação e teste usado uma única vez.
- API **FastAPI** com validação de entrada, **22 testes** automatizados, Ruff, **Docker** e **GitHub Actions**.
- `python -m src.train` reproduz o modelo versionado a partir dos dados brutos.
- Resultado no teste: Average Precision **0,072** contra **0,035** de linha de base (cerca de 2×), ROC-AUC 0,70. Sinal modesto, relatado como tal.

### Estudo de mudança de distribuição temporal
[**research/**](https://github.com/caueeeb/delivery-prediction-ml/tree/main/research) · [**Artigo técnico**](https://github.com/caueeeb/delivery-prediction-ml/blob/main/research/ARTICLE_TEMPORAL_DISTRIBUTION_SHIFT.md)

Por que as métricas caíram entre validação e teste? A taxa de atrasos foi de 7,82% (treino) para 3,49% (teste). O estudo mede deriva de atributos e do alvo, desempenho mensal, calibração e Brier score, e compara split aleatório com cronológico: o split aleatório teria dobrado o AP e o F1 aparentes, enquanto o ROC-AUC ficou em torno de 0,70 nos dois.

### Titanic — Kaggle
[**kaggle-titanic**](https://github.com/caueeeb/kaggle-titanic) · [**Modelo no Hugging Face**](https://huggingface.co/caueeb/titanic-survival-logistic-regression)

Pipeline scikit-learn, comparação de quatro modelos por validação cruzada, pontuação pública **0,77033** no Kaggle e modelo publicado com model card e script de inferência.

## Tecnologias

- **Linguagens:** Python, SQL/MySQL, C
- **Dados e ML:** pandas, NumPy, scikit-learn, Matplotlib, Seaborn, Jupyter
- **Engenharia:** FastAPI, Pydantic, pytest, Ruff, Docker, GitHub Actions, Git
- **Compartilhamento:** Hugging Face Hub

## Próximos passos

Melhorar o modelo de entregas (distância vendedor–cliente, histórico do vendedor sem vazamento temporal, calibração) e explorar aplicações com LLMs avaliadas com um conjunto de testes.

<details>
<summary><b>English</b></summary>

**Analysis and Systems Development student (Fatec Taquaritinga) focused on machine learning and AI engineering.** I build ML projects with honest evaluation and solid engineering around the model: real data, chronological validation, APIs, automated tests and documented limitations. I am looking for my first internship in AI / ML.

- **[delivery-prediction-ml](https://github.com/caueeeb/delivery-prediction-ml)** — late-delivery classification on Olist (96,470 orders, 26 features). Chronological split, FastAPI service, 22 tests, Docker and CI. Test Average Precision 0.072 vs. 0.035 chance level (about 2×), ROC-AUC 0.70.
- **[Temporal distribution shift study](https://github.com/caueeeb/delivery-prediction-ml/tree/main/research)** and **[technical article](https://github.com/caueeeb/delivery-prediction-ml/blob/main/research/ARTICLE_TEMPORAL_DISTRIBUTION_SHIFT.md)** — why metrics dropped between validation and test; random splits would have doubled the apparent AP and F1.
- **[kaggle-titanic](https://github.com/caueeeb/kaggle-titanic)** — scikit-learn pipeline, Kaggle public score 0.77033, model on [Hugging Face](https://huggingface.co/caueeb/titanic-survival-logistic-regression).

Stack: Python, SQL, C, pandas, NumPy, scikit-learn, FastAPI, pytest, Docker, GitHub Actions, Git, Hugging Face Hub.

</details>
