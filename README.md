# -Executando-Tarefas-Automatizadas-com-Lambda-Function-e-S3

# 🚀 Executando Tarefas Automatizadas com Lambda Function e S3

## 🧰 Tecnologias Utilizadas

- **AWS Lambda** – execução de código sem servidor
- **Amazon S3** – armazenamento de objetos e gatilho de eventos
- **IAM (Identity and Access Management)** – controle de permissões
- **AWS Console / CLI** – gerenciamento dos recursos
- **GitHub** – versionamento e documentação

---

## ⚙️ Etapas da Implementação

1. **Criação do Bucket S3**
   - Nome único e público para testes
   - Habilitação de eventos para upload (`PUT`)

2. **Criação da Função Lambda**
   - Linguagem utilizada: Python ou Node.js
   - Código que processa o evento (ex: log, mover arquivo, gerar resposta)

3. **Vinculação do Evento S3 à Lambda**
   - Configuração de gatilho no console da AWS
   - Permissões via IAM para permitir execução

4. **Testes e Validação**
   - Upload de arquivos no bucket
   - Verificação de logs no CloudWatch
   - Comportamento esperado da função
---

## 📚 Aprendizados e Insights

- Entendi como **eventos do S3** podem ser usados para acionar funções Lambda automaticamente.
- Aprendi a configurar **permissões corretas** para que os serviços se comuniquem com segurança.
- Vi na prática como **CloudWatch** ajuda a monitorar e depurar funções Lambda.
- Refleti sobre como essa automação pode ser aplicada em cenários reais, como processamento de imagens, validação de arquivos ou geração de relatórios.


Se quiser, posso te ajudar a revisar o código da função Lambda ou montar o template CloudFormation para automatizar tudo. É só me chamar!
