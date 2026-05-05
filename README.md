# 🤖 Automação Inteligente de Atendimento de E-mails com IA

## 📌 Visão geral
Projeto de automação desenvolvido para otimizar o atendimento de e-mails, utilizando Inteligência Artificial para classificar dúvidas, buscar respostas em uma base de conhecimento (FAQ) e gerar respostas assistidas com validação humana.

---

## ⚠️ Problema
Empresas lidam com alto volume de e-mails, muitos deles contendo dúvidas repetitivas. Isso gera:
- Tempo elevado de resposta  
- Sobrecarga no suporte  
- Falta de padronização  

---

## 💡 Solução
Desenvolvi uma automação no :contentReference[oaicite:0]{index=0} que:
- Classifica automaticamente os e-mails  
- Consulta uma base de FAQ em planilha  
- Utiliza IA para decidir e gerar respostas  
- Encaminha casos complexos para atendimento humano  

---

## ⚙️ Como funciona
1. Leitura automática de e-mails via Outlook  
2. Classificação inicial (dúvida ou não)  
3. Consulta na base de conhecimento (planilha FAQ) para encontrar perguntas e respostas relacionadas  
4. IA analisa e classifica como FAQ ou não  
5. Decisão:
   - ✅ FAQ:
     - Gera resposta baseada na base de conhecimento  
     - Cria rascunho para validação humana  
   - ❌ Não FAQ:
     - Encaminha para suporte humano  
6. Organização automática dos e-mails em pastas  

---

## 🧠 Inteligência aplicada
O sistema utiliza uma abordagem de **busca em base de conhecimento + geração de resposta com IA**, semelhante a um modelo simplificado de RAG (Retrieval-Augmented Generation), garantindo respostas mais precisas e contextualizadas.

---

## 🛠️ Tecnologias utilizadas
- :contentReference[oaicite:1]{index=1}  
- IA (Groq API)  
- Excel (base de conhecimento - FAQ)  
- Outlook (entrada e saída de e-mails)  

---

## 📊 Resultados esperados
- Redução do tempo de triagem de e-mails  
- Automação de respostas para dúvidas recorrentes  
- Padronização do atendimento  
- Melhor organização e rastreabilidade  

---

## 🚀 Diferenciais
- Integração entre múltiplas ferramentas  
- Uso prático de IA em um cenário real  
- Human-in-the-loop (validação antes do envio)  
- Base de conhecimento dinâmica (FAQ evolutivo)  

---

## 📷 Fluxo da automação
<img width="1356" height="634" alt="fluxo" src="https://github.com/user-attachments/assets/2c4282d2-3f29-4f67-ba9c-48f722e553da" />

---

## 📌 Possíveis melhorias
- Implementação de busca semântica (RAG completo)  
- Score de confiança da IA para decisões automáticas  
- Dashboard de métricas no :contentReference[oaicite:2]{index=2}  
- Aprendizado contínuo baseado em novos atendimentos  

---

## 👨‍💻 Autor
Otávio Custódio  
