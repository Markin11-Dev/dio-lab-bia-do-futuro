# 📊 Leo, o Educador Financeiro

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![License](https://img.shields.io/badge/license-MIT-green)

---

## 🧠 Visão Geral

O **Leo, o Educador Financeiro** é um assistente inteligente desenvolvido para ajudar usuários a entender, organizar e melhorar sua vida financeira.

A solução utiliza **Inteligência Artificial + análise de dados** para interpretar o comportamento financeiro do usuário e fornecer orientações personalizadas de forma simples, prática e educativa.

---

## 🚀 Motivação

Muitas pessoas têm dificuldade em:

* Entender para onde vai seu dinheiro
* Organizar gastos mensais
* Tomar decisões de investimento
* Identificar oportunidades de economia

O projeto foi criado para resolver esse problema usando IA como um **educador financeiro digital acessível**.

---

## 🎯 Objetivos do Projeto

* Transformar dados financeiros em insights claros
* Simular um educador financeiro inteligente
* Auxiliar na tomada de decisão com base em dados reais
* Criar uma solução prática utilizando IA generativa

---

## ⚙️ Tecnologias Utilizadas

* **Python** → processamento e lógica
* **Pandas** → análise de dados
* **JSON / CSV** → armazenamento de dados
* **Streamlit** → interface interativa
* **Ollama (LLM local)** → geração de respostas inteligentes

---

## 🏗️ Arquitetura da Solução

```bash
📁 data/
 ├── perfil_investidor.json   # Dados do perfil do usuário
 ├── transacoes.csv          # Histórico financeiro

📁 app/
 ├── main.py                 # Aplicação principal (Streamlit)

📁 utils/
 ├── processamento.py        # (opcional) tratamento de dados

README.md
```

---

## 🔄 Como Funciona

1. 📥 **Entrada de Dados**
   O sistema carrega:

   * Perfil do investidor
   * Histórico de transações

2. ⚙️ **Processamento**
   Os dados são tratados e organizados para análise

3. 🧠 **IA (LLM)**
   O modelo interpreta os dados e responde com base no contexto

4. 📊 **Interface**
   O usuário interage via Streamlit com respostas claras e objetivas

---

## 💬 Exemplos de Perguntas

* “Como estão meus gastos este mês?”
* “Estou gastando mais do que deveria?”
* “Qual meu perfil de investidor?”
* “Onde posso economizar?”
* “Estou pronto para investir?”

---

## 🖥️ Interface (Exemplo)


```bash
📌 Dica: use prints mostrando perguntas e respostas do Leo
```

---

## 🚀 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/Markin11-Dev/dio-lab-bia-do-futuro
```

### 2. Acesse a pasta

```bash
cd dio-lab-bia-do-futuro
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4. Execute a aplicação

```bash
streamlit run app/main.py
```

### 5. Execute o modelo local (Ollama)

Certifique-se de que está rodando em:

```bash
http://localhost:11434
```

---

## ⚠️ Pontos de Atenção

* Modelos locais podem exigir **memória RAM suficiente**
* Verifique caminhos dos arquivos de dados
* Projeto com finalidade **educacional**

---

## 📈 Melhorias Futuras

* 📊 Dashboard com gráficos interativos
* 🤖 Classificação automática de gastos
* 🌐 Integração com APIs financeiras
* 📉 Alertas de comportamento financeiro
* 🧾 Recomendações de investimento mais avançadas

---

## 🧩 Diferenciais do Projeto

* Uso de **IA aplicada a dados reais**
* Simulação de um **educador financeiro**
* Integração entre **dados estruturados + linguagem natural**
* Interface simples e funcional

---

## 👨‍💻 Autor

Desenvolvido por **Marco Antonio**
Como parte de um desafio prático com foco em:

* Inteligência Artificial
* Análise de Dados
* Desenvolvimento de aplicações reais

---

## ⭐ Contribuição

Sinta-se à vontade para:

* Abrir issues
* Sugerir melhorias
* Contribuir com novas funcionalidades

---

## 📌 Considerações Finais

O **Leo** não substitui um especialista financeiro, mas atua como um **guia inteligente**, ajudando o usuário a tomar decisões mais conscientes e baseadas em dados.

---

💡 *Projeto ideal para demonstrar habilidades em IA, dados e desenvolvimento aplicado.*

