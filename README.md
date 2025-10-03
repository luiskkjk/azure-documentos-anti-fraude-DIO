# 💳 Analisador de Cartão de Crédito com Azure Document Intelligence - Documentos Anti-Fraude

* Esse projeto integra um Desafio de Projeto proposto pelo **Microsoft Certification Challenge #4 - AI 102**, curso disponibilizado pela DIO. No projeto, foi realizado uma implementação de recursos de IA do Azure para fazer a verificação e validação de cartões.

* O arquivo de imagem é primeiro enviado para o **Azure Blob Storage** antes de ser processado pela IA.

---

## 🌟 Recursos Principais

* **Upload de Arquivos:** Interface Streamlit para upload de imagens de cartões de crédito (JPG, JPEG, PNG).
* **Armazenamento:** Envio da imagem para o Azure Blob Storage.
* **Recursos Azure:** Utiliza os recursos AI Document Intelligence e a Conta de Armazenamento

---

## 🛠️ Pré-requisitos e Configuração

### 1. Pré-requisitos

Para rodar este projeto, você precisará de:

* **Python 3.10+**
* **Conta Azure** com os seguintes recursos:
    * Um recurso de **Azure AI Document Intelligence** (para **Endpoint** e **Chave**).
    * Uma **Conta de Armazenamento** do Azure (para **String de Conexão** e **Nome do Container**).

### 2. Como executar

* **Copiar o repositório utilizando o comando:**

```bash
git clone https://github.com/luiskkjk/azure-documentos-anti-fraude-DIO
```

* Instale os requisitos presentes em "requirements.txt"
```bash
pip install -r requirements.txt
```

* Executar o **streamlit** com o comando:
```bash
streamlit run app.py
```
