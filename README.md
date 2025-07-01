# 📊 Projeto: Pipeline de Dados com Python

Este projeto foi desenvolvido como parte de um desafio prático de curso, com o objetivo de simular um pipeline de dados real. Ele une duas fontes de dados diferentes, realiza transformações e fornece uma saída limpa e padronizada — pronta para ser consumida pelo time de Planejamento Integrado (PI) ou outras áreas da empresa.

---

## 🎯 Objetivos do Projeto

* Integrar diferentes fontes de dados (CSV e JSON)
* Realizar transformações e padronizações nos dados
* Construir um pipeline reutilizável e modular
* Aplicar conceitos de **Programação Orientada a Objetos (POO)** para organização do código
* Exportar os dados processados em um arquivo CSV

---

## 🛠️ Ferramentas e Tecnologias Utilizadas

* **Python 3**
* **Jupyter Notebook** (para prototipação inicial)
* **Programação Orientada a Objetos (POO)**
* **Bibliotecas:**

  * `pandas` (manipulação e análise de dados)
  * `json` (leitura de arquivos JSON)
  * `csv` (leitura e escrita de arquivos CSV)

---

## 🚀 Etapas do Pipeline

1. **Leitura dos dados**
   Carregamento de arquivos CSV e JSON de fontes distintas.

2. **Exploração inicial**
   Análise preliminar dos dados no Jupyter Notebook utilizando estruturas como `for` e `if`.

3. **Transformação dos dados**
   Tratamento de dados faltantes, renomeação de colunas e unificação dos registros em um formato consistente.

4. **Refatoração com Orientação a Objetos**
   Implementação da classe `Dados`, que encapsula toda a lógica do pipeline em métodos reutilizáveis e organizados.

5. **Exportação final**
   Salvamento do dataset final em um arquivo `.csv` limpo e padronizado.

---

## 🧠 Habilidades Desenvolvidas

* Manipulação de dados com Python e pandas
* Leitura e escrita de arquivos CSV e JSON
* Aplicação de boas práticas de programação orientada a objetos
* Organização e estruturação de projetos reutilizáveis
* Desenvolvimento de lógica aplicada a pipelines de dados

---

## 📁 Estrutura do Projeto

```bash
pipeline_dados/
│
├── data_raw/              # Dados brutos (entrada)
├── data_processed/        # Dados processados (saída)
├── pipeline.py            # Código principal do pipeline
├── dados_empresaA.json    # Fonte JSON
├── dados_empresaB.csv     # Fonte CSV
└── README.md              # Este arquivo
```

---

## 🌐 Como Executar

Clone o repositório:

```bash
git clone https://github.com/Cezanne369/pipeline_dados.git
```

Execute o script principal:

```bash
python pipeline.py
```

Verifique os dados processados na pasta `data_processed/`.

---

## 📢 Sobre o Projeto

Este pipeline foi criado para colocar em prática conceitos importantes da engenharia de dados, simulando um fluxo completo: da coleta à entrega de dados. A estrutura é totalmente modularizada e orientada a objetos, facilitando manutenção, expansão e reuso.

O projeto foi idealizado e construído por mim, **Jean Paul Cézanne**, com o apoio da comunidade e ferramentas de IA para referências, mas toda a implementação é de minha autoria.

---

## 📀 Conclusão

Este projeto marca um passo importante na minha formação como Engenheiro de Dados. Ele mostra minha capacidade de pensar de forma estruturada, aplicar boas práticas de programação e resolver problemas reais com código limpo e reutilizável.

Se quiser compartilhar feedback ou tiver dúcidas, fique à vontade para entrar em contato! 🙏

---

## 📩 Contato

* GitHub: [@Cezanne369](https://github.com/Cezanne369)
* LinkedIn: [Jean Paul Cézanne Silva Borja](https://www.linkedin.com/in/seu-perfil-aqui)
