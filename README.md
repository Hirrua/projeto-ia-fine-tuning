# 🧉 Assistente de Turismo da Serra Gaúcha — Fine-Tuning de LLM
Bem-vindo(a)! Este repositório reúne o projeto final da disciplina de Inteligência Artificial, onde desenvolvemos um especialista virtual em turismo para a região da Serra Gaúcha (RS) por meio do fine-tuning de um modelo de linguagem de grande porte.

## 🚀 Como Executar
1️⃣ Acesse Google Colab.

2️⃣ Vá em Ambiente de execução > Alterar tipo de ambiente de execução e selecione GPU T4.

3️⃣ Execute o notebook célula por célula, seguindo esta ordem:

- Monte o Google Drive
- Instale as bibliotecas
- Realize o login no Hugging Face

4️⃣ Antes de rodar a última célula (avaliação), reinicie a sessão em ambiente de execução > reiniciar ambiente de execução.

5️⃣ Execute a última célula para rodar os testes. Um item aleatório do dataset de teste será avaliado.

## 🎯 Sobre o Projeto
O objetivo foi customizar o modelo google/gemma-2-2b-it para atuar como um guia turístico da Serra Gaúcha. Com um dataset próprio, treinamos o modelo para:

✅ Responder dúvidas frequentes

✅ Sugerir roteiros personalizados

✅ Fornecer informações detalhadas da região

Utilizamos o Fine-Tuning com eficiência de parâmetros (PEFT), aplicando a técnica LoRA (Low-Rank Adaptation) para otimizar o processo.

## 🧩 Tecnologias Utilizadas
- Framework: PyTorch
- Ecossistema de Modelos: Hugging Face
- Transformers: Para carregar o modelo e o tokenizador
- Peft: Para aplicar LoRA
- Datasets: Para manipulação dos dados
- Evaluate: Para calcular métricas (ex.: ROUGE)
- Ambiente: Google Colab (GPU T4)

## 📂 Estrutura do Repositório
Trabalho_IA.ipynb — Notebook principal com todas as etapas: preparação de dados, treinamento, fusão e avaliação.

dataset_bruto.json — Dataset completo com todos os pares instrução-resposta (não é necessário subir no colab esse arquivo, apenas para visualização dos dados).

Trabalho_IA.pdf — Relatório técnico com a fundamentação teórica, resultados, dificuldades enfrentadas e conclusões.
