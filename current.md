---
title: Notas de versão mais recentes
description: Saiba mais sobre as notas de versão mais recentes, os novos recursos e a nova documentação dos produtos e serviços para  [!DNL Experience Cloud] . Encontre ajuda e novos tutoriais sobre o [!DNL Experience Cloud], [!DNL Creative Cloud for enterprise], and [!DNL Document Cloud].
doc-type: release notes
last-update: February 2022
author: mfrei
mini-toc-levels: 1
exl-id: bcbdba6a-9e24-4f84-97ca-65c24ef45707
source-git-commit: f4b652db4759a65f38afe0fbd6dca07301875277
workflow-type: tm+mt
source-wordcount: '4963'
ht-degree: 51%

---

# Notas de versão da Adobe Experience Cloud - Fevereiro de 2022

![Banner](assets/experience-cloud-banner-3.png)

Como um Criador de experiências, seu caminho para o sucesso começa com [Adobe Experience League](https://experienceleague.adobe.com/?lang=en#home). Encontre uma vasta biblioteca de documentação de instruções, tutoriais autoguiados, vídeos de instruções e cursos para todos os níveis e funções, uma comunidade online de pares e suporte especializado quando precisar.

Pronto para começar? [Faça um teste de 5 minutos e ganhe](https://exploreadobe.com/experience-league-quiz/?sdid=4NM897N2&amp;mv=email&amp;mv2=nslsp)!

>[!NOTE]
>
>Para receber uma notificação por email mensal sobre atualizações nessa página, assine a [Atualização Prioritária de Produto da Adobe](https://www.adobe.com/subscription/priority-product-update.html). Verifique com frequência para ficar por dentro do que está acontecendo na Experience League.

**Fevereiro de 2022**

Última atualização: **11 de fevereiro de 2022**

* [[!DNL Experience League] Eventos](#events)
* [[!UICONTROL Status do Sistema] da Adobe](#status)
* [[!DNL Experience Cloud Central Interface Components] &amp; Administração](#ecloud)
* [[!DNL Adobe Experience Platform]](#platform)
* [[!DNL Adobe Analytics]](#analytics)
* [[!DNL Customer Journey Analytics]](#cust-journey)
* [[!DNL Adobe Audience Manager]](#aam)
* [[!DNL Adobe Experience Manager]](#aem)
* [[!DNL XML Documentation for Adobe Experience Manager]](#xml-doc)
* [[!DNL Adobe Commerce]](#magento)
* [[!DNL Adobe Target]](#target) (Atualizado em: **3 de fevereiro de 2022**)
* [[!DNL Adobe Campaign]](#ac)
* [[!DNL Adobe Journey Optimizer]](#journey-opt)
* [[!DNL Journey Orchestration]](#journey-orch)
* [[!DNL Adobe Marketo Engage]](#marketo)
* [[!DNL Adobe Workfront]](#workfront)
* [[!DNL Adobe Advertising Cloud]](#adcloud)
* [[!DNL Adobe Document Cloud]](#doc-cloud)
* [[!DNL Adobe Creative Cloud for enterprise]](#creative-cloud)
* [Digital Experience Blueprints - tutoriais](#blueprints)

Precisa de ajuda? Visite a [Adobe Experience League](https://experienceleague.adobe.com/?lang=pt-BR#home) para encontrar documentação técnica e de produtos, cursos com curadoria da Adobe, tutoriais em vídeo, respostas rápidas, insights da comunidade e treinamento ministrado por instrutores.

## ![Ícone](/assets/experience-league.png) [!DNL Experience League] Eventos {#events}

Experience League Events são um excelente local para obter respostas de especialistas sobre produtos da Adobe. Três tipos de eventos incluem:

| Tipo de evento | Descrição |
| -----------|---------- |
| [Experience League LIVE ](#exl-live) | Um streaming ao vivo produzido pela equipe do Experience League e hospedado no YouTube. É uma chance de se conectar com especialistas em produtos da Adobe e aprender dicas, truques e estratégias úteis que podem ser usadas com os aplicativos da Adobe Experience Cloud.<br> Role para baixo para saber mais sobre eventos futuros e assistir a eventos anteriores hospedados em [Experience League Live](https://experienceleague.adobe.com/docs/experience-league-live-events/events/overview.html?lang=pt-BR). |
| [Coffee breaks com perguntas e respostas da comunidade ](#coffee) | Passe uma hora com um convidado especial e envie suas perguntas nas comunidades da Experience League! Obtenha respostas de especialistas em produtos do Adobe Pegue um café e converse com Gerentes de produtos do Experience League Communities.<br>Role para baixo para ler sobre o que cobriremos. Não se esqueça de se registrar antes que seja tarde demais! |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=pt-BR) | Eventos de vídeo sob demanda disponíveis no Experience League. |

{style=&quot;table-layout:auto&quot;}

### Experience League LIVE {#exl-live}

| Data do evento | Hora | Nome do evento | Formato | Descrição |
| -----------| ---------- | ---------- | ---------- |---------- |
| 3 de fevereiro de 2022 | Por demanda | [Apresentação de todas as novas Demonstrações de Referência no AEM](https://www.youtube.com/watch?v=FEREXV826NQ) | Evento de vídeo ao vivo | Aprenda a maneira mais rápida de provisionar, testar e explorar os recursos do AEM as a Cloud Service. |

{style=&quot;table-layout:auto&quot;}

### Sessão de perguntas e repostas da comunidade {#coffee}

| Nome do evento | Data | Aplicativos | Formato | Descrição |
| -----------| ---------- | ---------- | ---------- |---------- |
| Comunidade e intervalo do Adobe Target | 23 de fevereiro de 2022 às 8h PST | Adobe Target, Experience Platform, RTCDP | Perguntas e respostas do fórum | [Inscreva-se já](http://atcommunityqacoffeebreak.splashthat.com/?utm_source=in-product&amp;utm_medium=gainsight&amp;utm_campaign=coffee_talk_AT&amp;utm_content=220223)! Junte-se a nós na Adobe Target Community das 8h às 9h PT para obter respostas de especialistas da Vishal Chordia, gerente sênior de produtos. Ele responderá a todas as perguntas relacionadas à Adobe Experience Platform (AEP), Personalização baseada em público-alvo, Real-time Customer Data Platform (RTCDP) integração com o Target e Adobe Target geral |

{style=&quot;table-layout:auto&quot;}

### Adobe Developer&#39;s Live {#dev-live}

| Evento | Data e hora | Tipo | Descrição |
| -----------| ---------- | ---------- |---------- |
| [Adobe [!DNL Developers Live]](https://experienceleague.adobe.com/docs/adobe-developers-live-events/events/2021/oct2021/overview.html?lang=en) | Por demanda | Vídeo | A [!DNL Developers Live] apresenta os mais recentes avanços tecnológicos e ferramentas de desenvolvedores que impulsionam o design, os fluxos de trabalho de criação de conteúdo, os serviços de documento e o gerenciamento de experiência do cliente em todos os setores. Assista o discurso de apresentação, aprenda sobre APIs do Analytics, camadas de dados do cliente, projetos de código aberto do Adobe I/O e muito mais. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/system-status.png) [!DNL Adobe System Status] {#status}

O [!DNL Adobe System Status] fornece informações detalhadas, atualizações de status e notificações por email sobre eventos de interrupção e manutenção de produtos e serviços da Adobe. Confira em [status.adobe.com](https://status.adobe.com/pt-BR).

Data de lançamento: **16 de novembro de 2021**

**Novidades**

* O Status do Adobe agora relata incidentes em um nível de Produto. As páginas da nuvem de status e do produto têm uma nova aparência e filtros aprimorados com base no relatório de incidentes no nível do produto. Isso facilita a compreensão de como o produto é afetado em [status.adobe.com](https://status.adobe.com/) e em suas notificações por email. Se você não tiver assinado, use este link para configurar suas preferências de assinatura personalizadas [https://status.adobe.com/proactive-notifications/manage](https://status.adobe.com/proactive-notifications/manage).

* A página inicial de status agora é personalizada com eventos filtrados com base em seus direitos e assinaturas de produto. Verifique em **status.adobe.com** > **[!UICONTROL Meus eventos]** guia .

**Novos recursos e melhorias disponíveis hoje**

| Recurso | Descrição |
| ------- | -------|
| Comunicação de incidentes a nível do produto | <ul><li>Cada produto tem um banner [!UICONTROL Status] que inclui atualizações, histórico e atributos de impacto mais recentes do produto</li><li>Os emails agora seguem o mesmo formato do relatório de impacto no nível do produto em vez de relatórios no nível do incidente</li></ul> |
| Visão personalizada do [!UICONTROL Status] página inicial | <ul><li>Apresentando uma nova visão, **[!UICONTROL Meus eventos]** no [!UICONTROL Visão geral] página. Essa exibição filtra eventos com base em seus direitos e assinaturas</li><li>Os direitos podem ser para organizações ou indivíduos. As assinaturas podem ser para produtos ou eventos</li></ul> |
| Experiência do usuário aprimorada | <ul><li>As páginas do Cloud têm um resumo da disponibilidade de todos os produtos e uma capacidade de filtrar por produto, região, datas e tipos de evento</li><li>As páginas do produto têm um resumo da disponibilidade de todos os recursos e uma exibição detalhada dos eventos e do histórico</li><li>Os filtros aprimorados estão disponíveis por capacidade, data centers/ambientes (quando aplicável), região, data, tipo de evento e status de incidente/manutenção</li></ul> |
| Atualizações aprimoradas de assinaturas com ofertas de produtos | <ul><li>As ofertas do Adobe Analytics são atualizadas para uma exibição simples do cliente (existente [!DNL Analytics] as subscrições são migradas para novas ofertas)</li><li>Ofertas granulares para [!DNL Customer Journey Analytics]</li></ul> |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/ec_appicon_24.png) [!DNL Experience Cloud Central UI Components] e administração {#ecloud}

| Recurso | Descrição |
| ------- |-------|
| **[!UICONTROL Recentes]** (atalhos) adicionados a [Experience Cloud](https://experience.adobe.com/home) aterrissagem | Você pode acessar atalhos para as atividades mais recentes do Journey Optimizer e do Experience Platform no novo **[!UICONTROL Recentes]** cabeçalho. Essa atualização também inclui melhorias gerais de layout e capacidade de resposta na página de aterrissagem. |
| **[!UICONTROL Sandboxes]** movido para a barra de cabeçalho | O indicador Sandboxes agora é integrado no cabeçalho para todos os aplicativos de interface do Experience Platform. Consulte [Sandboxes](https://experienceleague.adobe.com/docs/experience-platform/sandbox/ui/user-guide.html?lang=pt-BR) no Experience Platform para obter mais informações. |

{style=&quot;table-layout:auto&quot;}

**Mais recursos de ajuda sobre o [!DNL Experience Cloud Central UI Components] e administração**

* [Notas de versão](https://experienceleague.adobe.com/docs/core-services/interface/release-notes/release-notes.html?lang=en) para Componentes da interface do usuário central do Experience Cloud
* [Gerenciamento de usuários e produtos](https://experienceleague.adobe.com/docs/core-services/interface/experience-cloud.html?lang=pt-BR) para Experience Cloud (administração)
* Serviço Places [notas de versão](https://experienceleague.adobe.com/docs/places/using/release-notes.html?lang=pt-BR)
* Documentação do produto para [Pessoas - Atributos do cliente e Biblioteca de público-alvo](https://experienceleague.adobe.com/docs/core-services/interface/services/core-services-landing.html?lang=en)

## ![Ícone](/assets/experience_platform_appicon_24.png) Adobe Experience Platform {#platform}

Informações da versão mais recente e nova documentação do Experience Platform e [!UICONTROL SDK móvel]:

Data de lançamento: **26 de janeiro de 2022**

* [Notas de versão da Experience Platform](https://experienceleague.adobe.com/docs/experience-platform/release-notes/latest.html?lang=pt-BR)

### Novos tutoriais e cursos da Experience Platform {#tutorials-platform}

Novos vídeos, tutoriais ou cursos publicados para a Experience Platform.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Fevereiro de 2022 | [Implementar a Adobe Experience Cloud com o SDK da Web](https://experienceleague.adobe.com/docs/platform-learn/implement-web-sdk/overview.html) | Tutorial de várias páginas | Saiba como implementar aplicativos Experience Cloud usando o SDK da Web da Adobe Experience Platform. Este tutorial mostra como implementar o SDK da Web da plataforma usando um site de varejo de exemplo chamado _Luma_. O [Luma](https://luma.enablementadobe.com/content/luma/us/en.html) O site tem uma camada de dados avançada e uma funcionalidade que permite criar uma implementação realista. Comece já! |
| Fevereiro de 2022 | [Personalização de próxima ocorrência com a CDP em tempo real e a Adobe Target](https://experienceleague.adobe.com/docs/platform-learn/tutorials/experience-cloud/next-hit-personalization.html) | Vídeo | Saiba como personalizar na próxima ocorrência com [!UICONTROL Real-time Customer Data Platform] e Adobe Target. O destino do Adobe Target na CDP em tempo real permite usar segmentos do Experience Platform no Adobe Target para personalização de mesma página e próxima página com suporte de governança e privacidade. |

{style=&quot;table-layout:auto&quot;}

### SDK do Adobe Mobile

Consulte [Notas de versão e logs de alteração](https://aep-sdks.gitbook.io/docs/release-notes) dos SDKs móveis da Adobe Experience Platform.

## ![Ícone](/assets/analytics.png) [!DNL Adobe Analytics] {#analytics}

Data de lançamento: **16 de fevereiro de 2022**

* Adobe Analytics [notas de versão](https://experienceleague.adobe.com/docs/analytics/release-notes/latest.html?lang=en) (**nova localização**)
* Adobe Analytics [documentação e tutoriais do produto](https://experienceleague.adobe.com/docs/analytics.html?lang=pt-BR)

### [!DNL Customer Journey Analytics] {#cja}

Data de lançamento: **16 de fevereiro de 2022**

* Customer Journey Analytics [notas de versão](https://experienceleague.adobe.com/docs/analytics-platform/using/releases/latest.html?lang=en)  (**nova localização**)
* Customer Journey Analytics [documentação e tutoriais do produto](https://experienceleague.adobe.com/docs/customer-journey-analytics.html?lang=en)

### AppMeasurement {#appm}

Versão da versão: **2.22.4**

* [AppMeasurement para notas de versão do JavaScript](https://experienceleague.adobe.com/docs/analytics/implementation/appmeasurement-updates.html?lang=en)

### Novos tutoriais e cursos do Analytics {#tutorials-analytics}

Novos vídeos, tutoriais ou cursos publicados para o Adobe Analytics.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Fevereiro de 2022 | [Manipulação de dados de entrada com regras de processamento](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/manipulating-incoming-data-with-processing-rules.html?lang=pt-BR) | Vídeo | Obtenha uma visão geral das Regras de processamento no Adobe Analytics e saiba para que são usadas. Aprenda algumas dicas, exemplos e até mesmo um aviso. |
| Fevereiro de 2022 | [Configuração das variáveis da lista](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configuring-list-variables.html?lang=pt-BR) | Vídeo | Quando você deve colocar mais de um valor em um eVar (uma variável de conversão) de uma vez, o que você fará? Liste variáveis para o resgate! Saiba como e o porquê você configura e usa variáveis de lista no Adobe Analytics. |
| Fevereiro de 2022 | [Configurar classificações de tráfego](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-traffic-classifications.html?lang=en) | Vídeo | Saiba como configurar classificações para variáveis de tráfego, geralmente chamadas de _props_ e também para _pagename_ e assim por diante. |
| Fevereiro de 2022 | [Configurar classificações de conversão](https://experienceleague.adobe.com/docs/analytics-learn/tutorials/administration/manage-report-suites/configure-conversion-classifications.html?lang=en) | Vídeo | Saiba mais sobre como configurar classificações para variáveis de conversão, também conhecidas como _eVars_. Essa configuração também se aplica a produtos e variáveis de lista. |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/audience-manager.png) Audience Manager {#aam}

Correções e aprimoramentos no Audience Manager.

* Solução de um problema que fazia com que todas as chamadas de API retornassem um erro `Undocumented`, quando realizadas pela interface do Swagger. (AAM-59190)
* Solução de um problema que fazia com que funções de usuário incorretas fossem atribuídas a parceiros em algumas situações. (AAM-59451)
* Solução de um problema que fazia com que a API exigisse cabeçalhos de autenticação que diferenciassem maiúsculas e minúsculas. (AAM-58528)

Para obter recursos de autoajuda, consulte [Documentação e tutoriais do Audience Manager](https://experienceleague.adobe.com/docs/audience-manager.html?lang=en) no Experience League

## ![Ícone](/assets/aem.png) Adobe Experience Manager {#aem}

A Adobe recomenda visitar a página de [Atualizações e roteiros de versão do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/home.html?lang=pt-BR) para se manter atualizado sobre as informações de lançamento.

### Versões de produto do Experience Manager

* **Experience Manager as a Cloud Service**

   Observe a [Vídeo Visão geral da versão de janeiro de 2022](https://video.tv.adobe.com/v/340120) para obter um resumo dos recursos adicionados na versão 2022.1.0 (janeiro de 2022).

   * Vídeo de [](https://video.tv.adobe.com/v/339278)Visão geral dos novos recursos da versão de dezembro de 2021.
   * [Vídeo Visão geral dos novos recursos da versão de outubro de 2021](https://video.tv.adobe.com/v/338253).
   * [Vídeo Visão geral dos novos recursos da versão de setembro de 2021](https://video.tv.adobe.com/v/337381).

   * **Experience Manager Assets as a Cloud Service**

      _Novos recursos no Experience Manager Assets_

      * Dynamic Media - Agora você pode usar a interface Experience Manager - Dynamic Media para configurar [Configurações gerais](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-general-settings.html) e [Configuração de publicação](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-publish-settings.html) em vez de ter que passar pelo aplicativo de desktop do Dynamic Media Classic.
      * O Dynamic Media agora é compatível com assimilação, visualização, reprodução e publicação de vídeos MXF. A anotação e o vídeo que pode ser comprado para vídeos MXF ainda não são compatíveis.
      * Após configurar uma conexão entre implantações remotas de Sites e DAM, os ativos no DAM remoto são disponibilizados na implantação do Sites. Agora você pode [atualizar, excluir, renomear e mover operações](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/admin/use-assets-across-connected-assets-instances.html?lang=pt-BR) em ativos ou pastas remotos do DAM. As atualizações, com algum atraso, estão disponíveis automaticamente na implantação dos Sites.

      _Novo recurso no canal de pré-lançamento do Experience Manager Assets_

      * O Dynamic Media agora oferece a flexibilidade para permitir [configurar uma conta de alias de empresa](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-alias-account.html?lang=en) na interface do usuário, para que os URLs do Dynamic Media e o código de inserção do visualizador sejam atualizados. Essa ação afeta positivamente a SEO, para refletir as atualizações feitas no contexto de negócios, como a reformulação da marca.
      * Agora é possível usar a interface do usuário do Experience Manager Assets para:

         * Configurar a detecção de ativos duplicados em um repositório.
         * Configure a adição de marcas d&#39;água digitais a imagens.
      * Agora, os administradores podem configurar o serviço de email para downloads grandes. Permite que os usuários [ativar notificações por email para downloads grandes](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/download-assets-from-aem.html?lang=en#enable-email-notifications-for-large-downloads) na interface do Experience Manager Assets. O usuário recebe uma notificação por email contendo o link de download do arquivo ZIP após concluir o processo de download.
      * O recurso [Gerenciar publicação](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en) está aprimorado, com uma interface de usuário melhorada. Os usuários podem publicar ou cancelar a publicação de conteúdo de e para o destino selecionado, e [Adicionar conteúdo](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#add-content) para a lista de publicação em todo o repositório DAM. Eles também podem [Incluir configurações de pasta](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#include-folder-settings) para publicar o conteúdo das pastas selecionadas e aplicar filtros, e [agendar publicação](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/assets/manage/manage-publication.html?lang=en#publish-assets-later) para uma data ou hora posterior.

      _Correção de erros_

      * Os ativos não processados sem representação original são enviados ao Asset compute para processamento ao migrar ativos do Experience Manager no local para o Cloud Services.
   * **Experience Manager Forms as a Cloud Service**

      _Novo no Forms_

      * **Experience Manager Forms as a Cloud Service - Comunicações** — [APIs de comunicação](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/forms/using-communications/aem-forms-cloud-service-communications.html?lang=pt-BR) ajuda a combinar um modelo e dados XML para gerar documentos de impressão em vários formatos. O serviço permite gerar documentos em modos síncronos e em lote. As APIs ajudam a criar aplicativos que permitem fazer o seguinte:

         * Gerar documentos preenchendo arquivos de modelo com dados XML.
         * Gerar formulários em vários formatos, incluindo fluxos de impressão de PDF não interativos.
         * Gerar PDFs de impressão a partir de PDFs de formulário XFA.
         * Gerar documentos PDF, PostScript, PCL e ZPL em massa ao mesclar vários conjuntos de dados com modelos de origem.
      * **Fontes personalizadas para documentos de Documento de registro e PDF criados com APIs de comunicações** — Agora é possível usar fontes aprovadas pela marca em documentos PDF gerados usando APIs de comunicações para alinhar-se aos requisitos organizacionais.

      _Novo no canal de pré-lançamento do Forms_

      * [API do Assembler](https://developer.adobe.com/experience-manager-forms-cloud-service-developer-reference/references/assembler-sync/) — Assembler APIs para combinar, reorganizar, aumentar e obter informações sobre documentos PDF.
   * **Cloud Manager**

      _Data de lançamento_

      A data de lançamento do Cloud Manager no Experience Manager as a Cloud Service 2022.01.0 é 20 de janeiro de 2022.
A próxima versão está planejada para 10 de fevereiro de 2022.

      _Novos recursos_

      * Cloud Manager [evita reconstruir a base de código quando detecta que a mesma confirmação de git é usada](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/implementing/using-cloud-manager/create-application-project/setting-up-project.html?lang=en#build-artifact-reuse) em várias execuções de pipeline de pilha completa.
      * Agora, para acessar o log de ambiente do Experience Manager, é necessário **[!UICONTROL Gerenciador de implantação]** perfil do produto. Os usuários sem esse perfil veem um botão desativado na interface do usuário.
      * A interface do usuário não permite a configuração de pipeline de front-end para um programa em que o Sites não está habilitado como uma solução.
      * Após gerar uma senha git, a data de expiração é exibida.








### Comunidade

* **Webinar de GEMs do Experience Manager: _Crie sites com mais rapidez com o Experience Manager Headless e o App Builder_**

   **Data**: quarta-feira, 23 de março de 2022
   **Hora**: 8:00 A.M. (PST) ou 5:00 (CET) ou 9:00 (IST)
   **Alto-falante**: Duy Nguyen, Engenheiro de Desenvolvimento de Software Adobe
   [Registre-se no webinário em https://adobe.ly/3oCkEsh](https://adobe.ly/3oCkEsh)
   [Perguntas frequentes sobre o webinário](https://adobe.ly/3LkSWdm)

* Reproduza o Webinar de GEMs do Experience Manager de janeiro de 2022: [_Revisão de 2021 do Experience Manager as a Cloud Service e perspectivas de 2022_](https://adobe.ly/3rqbSOz)

### Novos cursos e tutoriais do Experience Manager {#tutorials-aem}

Novos vídeos, tutoriais e cursos publicados no mês passado.

| Publicado | Nome | Tipo | Descrição | Aplicativo |
| ------| ------| ----- | -----| ----|
| Fevereiro de 2022 | [Criar Credenciais de Serviço](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/service-credentials.html) | Vídeo | Saiba como criar credenciais de serviço para garantir a autenticação segura para suas integrações com AEM as a Cloud Service. | AEM Forms CS |
| Fevereiro de 2022 | [Criar um JSON Web Token (JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) | Artigo | Saiba mais sobre JSON Web Tokens, um método RFC 7519 aberto e padrão do setor para representar reclamações com segurança entre duas partes. `JWT.io` As bibliotecas são usadas nesta amostra para gerar o JWT. | AEM Forms CS |
| Fevereiro de 2022 | [Exchange JWT para Token de Acesso](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-access-token.html) | Artigo | O JWT criado na [Criar um JSON Web Token (JWT)](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/create-jwt.html) Essa etapa é trocada por APIs do Adobe IMS para um Token de acesso, que pode ser usado para acessar AEM as a Cloud Service. Saiba mais sobre como solicitar um Token de acesso para enviar uma solicitação de POST contendo JWT, client_id, client_secret para o serviço de autenticação IMS. | AEM Forms CS |
| Fevereiro de 2022 | [Como incorporar fontes no pdf gerado](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/intellij-set-up.html?lang=en#add-the-fonts-module) | Artigo | Saiba como instalar [!DNL IntelliJ] edição da comunidade. | AEM Forms CS |
| Fevereiro de 2022 | [Efetuar a chamada de POST](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/doc-gen-formscs/merge-data-with-template.html) | Vídeo | Saiba como fazer uma chamada HTTP POST para o endpoint com os parâmetros necessários. O modelo e os arquivos de dados são fornecidos como arquivos de recurso. | Forms CS |
| Fevereiro de 2022 | [Migração do arquétipo de AEM antigo](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/developing-for-cloud-service/updating-project-archetype.html?lang=en) | Vídeo | Desc. | Forms CS |
| Fevereiro de 2022 | [Externalizar o armazenamento de dados do workflow no AEM Forms CS](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/forms/create-aem-workflow/externalize-workflow.html?lang=en) | Vídeo | Saiba como armazenar seus dados de workflow no armazenamento do Azure. O AEM Forms CS tem novo recurso de armazenar seus dados de fluxo de trabalho, como variáveis, anexos e assim por diante, em uma conta de armazenamento externa. | AEM Forms CS |
| Fevereiro de 2022 | [Integrar o Adobe Analytics com a automação de configuração do Experience Cloud](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/sites/integrations/adobe-analytics-exc-setup-automation.html) | Vídeo | Saiba como a Experience Cloud Setup Automation fornece uma maneira simples e automatizada de integrar e instrumentar o Experience Manager Sites com o Experience Platform Launch e o Adobe Analytics. | AEM Sites |
| Fevereiro de 2022 | [Recomendações do produto](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/content-and-commerce/storefront/authoring/product-recommendations.html) | Vídeo | Saiba como inserir dinamicamente essas recomendações de produto em uma loja da Adobe Experience Manager (AEM). O Adobe Commerce tem um mecanismo de recomendação desenvolvido pela Adobe Sensei. | AEM e Adobe Commerce |

{style=&quot;table-layout:auto&quot;}

### Informações sobre a versão do Experience Manager

Todas as notas de versão do Experience Manager são mantidas nas seguintes páginas:

* [Informações sobre a versão do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/release-notes/home.html?lang=pt-BR)
* [Notas de versão do Experience Manager Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/release-notes/release-notes-current.html?lang=pt-BR)
* [Notas de versão do Serviço de conversão automatizada de formulários](https://experienceleague.adobe.com/docs/aem-forms-automated-conversion-service/using/release-notes.html?lang=pt-BR)
* [Notas de versão do Service Pack do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/release-notes/release-notes.html?lang=pt-BR)
* [Notas de versão do Cumulative Fix Pack do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64/release-notes/cfp-release-notes.html?lang=pt-BR)
* [Notas de versão do Experience Manager Assets Dynamic Media](https://experienceleague.adobe.com/docs/dynamic-media-developer-resources/release-notes/s7rn2017.html?lang=pt-BR)
* [Notas de versão do Experience Manager Brand Portal](https://experienceleague.adobe.com/docs/experience-manager-brand-portal/using/introduction/brand-portal-release-notes.html?lang=pt-BR)
* [Notas de versão do aplicativo para desktop Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-desktop-app/using/release-notes.html?lang=pt-BR)
* [Notas de versão do Experience Manager Dispatcher](https://experienceleague.adobe.com/docs/experience-manager-dispatcher/using/getting-started/release-notes.html?lang=pt-BR)
* [Notas de versão do Adobe Primetime](https://experienceleague.adobe.com/docs/primetime/release-notes/home.html?lang=pt-BR)
* [Notas de versão do Livefyre](https://experienceleague.adobe.com/docs/livefyre/using/release-notes/c-rn.html?lang=pt-BR)

### Outros recursos de Ajuda do Experience Manager

* [Guias do Experience Manager as a Cloud Service](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/content/home.html?lang=pt-BR)
* [Guia do Usuário do Cloud Manager](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.5](https://experienceleague.adobe.com/docs/experience-manager-65/deploying/home.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.4](https://experienceleague.adobe.com/docs/experience-manager-64.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.3](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=pt-BR)
* [Página de aprendizagem e suporte do Experience Manager 6.2](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=pt-BR#previous-updates)
* [Versões anteriores da documentação do Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/previous-updates/aem-previous-versions.html?lang=en#previous-updates)
* [Página inicial de ajuda do Dynamic Media Classic](https://experienceleague.adobe.com/docs/dynamic-media-classic/using/home.html?lang=pt-BR)
* [Documentação do Experience Manager: atualizações recentes](https://experienceleague.adobe.com/docs/experience-manager-release-information/aem-release-updates/doc-updates/documentation-updates.html?lang=pt-BR#aem-as-a-cloud-service)

## ![Ícone](/assets/ec_appicon_24.png) Documentação XML do Adobe Experience Manager {#xml-doc}

A Documentação XML do Adobe Experience Manager é um aplicativo implantado no AEM. É uma poderosa solução de gerenciamento de conteúdo de componentes (CCMS) de nível empresarial que permite o suporte ao DITA nativo no Adobe Experience Manager, permitindo que o AEM lide com a criação e a entrega de conteúdo baseado em DITA.

Saiba mais sobre [Documentação XML para AEM](https://www.adobe.com/br/products/xml-documentation-for-experience-manager/features.html).

### Novos tutoriais da Documentação XML do Adobe Experience Manager {#tutorials-xml-doc}

Novos vídeos, tutoriais ou cursos publicados da Documentação XML para o Adobe Experience Manager.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Janeiro de 2022 | [Versões da documentação XML](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/tutorials/release-info/latest-release-info.html?lang=pt-BR) | Vídeo | Saiba mais sobre a documentação XML para o Adobe Experience Manager, uma solução poderosa de gerenciamento de conteúdo de componentes corporativos (CCMS). Ela permite o suporte ao DITA nativo no Adobe Experience Manager, permitindo que o AEM lide com a criação e a entrega de conteúdo baseado em DITA. |
| Janeiro de 2022 | [Geração de saída com a documentação XML para o AEM](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/output-generation/overview.html?lang=pt-BR) | Vídeos e artigos | Saiba mais sobre o painel de mapa, relatórios, publicação com linhas de base e condições e muito mais. |

{style=&quot;table-layout:auto&quot;}

### Recursos adicionais

* [Documentação XML do Adobe Experience Manager](https://experienceleague.adobe.com/docs/experience-manager-xml-documentation-learn/videos/overview.html?lang=pt-BR) - tutoriais no Experience League
* [Documentação XML para Aprendizagem e suporte do Adobe Experience Manager](https://helpx.adobe.com/support/xml-documentation-for-experience-manager.html) - documentação do produto

## ![Ícone](/assets/magento.png) [!DNL Adobe Commerce] {#magento}

Consulte os seguintes links para as notas de versão do Adobe Commerce:

* [Adobe Commerce e Magento Open Source](https://devdocs.magento.com/guides/v2.4/release-notes/bk-release-notes.html)
* [Cloud Suite para Adobe Commerce](https://devdocs.magento.com/cloud/release-notes/cloud-tools.html)

### Novos tutoriais do Adobe Commerce {#tutorials-commerce}

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Fevereiro de 2022 | [Atualizar o Adobe Commerce/Magento Open Source](https://experienceleague.adobe.com/docs/commerce-operations/upgrade-guide/overview.html) | Guia do usuário | Obtenha toda a ajuda necessária para prosseguir com o processo de atualização. |
| Fevereiro de 2022 | [Workshop de atualização do Adobe Commerce 2.4](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/upgrade-workshop.html?lang=en) | Vídeo | Saiba mais sobre as etapas e práticas recomendadas a serem seguidas ao se preparar para a próxima atualização para a versão 2.4.4 ou superior. |
| Fevereiro de 2022 | [Usar a ferramenta de compatibilidade de atualização no PhpStorm](https://experienceleague.adobe.com/docs/commerce-learn/tutorials/uct-phpstorm.html?lang=en) | Vídeo | Saiba como usar o `PhpStorm` plugin |

{style=&quot;table-layout:auto&quot;}

## ![Ícone](/assets/target.png) [!DNL Adobe Target] {#target}

Última atualização: **1 de fevereiro de 2022**

* Para obter informações de pré-lançamento, consulte [Pré-lançamento do Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/target-release-notes.html?lang=pt-BR)
* Para obter informações atuais, consulte [Notas de versão do Adobe Target](https://experienceleague.adobe.com/docs/target/using/release-notes/release-notes.html?lang=en)

## ![Ícone](/assets/campaign.png) [!DNL Adobe Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### Últimas versões de produto do Campaign

Saiba mais sobre recursos, melhorias e correções mais recentes lançados:

* (Novo!) [Versão do Campaign Standard 2.1](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html?lang=pt-BR)
* [Campaign v8.2.10](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/release-notes.html?lang=pt-BR)
* [Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html?lang=pt-BR)

### Novos tutoriais e cursos do [!DNL Campaign] {#tutorials-campaign}

Novos vídeos, tutoriais ou cursos publicados para o Adobe Campaign.

| Publicado | Nome | Tipo | Descrição | Versão |
| ------| ----- | -----| ------ | --- |
| Fevereiro de 2022 | [Princípios básicos do gerenciamento de dados com workflows do Adobe Campaign](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/data-management-fundamentals.html?lang=en) | Vídeo | Saiba quais são as dimensões de direcionamento e as tabelas de trabalho, e como o Adobe Campaign gerencia os dados em diferentes fontes de dados. | Campaign v8 |
| Fevereiro de 2022 | [Alterar a fonte de dados](https://experienceleague.adobe.com/docs/campaign-learn/tutorials/data-management/change-data-source.html?lang=en) | Vídeo | Saiba como alterar a fonte de dados de uma tabela de trabalho do workflow usando Alterar atividade da fonte de dados para gerenciar dados de forma flexível em diferentes fontes de dados, como FDA, FDA e banco de dados local. | Campanha v8 |

{style=&quot;table-layout:auto&quot;}

### Recursos de ajuda do Campaign

* Adobe Campaign v8: [Documentação](https://experienceleague.adobe.com/docs/campaign/campaign-v8/campaign-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign/campaign-v8/start/whats-new.html?lang=pt-BR) - [Guias de implementação](https://experienceleague.adobe.com/docs/campaign/campaign-v8/implement/implement.html?lang=pt-BR)
* Adobe Campaign Standard: [Documentação do Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard/using/campaign-standard-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-notes.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/overview.html?lang=pt-BR) - [Planejamento de lançamento](https://experienceleague.adobe.com/docs/campaign-standard/using/release-notes/release-planning.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-standard/using/documentation-updates.html?lang=pt-BR)
* Adobe Campaign Classic: [Documentação do Campaign Classic v7](https://experienceleague.adobe.com/docs/campaign-classic/using/campaign-classic-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/campaign-classic/using/release-notes/latest-release.html) - [Vídeos explicativos](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/overview.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/campaign-classic/using/documentation-updates.html?lang=pt-BR)
* Painel de controle do Adobe Campaign: [Documentação](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/control-panel/using/release-notes.html?lang=pt-BR) - Vídeos explicativos do [Campaign Standard](https://experienceleague.adobe.com/docs/campaign-standard-learn/control-panel/control-panel-overview.html?lang=pt-BR)/[Campaign Classic](https://experienceleague.adobe.com/docs/campaign-classic-learn/control-panel/control-panel-overview.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) Adobe Journey Optimizer {#journey-opt}

Com o Journey Optimizer, você pode gerenciar campanhas omnicanal programadas e momentos particulares para milhões de clientes por meio de um único aplicativo, e toda a jornada é otimizada com decisões e insights inteligentes.

### Versões mais recentes do produto Journey Optimizer

Saiba mais sobre os recursos, melhorias e correções mais recentes nas [Notas de versão do Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html?lang=pt-BR).

### Mais recursos para o [!DNL Journey Optimizer]

* [Documentação do Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/overview.html?lang=pt-BR)
* [Documentação do Gerenciamento de decisões](https://experienceleague.adobe.com/docs/journey-optimizer/using/offer-decisioniong/get-started-decision/starting-offer-decisioning.html) - [Notas de versão](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-optimizer-learn/tutorials/decision-management-configuration/introduction-to-offer-decisioning.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journey-optimizer/using/whats-new/documentation-updates.html?lang=pt-BR)

## ![Ícone](/assets/experience_platform_appicon_24.png) [!DNL Adobe Journey Orchestration] {#journey-orch}

Use o Experience Platform para orquestrar a jornada de um cliente em escala nos canais de experiência, antecipando de forma inteligente as necessidades de cada indivíduo em tempo real.

### Últimas versões de produto do [!DNL Journey Orchestration]

Saiba mais sobre os recursos, melhorias e correções mais recentes nas Notas de versão do [[!DNL Journey Orchestration] ](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html?lang=pt-BR).

#### Mais recursos para o [!DNL Journey Orchestration]

* [Documentação do Journey Orchestration](https://experienceleague.adobe.com/docs/journeys/using/journey-orchestration-home.html?lang=pt-BR) - [Notas de versão](https://experienceleague.adobe.com/docs/journeys/using/release-notes/release-notes.html) - [Tutoriais em vídeo](https://experienceleague.adobe.com/docs/journey-orchestration-learn/tutorials/understanding-journey-orchestration.html?lang=pt-BR) - [Atualizações mais recentes da documentação](https://experienceleague.adobe.com/docs/journeys/using/release-notes/documentation-updates.html?lang=pt-BR)

## ![Ícone](/assets/marketo.png) [!DNL Adobe Marketo Engage] {#marketo}

O [!DNL Marketo Engage] é um aplicativo completo para o gerenciamento de clientes potenciais e para os profissionais de marketing B2B que procuram transformar as experiências dos clientes envolvendo-se em cada estágio de jornadas de compras complexas.

### Atualizações do Core Marketo Engage

Consulte a [!DNL Marketo Engage] [programação de lançamento](https://experienceleague.adobe.com/docs/marketo/using/release-notes/release-schedule.html?lang=pt-BR) para obter as informações mais recentes sobre a programação de lançamento e notas de versão.

## ![Ícone](/assets/workfront.png) [!DNL Adobe Workfront] {#workfront}

O Adobe [!DNL Workfront] é um aplicativo unificado de gerenciamento de trabalho para compartilhar ideias, criar conteúdos, gerenciar processos complexos e fazer o melhor trabalho.

Consulte a página [[!DNL Workfront] lançamentos](https://one.workfront.com/s/product-releases) para obter um resumo das informações mais recentes para todos os produtos.

## ![Ícone](/assets/advertising-cloud.png) Adobe Advertising Cloud {#adcloud}

Notas de versão para [!DNL Adobe Advertising Cloud].

* [Novos recursos através do  [!DNL Advertising Cloud]](#adcloud-all)
* [Novos recursos no  [!DNL Advertising Cloud DSP]](#adcloud-dsp)
* [Novos recursos no  [!DNL Advertising Cloud Search]](#adcloud-search)
* [Novos tutoriais da  [!DNL Advertising Cloud] ](#tutorials-ad-cloud)

### Novos recursos através do [!DNL Advertising Cloud] {#adcloud-all}

Última atualização: **27 de outubro de 2021**

| Recurso | Descrição |
| ------- | ----------- |
| Analytics para o Advertising Cloud | Se sua organização quiser mudar de usar o Adobe Analytics herdado `visitorAPI.js` biblioteca para a biblioteca do Adobe Experience Platform (`alloy.js`) para a coleta de dados, é necessário fazer alterações para ativar a compilação de ID. Consulte [Usar a biblioteca JavaScript de  [!DNL Last Event Service]  com o  [!DNL Web SDK] da Adobe Experience Platform](https://experienceleague.adobe.com/docs/advertising-cloud/integrations/analytics/planning/web-sdk.html?lang=pt-BR). |

{style=&quot;table-layout:auto&quot;}

### Novos recursos no [!DNL Advertising Cloud DSP] {#adcloud-dsp}

Última atualização: **27 de outubro de 2021**

| Recurso | Descrição |
| ------- | ----------- |
| Relatórios personalizados | Agora é possível criar e gerenciar o [!DNL Amazon S3] e diferentes tipos de locais de entrega FTP, chamados de *[!DNL report destinations]*, para seus relatórios personalizados. Depois de configurar os destinos do relatório, é possível configurar cada um dos novos relatórios personalizados para serem entregues a um ou mais locais, dentro de um tipo único de destino, ou para destinatários de e-mail. As atualizações do [!DNL Amazon S3] e das credenciais FTP não interromperão a entrega do relatório.<br><br>Os relatórios existentes ainda serão enviados aos destinatários de e-mail especificados. Para configurar a entrega para um destino de relatório diferente, crie um novo relatório com o novo destino. |
| Visualizações de [!UICONTROL Pacotes], [!UICONTROL Posicionamentos] e [!UICONTROL Anúncios] | Ao visualizar dados de um único dia, os gráficos de tendências agora incluem dados por hora. Mantenha o cursor sobre qualquer ponto para ver os dados daquela hora. |
| [!UICONTROL Posicionamentos] | O posicionamento [!UICONTROL Inspetor] agora inclui uma guia [!UICONTROL Inventário], que mostra todas as ofertas e suas métricas associadas para o posicionamento. Use as informações para fazer ajustes rápidos ou solucionar problemas sem gerar um relatório personalizado. |
| [!UICONTROL Anúncios] | (Usuários com permissão para incluir clock numbers da Clearcast em seus anúncios) O DSP não exibe mais um erro ao usar um clock number anexado a outro anúncio. **Observação:** A prática recomendada é usar um clock number exclusivo para cada anúncio de vídeo. Caso contrário, o editor não aprovará todos os anúncios. |
| [!UICONTROL IDs de oferta] | As configurações da [!UICONTROL ID de oferta] e outros locais na interface do usuário refletem a nova identidade visual da [!DNL Magnite] SSP:<br><ul><li>O SSP [!DNL Tremor] ([!DNL Telaria]) agora é [!DNL Magnite CTV].</li><li>Nas próximas semanas, [!DNL Rubicon] mudará para [!DNL Magnite DV+], onde [!DNL DV+] significa exibição, vídeo e outros formatos como áudio.</li></ul> |
| [!DNL Freewheel] ofertas via programação garantidas | Agora é possível encontrar o status dos anúncios das [!DNL Freewheel] ofertas via programação garantidas a partir da visualização de [!UICONTROL Anúncios]. Anteriormente, só era possível verificar o status a partir da visualização de [!UICONTROL Ofertas]. |

{style=&quot;table-layout:auto&quot;}

### Novos recursos no [!DNL Advertising Cloud Search] {#adcloud-search}

Última atualização: **16 de fevereiro de 2022**

| Recurso | Descrição |
| ------- | ----------- |
| [!UICONTROL Campanhas], [!UICONTROL Bulksheets] | (Versão de 22 de janeiro) ([!DNL Microsoft Advertising accounts]) Agora é possível criar e gerenciar anúncios de pesquisa responsivos (RSAs) na [!UICONTROL Campanhas] > [!UICONTROL Anúncios] exibir e de [!UICONTROL Campanhas] > [!UICONTROL Bulksheets]. |
| [!UICONTROL Bulksheets], [!UICONTROL Centro de notificação] | (Versão de 22 de janeiro) Todas as notificações por email para bulksheets, que o Advertising Cloud Search envia quando uma operação de bulksheet é concluída ou falhou, agora são manipuladas por [!UICONTROL Centro de notificação].<br><br>[!UICONTROL Bulksheets] é um novo tipo de notificação, com suas próprias preferências de notificação, em [!UICONTROL Centro de notificação]. Notificações por email e notificações da Web são ativadas por padrão, mas você pode, opcionalmente, alterar as configurações de notificação.<br><br>O formato e o conteúdo das notificações por email usam o [!UICONTROL Centro de notificação] e inclui um link de download direto para o arquivo de bulksheet ou arquivo de erro associado. |

{style=&quot;table-layout:auto&quot;}

### Novos tutoriais da Advertising Cloud {#tutorials-ad-cloud}

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Janeiro de 2022 | [Tutoriais da Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud-learn/tutorials/dsp/intro.html?lang=pt-BR) | Vídeos | Cinco tutoriais novos em vídeo sobre a Advertising Cloud DSP estão disponíveis. |

## ![Ícone](/assets/document-cloud-24.png) Adobe Document Cloud {#doc-cloud}

Novos vídeos, tutoriais ou cursos publicados na Adobe Document Cloud.

### Novos cursos e tutoriais da Document Cloud {#tutorials-doc-cloud}

Novos vídeos, tutoriais ou cursos publicados na Adobe Document Cloud.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Fevereiro de 2022 | [Trabalhar com campos de formulário](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/workforms.html?lang=en) | Vídeo | Saiba como adicionar vários tipos de campos de formulário, definir propriedades de campo de formulário e adicionar segurança para criar formulários profissionais de alta qualidade. |
| Fevereiro de 2022 | [Optimize PDF para SEO (Otimização do mecanismo de pesquisa)](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/advanced-tasks/optimizeseo.html) | Vídeo | Saiba como otimizar uma PDF para melhorar a descoberta e a classificação do mecanismo de pesquisa na Web. |

{style=&quot;table-layout:auto&quot;}

Para obter ajuda sobre a Document Cloud, consulte:

* [Adobe Acrobat](https://experienceleague.adobe.com/docs/document-cloud-learn/acrobat-learning/overview.html?lang=pt-BR)
* [Adobe Acrobat Sign](https://experienceleague.adobe.com/docs/document-cloud-learn/sign-learning-hub/overview.html?lang=pt-BR)
* [Aprendizagem e suporte da Document Cloud](https://helpx.adobe.com/support/document-cloud.html)

## ![Ícone](/assets/creative-cloud-24.png) Adobe Creative Cloud para corporações {#creative-cloud}

Consulte [Tutoriais da Creative Cloud para corporações](https://experienceleague.adobe.com/docs/creative-cloud-enterprise-learn/cce-learning-hub/overview.html?lang=pt-BR) para obter os tutoriais mais recentes.

## Digital Experience Blueprints - tutoriais {#blueprints}

[Digital Experience Blueprints](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/overview.html?lang=en) são implementações repetíveis que permitem abordar a estratégia e resolver rapidamente os problemas de negócios estabelecidos. Cada Blueprint fornece uma série de artefatos que explicam o problema de negócios de alto valor, arquiteturas, etapas de implementação, considerações técnicas e links para a documentação relevante.

| Publicado | Nome | Tipo | Descrição |
| -----------| ---------- | ---------- | ---------- |
| Fevereiro de 2022 | [Jornadas do cliente](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/overview.html?lang=en) | Vídeo | As Jornadas do cliente abordam a capacidade das marcas de se engajarem e se comunicarem de forma proativa com seus clientes por meio de canais como email, SMS e alertas móveis. |
| Fevereiro de 2022 | [Blueprint do Campaign v7](https://experienceleague.adobe.com/docs/blueprints-learn/architecture/customer-journeys/campaign-v7/campaign-v7.html?lang=en) | Vídeo | O Adobe Campaign v7 é uma ferramenta de campanha criada para canais de marketing tradicionais, como email e mala direta. Ele oferece recursos avançados de ETL e gerenciamento de dados para ajudar a criar e preparar a campanha perfeita. |

{style=&quot;table-layout:auto&quot;}
