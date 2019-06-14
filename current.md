---
title: Notas de versão da Adobe Experience Cloud
description: Notas de versão da Experience Cloud de june 019
doc-type: notas de versão
last-update: junho de 2019
author: mfrei
translation-type: tm+mt
source-git-commit: 3db1b9386db42a9b63a9a313ef80f05f377f1c65

---


# Notas de versão da Adobe Experience Cloud

Novos recursos e correções na Adobe Experience Cloud.

>[!NOTE]
>Assine a [Adobe Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html) para ser notificado por email sobre versões futuras. Você receberá um aviso três a cinco dias úteis antes do lançamento da versão. Novas informações publicadas após o lançamento serão marcadas com a data da publicação.

**Data de lançamento: 13 de junho de 2019**

* [Adobe Experience Platform](#platform)
* [Analytics](#analytics)
* [Audience Manager](#aam)
* [Experience Manager](#aem)
* [! [Campanha DNL](#ac)]
* [Mobile Services](#mobile)
* [Advertising Cloud](#adcloud)
* [Target Standard/Premium 19.6.1](#target)
* [Magento](#magento)
* [Primetime](#primetime)

## Adobe Experience Platform {#platform}

### Notas de versão da Adobe Experience Platform

* See [[!DNL Experience Platform] release notes](https://www.adobe.io/apis/experienceplatform/home/services/release-notes.html#!end-user/markdown/release-notes/release-notes-20190515.md) on Adobe.io for the latest updates to [!DNL Experience Platform].

### [!DNL Experience Platform Launch]

* Consulte [[! Lançamento da plataforma de experiência DNL]](https://docs.adobelaunch.com/) para obter as informações mais recentes.

## Analytics {#analytics}

Novos recursos e correções no Adobe Analytics:

* [Novos recursos e correções no Adobe Analytics](#aa-features)
* [Avisos importantes para administradores do Analytics](#aa-notices)

Para obter a documentação do produto, consulte [Página inicial de ajuda do Analytics](https://marketing.adobe.com/resources/help/en_US/reference/).

### Novos recursos e correções no Adobe Analytics {#aa-features}

| Recurso | Descrição |
| -----------| ---------- |  
| **Segmentação** | Novos modelos de atribuição para dimensões na segmentação:<ul><li>Repetitivo (Padrão): Inclui instâncias + valores persistentes para a dimensão.</li><li>Instância: Inclui instâncias para a dimensão.</li><li>Instância não repetitiva: Inclui instâncias exclusivas (não repetitivas) para a dimensão.</li></ul> [Mais](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segmentation-workflow/seg-build.html) |
| **Segmentação** | New segment operators: **[!UICONTROL Equals Any of]** and **[!UICONTROL Does not Equal Any of]**. [Mais...](https://docs.adobe.com/content/help/en/analytics/components/segmentation/segment-reference/seg-operators.html) |
| **Depurador** | Quando conectado com sua Adobe ID, agora você tem a opção de recuperar ocorrências processadas no depurador da Experience Cloud. As ocorrências pós-processadas são chamadas do servidor após terem passado pelas [!UICONTROL Regras] de processamento e Regras VISTA, permitindo validar [!UICONTROL Regras] de processamento e regras VISTA. **Observação**: Se você estiver usando A 4 T (Complementares aldataid), os dados pós-processamento poderão levar alguns minutos para retornar. |
| **Analysis Workspace:** | Novos filtros prontos para uso na pesquisa do trilho à esquerda. Além do que você verá hoje (Dimensões, Métricas, Aprovado etc.), novos filtros como Métricas calculadas, Atributos do cliente, evars, Props, Vídeo etc. foram adicionados para facilitar a localização dos componentes necessários. |
| **Analysis Workspace** | Adicionamos um aviso à visualização de Fallout que será exibida quando você adicionar um segmento como ponto de contato - determinadas combinações de contêiner de segmento inválidas resultarão em diagramas de fallout inválidos, como <ul><li>Usar um segmento com base em visitantes como um ponto de contato dentro de uma visualização de Fallout de contexto do visitante</li><li>Usar um segmento com base em visitantes como um ponto de contato dentro de uma visualização de Fallout de contexto de visitas</li><li>Usar um segmento com base em visita como um ponto de contato dentro de uma visualização de Fallout de contexto de visitas</li></ul> <br> [Mais...](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/visualizations/fallout/compare-segments-fallout.html) </br> |
| **Melhorias na documentação do Analytics** | A documentação do Analytics foi reorganizada e agora inclui recursos de colaboração que permitem melhorar o conteúdo! Você pode registrar problemas com a documentação e sugerir edições. O conjunto de doc foi movido para um [novo domínio](https://docs.adobe.com/content/help/en/analytics/landing/home.html). Os redirecionamentos devem estar em vigor. |
| **Novo Guia do Usuário das Notas Técnicas** | O guia do usuário [da Tech Notes](https://docs.adobe.com/content/help/en/analytics/technotes/home.html) está disponível agora. Atualmente, é direcionado para ajudar os usuários mais experientes com ferramentas de análise de terceiros, como o Google Analytics, a se familiarizar com o Adobe Analytics. O guia do usuário das notas técnicas será expandido nos próximos meses para incluir conteúdo adicional. |

**Correções da Analysis Workspace**

* Correção de um problema com informações de data localizada em japonês nas [!DNL Analysis Workspace] visualizações. (AN-180114)
* Correção de um problema que ocorria após copiar e colar itens de dimensão. Pesquisas subsequentes no item resultavam em um erro. (AN-177394)
* Corrigido um problema com a opção de edição ausente nos painéis de segmentos nas tabelas de forma livre. (AN-171703)
* Corrigido um problema com **[!UICONTROL o recurso Definir como página]** inicial não funcionando quando compartilhado com um grande conjunto de destinatários. (AN-163922)
* Correção de um problema em que as sequências de caracteres eram cortadas verticalmente nos relatórios em tempo real. (AN-175980)

**Outras correções do Analytics**

* Correção de um problema em que os usuários Administradores não conseguiam ativar **[!UICONTROL Eventos de sucesso]**. (AN-176689)
* Correção de um problema que ocorria ao criar um alerta com a métrica **[!UICONTROL Taxa]** de saída. (AN-177476)

### Avisos importantes para administradores do Analytics {#aa-notices}

| Aviso | Data de adição ou atualização | Descrição |
| -----------| ---------- | ---------- |
| Limites do construtor de regras de classificação | Adição de June de junho de 2019 | Esses limites não são novos, mas foram adicionados à documentação [aqui](https://marketing.adobe.com/resources/help/en_US/reference/classification_rule_builder.html). |
| Limites de novos operadores de segmento | Adição de May 1 de maio de 21 19 | A partir de 18 de julho de 28 19, os operadores de segmento &quot;contém qualquer um de&quot;, &quot;não contém qualquer&quot;, todos &quot;e&quot; não contêm todos os &quot;e&quot; não contêm todos os &quot;serão limitados a 100 palavras por campo de entrada&quot;. O limite será aplicado a todos os segmentos novos e modificados após essa data. Os segmentos existentes que excedem o limite continuarão sendo suportados, mas não poderão ser modificados ou salvos até que o campo de entrada seja reduzido. Esses limites estão sendo aplicados como parte de um esforço contínuo para melhorar o desempenho da consulta. |
| Futuras alterações de suporte das Classificações **[!UICONTROL ativadas por data]** e **[!UICONTROL numéricas 2]** | Atualizado em 28 de maio de 2019 | A capacidade de importar classificações Numérico 2 e Ativadas por data foi removida da base de código. Essa alteração será aplicada na Versão de manutenção de julho de 2019. Se você tiver colunas Numéricas ou Ativadas por data no arquivo de importação, essas células serão ignoradas silenciosamente e todos os outros dados nesse arquivo serão importados normalmente. <br/>As classificações existentes ainda podem ser exportadas por meio do fluxo de trabalho de classificação padrão, e continuarão disponíveis nos relatórios. |
| Futura alteração para cálculos de _Total de relatório_ | Atualizado em 2 de maio de 2019 | Em **13 de junho de 2019**, o Adobe Analytics disponibilizará os cálculos de _Total de relatório_ de maneira consistente em todas as dimensões e métricas. Isso resultará em uma alteração aos totais referentes a alguns relatórios (tipicamente, relatórios de ou de Atributos do cliente). Antes desta alteração, alguns Totais de relatório incluíam ou excluíam de maneira inconsistente o item de linha _Não especificado_ no total, independentemente de _Não especificado_ aparecer no relatório. <br/>A partir de 13 de junho de 2019, _Não especificado_ sempre aparecerá no total do relatório, mesmo se não aparecer como um item de linha no mesmo. Além disso, segmentos que usam a lógica _existe_ ou _não existe_ poderão apresentar resultados diferentes para algumas dimensões após essa mudança. Essa alteração afetará as soluções Analysis Workspace, Reports &amp; Analytics, Ad Hoc Analysis, Report Builder e a API de relatórios. |
| Atualização de downloads em CSV da [!DNL Analysis Workspace] | 10 de abril de 2019 | A partir de 11 de abril de 2019, várias alterações foram feitas a **[!UICONTROL downloads CSV]** (e **[!UICONTROL Copiar para área de transferência]**) da [!DNL Analysis Workspace] para remover a formatação de dados exportados.  <ul><li>O separador de milhares não está mais incluído. Além disso, o separador decimal continuará a ser incluído, e vai aderir ao formato definido em **[!UICONTROL Componentes &gt; Configurações de relatórios &gt; Separador de milhar]**. Observação: valores numéricos que usam uma vírgula como separador decimal continuarão a ser incluídos entre aspas no CSV exportado.</li><li>Nenhum símbolo de moeda será exibido.</li><li>Nenhum símbolo de porcentagem será exibido. As porcentagens estarão em formato decimal. Por exemplo, 75% será representado como 0,75.</li><li>O tempo será exibido em segundos.</li><li>As Tabelas de coorte mostrarão somente valores brutos; as porcentagens serão removidas.</li><li>Se um número for inválido, uma célula vazia será exibida.</li></ul> |
| Alteração futura no comando do depurador da [!DNL Analysis Workspace] | 4 de abril de 2019 | O comando do Console para ativar o depurador da [!DNL Analysis Workspace] será alterado para adobeTools.debug.includeOberonXml em **13 de junho de 2019**. adobe.tools.debug.includeOberonXml parará de funcionar após essa data. |
| Números de versão do navegador em dispositivo móvel | 7 de fevereiro de 2019 | Em 8 de janeiro de 2019, alteramos o nível de truncação para os números de versão do navegador móvel de 2 para 1. A partir dessa data, as versões exibirão somente os dois primeiros níveis (por exemplo, _Firefox 64.0.2_ agora é exibido como _Firefox 64.0_). |
| Término da vida útil da [!DNL Ad Hoc Analysis] | 29 de janeiro de 2019 | Em 6 de agosto de 2018, a Adobe anunciou a intenção de encerrar a vida útil da [!DNL Ad Hoc Analysis]. Uma data para o fim da vida útil será compartilhada assim que estiver disponível.<br/>Para obter mais informações, incluindo quais versões do Java serão compatíveis durante esse período, visite [Discover Workspace](https://adobe.ly/discoverworkspace). |
| Links encurtados de relatórios do Analytics | 14 de janeiro de 2019 | Links encurtados de relatórios do Analytics que não forem visitados em um ano serão excluídos, a partir de quinta-feira, 17 de janeiro de 2019, em uma programação contínua. |
| Fim de suporte para TLS 1.0 | Atualizado em 10 de janeiro de 2019 | Desde 11 de fevereiro de 2019, os relatórios do Adobe Analytics não são mais compatíveis com a criptografia TLS (Transport Layer Security) 1.0. Essa alteração é parte de nossos esforços contínuos para manter os mais altos padrões de segurança e proteger os dados do cliente. Se não conseguir se conectar aos relatórios do Adobe Analytics após 11 de fevereiro de 21 19, você deve atualizar o navegador para a [versão mais recente](https://marketing.adobe.com/resources/help/en_US/sc/user/requirements.html).<br/> Desde 20 de fevereiro de 2019, a coleta de dados do Adobe Analytics não é mais compatível com TLS 1.0. Com essa alteração, a Adobe não mais coletará dados do Analytics de usuários finais com dispositivos ou navegadores da Web antigos não compatíveis com TLS 1.1 ou versão posterior. Não esperamos que isso afete significativamente os dados ou relatórios do cliente. (Se seu site já não for compatível com o TLS 1.0, você não será afetado.) <br/>A partir de 11 de abril de 2019, a API de relatórios do Adobe Analytics não será mais compatível com a criptografia TLS 1.0. Clientes que acessam a API devem verificar se não serão afetados. <ul><li>Os clientes da API que usam o Java 7 com configurações padrão precisarão de [modificações para terem suporte ao TLS 1.2](https://www.java.com/en/configure_crypto.html). (Consulte _Alteração da versão de protocolo TLS padrão para pontos de extremidade do cliente: de TLS 1.0 para TLS 1.2_.) </li><li>Os clientes de API que usam o Java 8 não deverão ser afetados, pois a configuração padrão é TLS 1.2.</li><li> Os clientes da API que usam outras estruturas precisarão entrar em contato com seus fornecedores para obterem detalhes sobre o suporte a TLS 1.2.</li></ul> |
| Feed de dados: post_product_list column - alteração de tamanho | 9 de janeiro de 2019 | Em 7 de fevereiro de 2019, a Adobe estendeu o tamanho da coluna post_product_list de 64 KB para 16 MB. Essa alteração garante que valores de eVars de merchandising adicionados a post_product_list durante o processamento não causassem truncamento de valores de produto e de receita. Se você tiver processos que assimilam valores de post_product_list, certifique-se de que tais processos sejam compatíveis com valores de até 16 MB em comprimeito, caso contrário o valor será truncado em 16 KB para evitar falhas de assimilação de dados. |
| Alterações de gerenciamento que afetam endpoints do [!DNL Analytics Live Stream] inativos | 20 de dezembro de 2018 | A partir de 1 de fevereiro de 2019, os endpoints do [!DNL Live Stream] sem conexões de cliente ativas por 90 poderão ser desabilitados. É possível entrar em contato com o Atendimento ao cliente da [!DNL Live Stream] para saber sobre os endpoints do e, se necessário, reativá-los. Além disso, certifique-se de que os processos do cliente mantenham uma conexão persistente, conforme pretendido pelo design do serviço, e que estejam implementados para reconectar quando a conexão for perdida ou interrompida. |
| Atualizar o Adobe [!DNL Report Builder] devido ao fim do suporte para TLS 1.0 | 7 de setembro de 2018 | Devido ao fim do suporte para TLS 1.0, recomendamos que os usuários do [!DNL Report Builder] baixem a versão v5.6.21 antes de fevereiro de 2019. Depois dessa data, versões anteriores do [!DNL Report Builder] não funcionarão. |

## Audience Manager {#aam}

**Correções, melhorias e desaprovações**

* O Audience Manager agora conta apenas modelos algorítmicos ativos em relação ao limite de uso.
* Solução de um problema que fazia com que o alcance do modelo algorítmico não fosse exibido para características que usassem o modelo correspondente.
* Correção de um problema que fazia com que o conteúdo das pastas características não fosse exibido, e os nomes das pastas continham parantheses e/ou colchetes.
* Correção de um problema que causava a falha da classificação de características ao selecionar apenas um tipo de característica.
* Correção de um problema que fazia com que a árvore de pastas de características fosse reduzida à exibição [!UICONTROL Todas as características] sempre que você criar ou atualizar uma nova subpasta.
* Solução de um problema que fazia com [!DNL VIEW_DATASOURCES] que a permissão fosse necessária ao tentar excluir um parceiro.
* Solução de um problema que fazia com [!UICONTROL que a caixa Pesquisar] na página [!UICONTROL Segmentos] pesquisasse em todas as pastas em vez do selecionado.
* Corrigido um problema que impedia que a tabela [!UICONTROL Excluir características] fosse classificada pelos controles de cabeçalho, ao criar um novo modelo algorítmico.
* Solucionado o problema que fazia com que o Audience Manager travasse ao executar qualquer relatório com datas de intervalo vazias.

## Experience Manager {#aem}

Novos recursos, correções e atualizações no Adobe Experience Manager (AEM). A Adobe recomenda que os clientes com implantações locais implantem os patches mais recentes como um modo de assegurar estabilidade, segurança e desempenho superiores.

### Versões do produto

**Cloud Manager 2019.5.0**

A versão mais recente do Experience Cloud Manager (2019.5.0) não contém alterações funcionais significativas, embora ofereça algumas correções de erros.

* [Notas de versão do Cloud Manager 2019.5.0](https://docs.adobe.com/content/help/en/experience-manager-cloud-manager/using/release-notes/release-notes-current.html)

**Documentação XML do AEM**

A versão 3.3 da solução Documentação XML agora está disponível. Consulte as seguintes notas de versão:

***Recursos do mapa avançado***
* Adicione referências de tópico usando arrastar e soltar da exibição de repositório ou usando a barra horizontal e o catálogo de elementos.
* Adicione metadados em um tópico ref, chunk, como título de navegação, formato, escopo e assim por diante.
* Clicar no tópico ref deve abrir o tópico no editor (o modo de visualização se não for retirado e desativar a edição com o check-checkout ativado).
* Adicionar cabeçalho de tópico e grupo de tópico.
* Adicione bookmaps com o Fronttópico (Tópicos, Prefácio, lista de livros, avisos etc.) e a Backeding (Tópicos, Apênfens, Glossário e assim por diante).
* No modo Autor, os links quebrados são realçados, as navegações estruturais são exibidas e a Exibição de tags completas está disponível.
* Capacidade de definir atributos de nível de mapa.
* Capacidade de definir Título/booktitle.
* Suporte para recargas com a capacidade de adicionar cabeçalho rel, colunas, arrastar/soltar tópicos do mapa e repositório para a tabela rel, definir links, escopo e outros parâmetros para os links, reordenar links dentro da célula.
* Widget de barra de ferramentas para inserir antes, inserir depois e inserir elemento.
* Realce se uma condição for aplicada em um tópico.
* Capacidade de editar vários mapas por vez (cada mapa é aberto como uma guia no mesmo navegador).
* No painel do mapa e na exibição de repositório, ao passar o mouse - mostre o título completo do tópico e o nome do arquivo.

***Exibição completa de tags***

* Insira novas tags entre dois elementos.
* Copie e cole tags.
* Arrastar e soltar tags em posições permitidas e não permitidas dentro de um arquivo.
* Expandir e recolher tags.

***Aprimoramentos de pesquisa específicos de DITA***

* Uma ferramenta de serialização foi fornecida para reindexar o conteúdo selecionado
* Os usuários podem usar `contains` e `exact match` em sua pesquisa. Eles também podem pesquisar usando os seguintes parâmetros. :
   * Metadados do ativo. Por exemplo, `file name`ou `title`qualquer metadado personalizado definido pelo cliente.
   * Nome do atributo DITA e seu valor. Por exemplo, `platform=winOS`.
   * Nome do elemento DITA e seu valor. Por exemplo, `author = Joe Smith`.
   * Nome do elemento DITA e seu atributo aplicado. Por exemplo, tabela com o nome do atributo/nome do atributo do spacebase aplicado a ele.
   * Tópico DITA e metadados do mapa.
   * Tipo de informações DITA. Para exame [ple, map, tópico, conceito e assim por diante.
   * Caminho da pasta raiz onde o ativo está localizado.
   * Estado do documento.
   * Status retirado.
   * Intervalo de datas modificado.
   * Tags do CQ.
* É possível criar consultas complexas combinando um ou mais parâmetros de pesquisa acima.

***Revisar alterações do recurso***

* Dicas para um revisor:
   * Importe todos os comentários e incorpore as alterações para revisões em andamento antes de atualizar para a compilação 3.3.
   * Certifique-se de que várias guias não estejam abertas para o editor.
   * Certifique-se de que a exibição Tags completas não esteja ativada.
   * Não alterne entre o modo Autor e o modo de Origem enquanto a revisão estiver em andamento.
* Capacidade de especificar a versão do meu conteúdo que deve ser analisada.
* Capacidade de escolher as versões dos tópicos selecionados com base em uma linha de base, data, rótulo ou versão ativa no momento, ou especificar as versões para cada um dos tópicos ao criar uma revisão.
* Capacidade de enviar o mesmo tópico/mapa para revisão várias vezes e o autor pode acessar todas as revisões no painel de revisão do editor.
* Como iniciador, capacidade de mover uma versão posterior do conteúdo para os revisores. Os revisores receberão uma notificação quando um novo conteúdo for solicitado para revisão.
* Como autor, o usuário poderá visualizar os comentários de revisão para todas as versões de seu conteúdo no painel de revisão do editor. Os autores poderão filtrar os comentários por número de versão.
* Como um usuário do autor terá a capacidade de exibir e importar comentários em uma versão mais antiga do conteúdo no editor, que estava sob revisão.

***Diversos***

* Crie uma nova pasta, tópico ou mapa na exibição Repositório.
* Exibir na interface do usuário Ativos - adicione uma opção de menu para pastas e tópicos - «Exibir na interface do usuário ativos». Essa opção abre a interface de usuário Ativos na qual o usuário pode visualizar a árvore de conteúdo à esquerda e todos os arquivos na exibição de Lista à direita com todos os menus de ativos na parte superior.
* Um painel de revisão agora está disponível como um Bloco no projeto DITA que acompanha a revisão em um Nível de revisualizador e em um Nível de tarefa de revisão.
* Adição da capacidade de converter IDML para DITA.
* Forneça a API para aplicar determinada etiqueta em todas as versões especificadas em uma linha de base.
* Ative um evento depois que a conversão de XHTML/DOCX para DITA estiver concluída. É possível usar esse evento para adicionar atributos especializados ao conteúdo convertido, ou para qualquer outra lógica personalizada que você precise implementar.
* Melhorias na guia de desempenho da linha de base. Primeiro, o usuário precisa executar um script em todas as linhas de base existentes.
* Foram feitos aprimoramentos no XHTML à conversão DITA.
* DITA-OT Offlutuading for Publishing Optimization.
* Correção da classificação na coluna Tipo na exibição de Lista.
* Capacidade de lidar com estilos em cascata no Word para conversão DITA.

### Comunidade

**[Série de webinars do Experience Manager Manager Skills Builder](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)**

Interessado em saber como o devops processa as atividades diárias para o gerenciamento do Adobe Experience Manager na nuvem? O Cloud Manager fornece a primeira geração de funcionalidades nativas para o Adobe Experience Manager que permite a agilidade da nuvem, se a sua organização está iniciando a transformação devops ou procura estratégias para aumentar os processos existentes do devops.

[Nesta série](https://cloudmanagerskillbuilder.experienceleague.adobeevents.com/)mensal, você pode aprender diretamente da equipe de produtos da Adobe sobre como começar a usar os recursos do Experience Cloud Manager para simplificar o gerenciamento do Adobe Experience Manager na nuvem.

Você aprenderá o seguinte:
* Como começar a usar o Gerenciador de nuvem e configurar o CI/CD Pipeline
* Como funcionam os trabalhos de fornecimento automático de serviço e entrega de serviço e pode simplificar o gerenciamento de ambiente do Adobe Experience Manager na nuvem
* Como usar a API do Experience Cloud Manager e integrar os processos existentes do devops

### Recursos adicionais

* [Página inicial de Aprendizagem e suporte do AEM 6.5](https://helpx.adobe.com/support/experience-manager/6-5.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.4](https://helpx.adobe.com/support/experience-manager/6-4.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.3](https://helpx.adobe.com/support/experience-manager/6-3.html)
* [Página inicial de Aprendizagem e suporte do AEM 6.2](https://helpx.adobe.com/support/experience-manager/6-2.html)
* [Guia do Usuário do Cloud Manager](https://helpx.adobe.com/experience-manager/cloud-manager/user-guide.html)
* [Versões anteriores da documentação do AEM](https://helpx.adobe.com/experience-manager/aem-previous-versions.html)
* [Notas de versão do Scene7 Publishing System](https://marketing.adobe.com/resources/help/en_US/s7/release_notes/index.html)
* [Notas de versão do Livefyre](https://marketing.adobe.com/resources/help/en_US/livefyre/c_rn.html)

## [!DNL Campaign] {#ac}

O Adobe Campaign oferece uma maneira intuitiva e automatizada de enviar mensagens individuais por canais de marketing online e offline. Agora, é possível prever o que seus clientes desejam usando as experiências determinadas por seus hábitos e preferências.

### [!DNL Campaign Classic] Versão de primavera de 19.1

| Recurso | Descrição |
| ------------- | ----------- |
| Painel de controle | Para aumentar a eficiência do trabalho como usuário administrador, gerencie configurações de servidores SFTP monitorando armazenamento, endereços IP de lista de permissões e instalando chaves SSH para cada instância. Observe que o Painel de controle está disponível somente para clientes hospedados no AWS a partir de hoje. [Faça logon pela Experience Cloud](https://experiencecloud.adobe.com/campaign/controlpanel/). <br> Para obter mais informações, consulte a documentação [detalhada](https://helpx.adobe.com/campaign/kb/control-panel.html) e o vídeo [passo](https://helpx.adobe.com/campaign/kt/acc/using/acc-control-panel-video-use.html)a passo. |
| Trilha de auditoria | Como administrador, aumente a produtividade monitorando e gerenciando alterações feitas na instância do Adobe Campaign Classic. A Trilha de auditoria registrará ações feitas no Esquema de origem, Fluxo de trabalho e Opção. Você pode ver rapidamente se um elemento foi criado, modificado ou excluído.<br>Para obter mais informações, consulte a documentação [detalhada](https://docs.campaign.adobe.com/doc/AC/en/PRO_Production_procedures_Audit_trail.html) e o vídeo [passo](https://helpx.adobe.com/campaign/kt/acc/using/acc-audit-trail-feature-video-use.html)a passo. |
| Guardrail, Solidez e escalonabilidade | Uma série de melhorias foi adicionada [!DNL Campaign Classic]. Os aprimoramentos de Guardrail, solidez e escalonabilidade estão listados nas [Notas de versão do Adobe Campaign Classic](https://docs.campaign.adobe.com/doc/AC/en/RN.html). |
| Mensagens SMS seguras (TLS) | O SMS protegido agora é suportado por meio do Conector SMPP genérico estendido. Isso permite uma conexão criptografada com o provedor. <br>[ Para obter mais informações, consulte a documentação detalhada](https://helpx.adobe.com/campaign/kb/sms-connector-protocol-and-settings.html). |
| Atualização da matriz de compatibilidade | Com esta nova versão, o Adobe Campaign agora oferece suporte aos seguintes sistemas de banco de dados. Consulte a [Matriz de compatibilidade](https://helpx.adobe.com/campaign/kb/compatibility-matrix.html) <ul><li>Oracle 18 c</li><li>Mysql 5.7 (FDA)</li><li>SQL Server 2017</li><li>Teradata 16 (FDA)</li><li>Postgresql 11</li></ul> |

Consulte [Notas de versão do] Adobe Campaign Classic] (http://docs.campaign.adobe.com/doc/AC/en/RN.html) para obter correções e melhorias.

### [!DNL Campaign Standard] Versão de primavera de 19.2

| Recurso | Descrição |
| ------------- | ----------- |
| Painel de controle | Para ajudar a aumentar a eficiência do seu trabalho como usuário administrador, você pode monitorar facilmente a capacidade e gerenciar as configurações de suas instâncias (começando pelo gerenciamento de servidores SFTP). <br> Para obter mais informações, consulte a documentação [detalhada](https://helpx.adobe.com/campaign/kb/control-panel.html) e o vídeo [passo](https://helpx.adobe.com/campaign/kt/acs/using/acs-control-panel-video-use.html)a passo. |
| Notificações locais | As mensagens de notificação local permitem informar os usuários quando os novos dados tornam-se disponíveis em seus aplicativos móveis, mesmo sem ter acesso à Internet ou ao aplicativo móvel em execução em primeiro plano. As notificações locais são acionadas por um aplicativo móvel em um determinado momento e dependendo de um evento.<br>[Para obter mais informações, consulte a documentação detalhada](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type). |
| Aprimoramento de fluxo de trabalho - Adicionar uma carga à atividade de sinal externo | Inicie um fluxo de trabalho com uma carga quando as condições definidas forem cumpridas com êxito de outro fluxo de trabalho ou uma chamada REST API para integrar com seus sistemas externos. Isso também inclui uma nova atividade de teste, na qual é possível executar testes nesta funcionalidade. <br>Para obter mais informações, consulte a documentação [detalhada](https://helpx.adobe.com/campaign/standard/channels/using/customizing-an-in-app-message.html#customizing-a-local-notification-message-type) e o vídeo [passo](https://helpx.adobe.com/campaign/kt/acs/using/acs-external-signal-activity-feature-video-use.html)a passo. |
| Aprimoramento de páginas de aterrissagem - recaptcha do Google | Aproveite o Google recaptcha para evitar spam em suas páginas de aterrissagem sem nenhuma ação de seus clientes. <br>[Para obter mais informações, consulte a documentação detalhada](https://helpx.adobe.com/campaign/standard/channels/using/designing-a-landing-page.html#setting-google-recaptcha). |

Para obter a documentação do produto, consulte:

* Adobe Campaign Standard: [Documentação](https://helpx.adobe.com/support/campaign/standard.html) - [ Notas de versão](https://helpx.adobe.com/campaign/standard/rn/using/release-notes.html) - [ Vídeos em destaque](https://helpx.adobe.com/campaign/kt/acs/index/acs-videos.html)
* Adobe Campaign Classic: [Documentação](https://helpx.adobe.com/support/campaign/classic.html) - [Notas de versão](https://docs.campaign.adobe.com/doc/AC/en/RN.html) - [Vídeos em destaque](https://helpx.adobe.com/campaign/kt/acc/index/acc-videos.html)

## Mobile Services {#mobile}

* O TLS 1.0 foi desativado em todos os servidores da Adobe. Para dispositivos Android 4. x para se conectar aos serviços da Adobe por meio do SSL, o SDK agora forçará TLS 1.1/TLS 1.2 ao estabelecer um handshake.

## Advertising Cloud {#adcloud}

Última atualização: 5 de junho de 2019, para a versão de 8 de junho

| Produto | Recurso | Descrição |
| -----------| ---------- | ----------  |
| Campanhas de pesquisa, classificações de etiquetas e restrições | Atalhos de teclado | Agora você pode usar <b>Shift + clique</b> para selecionar várias linhas consecutivas e <b>Ctrl + clique</b> para selecionar várias linhas não consecutivas. |
|  | Selecionar todos vs. Selecionar todos na página | Nas tabelas de dados, quando você seleciona a caixa de seleção superior para selecionar todas as linhas, o novo padrão é selecionar todas as linhas na página (se você estiver visualizando 25 linhas, 50 linhas, 100 linhas, 200 linhas ou Rolagem contínua). Ainda há uma opção para selecionar todas as linhas disponíveis. |
| Exibições padrão, visualizações personalizadas e configurações de personalização de coluna independentes | Reorganização de coluna | Os botões Novo e Para baixo permitem reordenar colunas. Você ainda pode arrastar e soltar colunas para reordená-las, como anteriormente. |

## Target Standard/Premium 19.6.1 (25 de junho de 2019) {#target}

Consulte as Notas de versão do Adobe Target para obter as informações da versão mais recente:

[Notas de versão do Target (pré-lançamento)](https://docs.adobe.com/content/help/en/target/using/release-notes/target-release-notes.html)

[Notas de versão do Target (atual)](https://docs.adobe.com/content/help/en/target/using/release-notes/release-notes.html)

## Magento {#magento}

O Magento é uma plataforma de e-commerce que fornece a vendedores online um sistema de carrinho de compras flexível e controle sobre a aparência, o conteúdo e a funcionalidade da loja online. O Magento está disponível em uma versão de código aberto e uma versão de comércio fuller-featured.

O Magento Commerce faz parte da Adobe Commerce Cloud e oferece uma solução de eCommerce com potência empresarial, escalabilidade ilimitada e flexibilidade de código aberto para experiências B2C e B2B.

Notas de versão para as edições de Open Source e Commerce podem ser encontradas na página [Informações](https://devdocs.magento.com/guides/v2.3/release-notes/bk-release-notes.html) da versão.

## Primetime {#primetime}

O Adobe Primetime é uma plataforma de TV multitelas, que ajuda empresas de mídia a criarem e monetizarem experiências de visualização personalizadas e atraentes.

[Notas de versão do Primetime](http://help.adobe.com/en_US/primetime/release_notes/index.html)
[Página inicial de ajuda do Primetime](http://help.adobe.com/en_US/primetime/)
