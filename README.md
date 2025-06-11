# apim-test-for-challenge
The following repository was created by me as part of a Bootcamp project for evaluation and approval purposes. Although the task involves basic steps and configurations, the implementation was carried out according to the requirements described in the Challenge Description.

#⚠️IMPORTANTE⚠️ 
### O Lab a seguir foi feito em uma Subscription Trial do Azure e, no momento da leitura, já pode ter sido deletada

---
> ⚠️ O seguinte README refere-se a um projeto para a obtenção de nota ou aprovação em um Bootcamp da [Digital Innovation One](https://www.dio.me/en) e está de acordo com a respectiva **"Descrição do Desafio"** que possuir.  
> Em determinados casos, o projeto possui entregas **simplesmente visuais que sejam apresentadas neste README do GitHub**. Neste caso, a entrega do projeto será realizada por **meio deste arquivo**.

---

## 📝 Descrição

Este projeto tem como objetivo demonstrar o processo de configuração de uma API no Azure API Management (APIM) a partir de um App Service, além da configuração de subscription. Todas as ações foram realizadas conforme demonstrado nas imagens anexadas.

---

## 🎯 Objetivos do Projeto

Ao concluir este desafio, você será capaz de:

- ✅ Criar uma API a partir de um App Service no Azure API Management.
- ✅ Configurar a API com suffix personalizado e Base URL.
- ✅ Criar subscriptions no APIM para gerenciamento de chaves de API.
- ✅ Analisar a resposta HTTP gerada pela requisição.

---

## 🖥️ Passos Realizados

A seguir, os passos executados para a realização deste projeto:

### 🔹 Criação da API no Azure API Management

Foi utilizado o Azure API Management Service para criar uma nova API a partir de um App Service existente. No painel lateral, na seção **APIs**, foi selecionado **Add API** > **App Service** e, em seguida, preenchidos os campos de acordo com as imagens a seguir:

- **App Service**: app-web-app-labMACN01  
- **Display name**: app-web-app-labMACN01  
- **Name**: app-web-app-labmacn01  
- **API URL suffix**: ph-lab-macn  
- **Base URL**: https://phapimpay01.azure-api.net/ph-lab-macn/

![Captura de tela 2025-06-11 111237](https://github.com/user-attachments/assets/af5254be-bc15-4707-a6db-7d97b818e443)

![Captura de tela 2025-06-11 111246](https://github.com/user-attachments/assets/84d48c9e-ce61-4bbe-b294-bc0cd69f1c1b)

![Captura de tela 2025-06-11 111308](https://github.com/user-attachments/assets/6b498190-4828-4c04-8cf3-fb171fb9325c)


---

### 🔹 Configuração da Subscription

No Azure API Management, foi criada uma subscription chamada **APIsPagamento** com os seguintes campos:

- **Name**: APIsPagamento  
- **Display Name**: APIs Pagamento  
- **API**: app-web-app-labMACN01  
- **User**: Administrator  
- **Product**: Starter  
- **Scope**: API
  
![Captura de tela 2025-06-11 114842](https://github.com/user-attachments/assets/12c98be6-640f-4e3c-99d6-79cac0374648)

---

## 🖼️ Evidências Visuais


![Captura de tela 2025-06-11 115329](https://github.com/user-attachments/assets/15c49a9b-7ff6-4cb4-9e06-9ca9862cfbb8)

Gerando App Registration

![Captura de tela 2025-06-11 115401](https://github.com/user-attachments/assets/54f07e70-3681-43a2-b483-439bb6317b96)



Gerando Secret

![Captura de tela 2025-06-11 115659](https://github.com/user-attachments/assets/89f7cfd7-d584-456e-bee1-22d1b37fe5a4)

---

## 🧾 Notas Finais

Este README é um modelo padrão reutilizável para projetos desenvolvidos em bootcamps da [Digital Innovation One](https://www.dio.me/en).  
Adapto conforme o desafio proposto, mantendo a estrutura clara e objetiva.

---
