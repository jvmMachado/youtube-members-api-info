# Bem-vindo ao Nerdpack Members List

Esta página fornece informações sobre o Nerdpack Members List, uma ferramenta de backend projetada para ajudar criadores de conteúdo do YouTube a gerenciar e interagir com os membros do seu canal.

**URL da API:** `https://youtube-members-637187041093.us-central1.run.app` (Apenas endpoints específicos são acessíveis e requerem autenticação via chave de API).

---

## O que faz esta API?

Esta API permite que o **proprietário autenticado de um canal do YouTube** liste os membros atuais do seu próprio canal. A principal funcionalidade é fornecer um endpoint (`/youtube/members/all`) que retorna uma lista de IDs de canal dos membros e seus níveis de assinatura.

**Caso de Uso Principal:** O proprietário do canal pode usar esta lista para integrar com seus próprios sistemas (website, aplicativo, Discord, etc.) para verificar se um usuário é um membro ativo e conceder benefícios ou permissões especiais.

**Importante:** Esta API é uma ferramenta de backend. Ela não possui uma interface de usuário própria para membros do canal ou para o público geral. O acesso aos dados é controlado pelo proprietário do canal através de chaves de API seguras.

---

## Política de Privacidade

**Última atualização:** 10/04/2025

Esta Política de Privacidade descreve como João Vitor Machado ("nós", "nosso") coleta, usa e protege as informações em conexão com o uso do Nerdpack Members List ("Serviço").

**1. Informações que Coletamos:**

* **Dados de Autenticação do Google (Proprietário do Canal):** Quando você (o proprietário do canal) se autentica usando sua Conta Google para autorizar o acesso do Serviço aos seus dados do YouTube, nós recebemos um token de acesso e um token de atualização do Google. Nós armazenamos o **token de atualização** de forma segura ([Descreva brevemente como: ex: "em um arquivo protegido no servidor", "usando o Google Secret Manager"]) para permitir que o Serviço acesse seus dados do YouTube em seu nome, conforme autorizado. Não armazenamos sua senha do Google.
* **Dados da API do YouTube:** Quando autorizado por você, o Serviço acessa a API de Dados do YouTube para recuperar:
    * Lista de membros do seu canal (incluindo ID do canal do membro, nome de exibição público, URL da foto do perfil pública, data de início da assinatura e nome do nível de assinatura). Isso é feito usando o escopo `youtube.channel-memberships.creator`.
    * O ID do seu próprio canal do YouTube para garantir que estamos consultando os dados corretos. Isso é feito usando o escopo `youtube.readonly`.
* **Chaves de API:** Armazenamos as chaves de API que você configura para permitir o acesso programático aos endpoints da sua API de backend.

**2. Como Usamos as Informações:**

* Para fornecer a funcionalidade principal do Serviço: listar os membros do seu canal quando solicitado por você através de uma chamada de API autenticada (usando sua chave de API).
* Para autenticar e autorizar o acesso aos seus dados do YouTube conforme suas permissões.
* Para manter e melhorar o Serviço.

**3. Compartilhamento de Informações:**

* **NÃO compartilhamos seus tokens de autenticação do Google ou os dados dos seus membros do canal com terceiros.**
* Os dados dos membros do seu canal (lista de IDs, nomes, níveis) são acessíveis **apenas para você** através dos endpoints protegidos pela sua chave de API. É sua responsabilidade proteger sua chave de API e como você usa esses dados em seus próprios sistemas.
* Podemos compartilhar informações se exigido por lei ou para proteger nossos direitos.

**4. Segurança de Dados:**

* Empregamos medidas de segurança para proteger as informações sob nosso controle, incluindo o armazenamento seguro do token de atualização e o uso de chaves de API para acesso aos dados. O serviço roda em infraestrutura segura do Google Cloud Run.

**5. Retenção de Dados:**

* Armazenamos seu token de atualização do Google enquanto você mantiver a autorização ativa para permitir o funcionamento contínuo do serviço. Você pode revogar o acesso a qualquer momento através das configurações da sua Conta Google ([link: https://myaccount.google.com/permissions](https://myaccount.google.com/permissions)). Após a revogação, não poderemos mais acessar seus dados do YouTube.
* Não armazenamos persistentemente a lista de membros do seu canal. Os dados são buscados da API do YouTube em tempo real quando você faz uma solicitação à nossa API.

**6. Seus Direitos:**

* Você tem o direito de revogar o acesso do Serviço aos seus dados do YouTube a qualquer momento através das configurações da sua Conta Google.
* Você tem controle sobre quem pode acessar os dados dos seus membros através da gestão das suas chaves de API.

**7. Uso de Dados da API do YouTube:**

* Este Serviço usa as APIs do YouTube. Ao usar este Serviço, você também concorda em estar vinculado aos Termos de Serviço do YouTube ([link: https://www.youtube.com/t/terms](https://www.youtube.com/t/terms)).
* Utilizamos os dados recebidos das APIs do YouTube estritamente para fornecer a funcionalidade descrita (listar membros para o proprietário do canal).
* A gestão e proteção da privacidade dos dados obtidos através das APIs do YouTube seguem as Políticas de Desenvolvedor das APIs do Google ([link: https://developers.google.com/terms/api-services-user-data-policy](https://developers.google.com/terms/api-services-user-data-policy)).

**8. Contato:**

* Se tiver dúvidas sobre esta Política de Privacidade, entre em contato conosco em: joaovmmachado@gmail.com

---

## Termos de Serviço

**Última atualização:** 10/04/2025

Estes Termos de Serviço regem o seu acesso e uso do Nerdpack Members List ("Serviço").

1.  **Aceitação dos Termos:** Ao acessar ou usar o Serviço, você concorda em cumprir estes Termos.
2.  **Uso do Serviço:** O Serviço destina-se exclusivamente a proprietários de canais do YouTube para listar os membros do seu próprio canal. Você é responsável por proteger suas credenciais de autenticação do Google e suas chaves de API.
3.  **Dados do YouTube:** O uso dos dados obtidos através das APIs do YouTube está sujeito aos Termos de Serviço do YouTube e às políticas de desenvolvedor relevantes. Você é responsável por como usa os dados dos membros obtidos através deste Serviço em seus próprios sistemas.
4.  **Disponibilidade:** Faremos esforços razoáveis para manter o Serviço operacional, mas não garantimos disponibilidade ininterrupta.
5.  **Limitação de Responsabilidade:** O Serviço é fornecido "como está". Não nos responsabilizamos por quaisquer danos diretos ou indiretos decorrentes do uso ou incapacidade de usar o Serviço.
6.  **Modificações:** Podemos revisar estes Termos periodicamente. A versão mais recente estará sempre disponível nesta página.
7.  **Contato:** joaovmmachado@gmail.com

---

*Desenvolvido por João Vitor Machado*

---

---

# English Version

---

# Welcome to Nerdpack Members List

This page provides information about Nerdpack Members List, a backend tool designed to help YouTube content creators manage and interact with their channel members.

**API URL:** `https://youtube-members-637187041093.us-central1.run.app` (Only specific endpoints are accessible and require API key authentication).

---

## What does this API do?

This API allows the **authenticated owner of a YouTube channel** to list their own channel's current members. The main functionality is providing an endpoint (`/youtube/members/all`) that returns a list of member channel IDs and their subscription levels.

**Primary Use Case:** The channel owner can use this list to integrate with their own systems (website, application, Discord, etc.) to verify if a user is an active member and grant special benefits or permissions.

**Important:** This API is a backend tool. It does not have its own user interface for channel members or the general public. Data access is controlled by the channel owner via secure API keys.

---

## Privacy Policy

**Last updated:** April 10, 2025

This Privacy Policy describes how João Vitor Machado ("we", "us", "our") collects, uses, and protects information in connection with the use of the Nerdpack Members List ("Service").

**1. Information We Collect:**

* **Google Authentication Data (Channel Owner):** When you (the channel owner) authenticate using your Google Account to authorize the Service's access to your YouTube data, we receive an access token and a refresh token from Google. We securely store the **refresh token** ([Briefly describe how: e.g., "in a protected file on the server", "using Google Secret Manager"]) to allow the Service to access your YouTube data on your behalf, as authorized. We do not store your Google password.
* **YouTube API Data:** When authorized by you, the Service accesses the YouTube Data API to retrieve:
    * Your channel's members list (including member's channel ID, public display name, public profile picture URL, membership start date, and membership level name). This is done using the `youtube.channel-memberships.creator` scope.
    * Your own YouTube channel ID to ensure we are querying the correct data. This is done using the `youtube.readonly` scope.
* **API Keys:** We store the API keys you configure to allow programmatic access to your backend API endpoints.

**2. How We Use Information:**

* To provide the core functionality of the Service: listing your channel members when requested by you via an authenticated API call (using your API key).
* To authenticate and authorize access to your YouTube data according to your permissions.
* To maintain and improve the Service.

**3. Information Sharing:**

* **We DO NOT share your Google authentication tokens or your channel members' data with third parties.**
* Your channel members' data (list of IDs, names, levels) is accessible **only to you** through the endpoints protected by your API key. It is your responsibility to protect your API key and how you use this data in your own systems.
* We may share information if required by law or to protect our rights.

**4. Data Security:**

* We employ security measures to protect the information under our control, including secure storage of the refresh token and the use of API keys for data access. The service runs on secure Google Cloud Run infrastructure.

**5. Data Retention:**

* We store your Google refresh token as long as you maintain active authorization to allow the service to function continuously. You can revoke access at any time through your Google Account settings ([link: https://myaccount.google.com/permissions](https://myaccount.google.com/permissions)). Upon revocation, we will no longer be able to access your YouTube data.
* We do not persistently store your channel's members list. The data is fetched from the YouTube API in real-time when you make a request to our API.

**6. Your Rights:**

* You have the right to revoke the Service's access to your YouTube data at any time via your Google Account settings.
* You have control over who can access your members' data through the management of your API keys.

**7. Use of YouTube API Data:**

* This Service uses YouTube APIs. By using this Service, you also agree to be bound by the YouTube Terms of Service ([link: https://www.youtube.com/t/terms](https://www.youtube.com/t/terms)).
* We use data received from YouTube APIs strictly to provide the described functionality (listing members for the channel owner).
* The management and protection of data privacy obtained through the YouTube APIs adhere to the Google API Services User Data Policy ([link: https://developers.google.com/terms/api-services-user-data-policy](https://developers.google.com/terms/api-services-user-data-policy)).

**8. Contact:**

* If you have questions about this Privacy Policy, please contact us at: joaovmmachado@gmail.com

---

## Terms of Service

**Last updated:** April 10, 2025

These Terms of Service govern your access to and use of the Nerdpack Members List ("Service").

1.  **Acceptance of Terms:** By accessing or using the Service, you agree to comply with these Terms.
2.  **Use of Service:** The Service is intended solely for YouTube channel owners to list their own channel members. You are responsible for safeguarding your Google authentication credentials and your API keys.
3.  **YouTube Data:** The use of data obtained through the YouTube APIs is subject to the YouTube Terms of Service and relevant developer policies. You are responsible for how you use the member data obtained through this Service in your own systems.
4.  **Availability:** We will make reasonable efforts to keep the Service operational, but we do not guarantee uninterrupted availability.
5.  **Limitation of Liability:** The Service is provided "as is". We are not liable for any direct or indirect damages arising from the use or inability to use the Service.
6.  **Modifications:** We may revise these Terms periodically. The most current version will always be available on this page.
7.  **Contact:** joaovmmachado@gmail.com

---

*Developed by João Vitor Machado*
