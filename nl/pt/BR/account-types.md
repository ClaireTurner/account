---

copyright:

  years: 2015, 2018
lastupdated: "2018-08-14"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:new_window: target="_blank"}

# Tipos de Conta
{: #accounts}

É possível começar a construir no {{site.data.keyword.Bluemix}} de graça. Quando você estiver pronto para crescer, faça upgrade e pague somente pelo uso que ultrapassa os abonos grátis. O {{site.data.keyword.Bluemix}}
tem quatro tipos de contas diferentes: Lite, Pré-pago, Assinatura e Promo. Escolha aquele que melhor atender às suas necessidades.
{:shortdesc}

## Comparação de conta
{: #compare}

A tabela a seguir fornece uma comparação das contas Lite, Pré-paga e Assinatura. 

|  | Lite  | Pré-paga | Inscrição |
|--------------------|--------------------|--------------------|--------------------|
| **Acesso à memória do Cloud Foundry grátis** | 256 MB | 512 MB | 512 MB |
| **Acesso aos [Planos de serviços Lite ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://console.bluemix.net/catalog/?search=label:lite%20lite){: new_window}** | ![Recurso disponível](../icons/icon_enabled.svg) | ![Recurso disponível](../icons/icon_enabled.svg) | ![Recurso disponível](../icons/icon_enabled.svg) |
| **Acesso a todos os planos grátis** |  | ![Recurso disponível](../icons/icon_enabled.svg) | ![Recurso disponível](../icons/icon_enabled.svg) |
| **Acesso ao catálogo integral** |  | ![Recurso disponível](../icons/icon_enabled.svg) | ![Recurso disponível](../icons/icon_enabled.svg) |
| **Sem restrições de tempo** | ![Recurso disponível](../icons/icon_enabled.svg) | ![Recurso disponível](../icons/icon_enabled.svg) | ![Recurso disponível](../icons/icon_enabled.svg) |
| **Custo zero garantido** | ![Recurso disponível](../icons/icon_enabled.svg) |  |  |
| **Precificação negociada** |  |  | ![Recurso disponível](../icons/icon_enabled.svg) |
| **Melhor para aprendizado ou construção de POCs** | ![Recurso disponível](../icons/icon_enabled.svg) | ![Recurso disponível](../icons/icon_enabled.svg) |  |
| **Adequado para casos de uso de produção** |  | ![Recurso disponível](../icons/icon_enabled.svg) | ![Recurso disponível](../icons/icon_enabled.svg) |
{: caption="Tabela 1. Comparação de contas do {{site.data.keyword.Bluemix_notm}}" caption-side="top"}

## Conta Lite
{: #liteaccount}

Inscreva-se para uma conta Lite grátis para construir os apps e explorar os serviços com os planos grátis
selecionados exibidos com uma tag Lite ![tag Lite](../icons/Lite.svg) no console do {{site.data.keyword.Bluemix_notm}}. Sua conta Lite não expira e seu cartão de crédito não é necessário.

Você tem acesso a um único grupo de recursos criado para você e denominado `Default`. Todas as suas instâncias de serviços que são gerenciadas pelo {{site.data.keyword.Bluemix_notm}} Identity and Access Management (IAM) são incluídas automaticamente nesse grupo de recursos. É possível atualizar o nome desse grupo de recursos a qualquer momento. Consulte [Renomeando um grupo de recursos](/docs/admin/resourcegroups.html#renaming-a-resource-group) para obter as etapas detalhadas.

Cada grupo de recursos é livre. Ao criar uma conexão entre um serviço gerenciado pelo IAM e um app Cloud Foundry, você cria um alias, que é uma instância de serviço, que conta para sua cota. Consulte [O que é um alias?](/docs/manageapps/connecting_apps.html#what_is_alias)
{: tip}

### O que está disponível?

Você pode estar se perguntando o que uma conta Lite oferece. Confira a lista a seguir de recursos-chave:

   * A conta é grátis, nenhum cartão de crédito é necessário.
   * A conta nunca expira.
   * É possível usar uma organização em uma região do {{site.data.keyword.Bluemix_notm}}.
   * Suporte grátis do {{site.data.keyword.Bluemix_notm}}.
   * Você recebe notificações por e-mail sobre o status da conta e limites de cota.
   * Seus apps Cloud Foundry podem acessar até 256 MB de memória instantânea de tempo execução grátis.
   * É possível trabalhar com um cluster do Kubernetes com 2 CPUs e 4 GB de RAM.
   * É possível ter uma instância de qualquer serviço no catálogo do [{{site.data.keyword.Bluemix_notm}} ![Ícone de link externo](../icons/launch-glyph.svg "Ícone de link externo")](https://console.bluemix.net/catalog/?search=label:lite%20lite){: new_window} que tenha um plano Lite.
   * Depois de 10 dias sem atividade de desenvolvimento, seus apps serão suspensos. É possível começar a trabalhar em novos apps sem ter que se preocupar com a obtenção de limites de cota de memória.
   * Depois de 30 dias sem atividade de desenvolvimento, suas instâncias de serviço com planos Lite serão excluídas. Dessa forma, não é necessário gerenciar a exclusão de instâncias inativas antes da criação de novas.

## Contas faturáveis
{: #billableacts}

Ao se inscrever em um plano faturável do {{site.data.keyword.Bluemix_notm}} ou solicitar um upgrade em sua conta, é possível selecionar quatro contas diferentes do {{site.data.keyword.Bluemix_notm}}. A tabela a seguir lista os diferentes tipos de contas e seus métodos de cobrança.

|Tipo de conta |	Como sou cobrado? |
|------------------|-----------------------|
|Pré-paga |	Os encargos baseiam-se no uso do cálculo e serviços do {{site.data.keyword.Bluemix_notm}} |
|Inscrição | É possível obter um desconto mensal com base em um compromisso de gasto mínimo mensal |
| {{site.data.keyword.Bluemix_dedicated_notm}} | Contrato anual |
|{{site.data.keyword.Bluemix_local_notm}} |	Contrato anual |
{:caption="Tabela 2. Contas e encargos faturáveis do {{site.data.keyword.Bluemix_notm}}" caption-side="top"}

Se você vincular sua conta faturável do {{site.data.keyword.Bluemix_notm}} a uma conta do SoftLayer, iniciando no primeiro do próximo mês, seus encargos combinados serão incluídos na fatura do {{site.data.keyword.Bluemix_notm}}. Para obter mais informações, veja [Visualizando créditos](/docs/pricing/viewing_usage.html#credits).
{: tip}

### Conta pré-paga

Com uma conta Pré-paga, é possível criar vários grupos de recursos para gerenciar facilmente a cota e
visualizar o uso do faturamento para um conjunto de recursos.

Você é elegível para abonos grátis de tempo de execução e serviço. Se você usar além do abono grátis, receberá uma fatura mensal do {{site.data.keyword.Bluemix_notm}}. A fatura será em dólares dos Estados Unidos (USD) e detalhará suas cobranças de recursos.

Em muitos países e regiões, é possível inscrever-se para uma conta pré-paga no console do {{site.data.keyword.Bluemix_notm}}. Depois de fornecer suas informações de faturamento e de cartão de crédito, aceite os termos e condições e envie sua solicitação de conta. Em seguida, seu cartão de crédito será validado. Um e-mail de confirmação dos dados da conta também será enviado. Alguns minutos após o recebimento do e-mail de confirmação, é possível retornar ao console para continuar a construção de seus apps.

Se sua solicitação on-line não puder ser processada para seu país ou sua região, entre em contato com a equipe de Vendas do {{site.data.keyword.Bluemix_notm}} usando o link listado na página [Suporte do {{site.data.keyword.Bluemix_notm}} ![Ícone de link externo](../icons/launch-glyph.svg)](http://ibm.biz/bluemixsupport){: new_window}.

É possível converter a sua conta pré-paga em uma conta de assinatura a qualquer momento. Entre em contato com a equipe de Vendas do {{site.data.keyword.Bluemix_notm}} usando o link listado na página [Suporte do {{site.data.keyword.Bluemix_notm}} ![Ícone de link externo](../icons/launch-glyph.svg)](http://ibm.biz/bluemixsupport){: new_window}.

### Conta Assinatura

Com uma conta Assinatura, é possível criar vários grupos de recursos para gerenciar facilmente a cota e
visualizar o uso do faturamento para um conjunto de recursos.

Você confirma uma quantia de gasto mínimo cada mês e recebe um desconto na assinatura que será aplicado a esse encargo mínimo. Você também paga por qualquer uso que exceda a quantia mínima de gasto.

Para se inscrever para uma conta de Assinatura e para obter mais informações sobre taxas e descontos de assinatura, deve-se entrar em contato com
as Vendas do {{site.data.keyword.Bluemix_notm}} usando o link listado na página [Suporte do {{site.data.keyword.Bluemix_notm}} ![Ícone de link externo](../icons/launch-glyph.svg)](http://ibm.biz/bluemixsupport){: new_window}.

### Conta do {{site.data.keyword.Bluemix_dedicated_notm}}

Com o {{site.data.keyword.Bluemix_dedicated_notm}}, é necessário inscrever-se para um prazo mínimo de um ano que inclui:

   * Conectividade VPN de volta para a sua infraestrutura
   * Ambiente completamente redundante em um data center do {{site.data.keyword.BluSoftlayer_notm}}
   * Todos os tempos de execução suportados (IBM Java Liberty, Node.js e tempos de execução de software livre integrados)
   * Todos os serviços dedicados que selecionar e todos os serviços públicos do {{site.data.keyword.Bluemix_notm}}
   * Suporte {{site.data.keyword.Bluemix_notm}} padrão

Também é possível pedir itens opcionais, tais como o SoftLayer DirectLink ou opções de suporte premium. Entre em contato com
[Vendas do {{site.data.keyword.Bluemix_notm}} ![Ícone de link externo](../icons/launch-glyph.svg)](http://ibm.biz/bluemixsupport){: new_window}
para obter mais informações.

Durante esse prazo, cada mês você pagará com base nos serviços dedicados que desejar, mais uma conta de Assinatura que dará acesso a todos os serviços públicos. Os encargos de uso dos serviços no {{site.data.keyword.Bluemix_notm}} Público são calculados com base no contrato da conta da assinatura. Você recebe uma fatura para os serviços usados, além desse contrato de assinatura. Entre em contato com o representante de conta designado da IBM ou com as [Vendas do {{site.data.keyword.Bluemix_notm}} ![Ícone de link externo](../icons/launch-glyph.svg)](http://ibm.biz/bluemixsupport){: new_window}
para iniciar a utilização de seu contrato.

### Conta do {{site.data.keyword.Bluemix_local_notm}}

Com o {{site.data.keyword.Bluemix_local_notm}}, deve-se inscrever por um prazo mínimo de um ano que inclui:

   * Uma capacidade de entrega denominada retransmissão que permite que a IBM se conecte à implementação local e entregue atualizações de forma automática e consistente.
   * Todos os tempos de execução suportados (IBM Java Liberty, Node.js e tempos de execução de software livre integrados)
   * Todos os serviços locais que você selecionou e acesso a todos os serviços públicos do {{site.data.keyword.Bluemix_notm}}
   * Suporte {{site.data.keyword.Bluemix_notm}} padrão

Durante esse prazo, cada mês você pagará com base nos serviços locais que desejar, mais uma conta de Assinatura que dará acesso a todos os serviços públicos. Os encargos de uso dos serviços no {{site.data.keyword.Bluemix_notm}} Público são calculados com base no contrato da conta da assinatura. Você recebe uma fatura para os serviços usados, além desse contrato de assinatura. Entre em contato com o representante de conta designado da IBM ou com as [Vendas do {{site.data.keyword.Bluemix_notm}} ![Ícone de link externo](../icons/launch-glyph.svg)](http://ibm.biz/bluemixsupport){: new_window}
para iniciar a utilização de seu contrato.

## Conta Promocional
{: #promo}

As contas Promocionais, oferecidas ocasionalmente como parte de promoções especiais, são avaliações grátis de prazo fechado com acesso à maior parte do catálogo do {{site.data.keyword.Bluemix_notm}}. Esse tipo de conta está disponível somente usando um código promocional. O período de tempo de validade para a conta varia por promoção.

Com uma conta promocional, você tem acesso a um único grupo de recursos que é criado para você e denominado `Padrão`. Todas as suas instâncias de serviço gerenciado pelo IAM são automaticamente incluídas nesse grupo de recursos. É possível atualizar o nome desse grupo de recursos a qualquer momento. Consulte [Renomeando um grupo de recursos](/docs/admin/resource-groups.html#renaming-a-resource-group) para obter as etapas detalhadas.

Cada grupo de recursos é livre. Ao criar uma conexão entre um serviço gerenciado pelo IAM e um aplicativo Cloud Foundry, crie um alias, que é uma instância de serviço, que conta para sua cota. Consulte [O que é um alias?](/docs/manageapps/connecting_apps.html#what_is_alias)
{: tip}

### O que acontece quando minha conta promocional expira?
{: #trialend}

Quando sua conta promocional expira, os aplicativos em sua conta são interrompidos. Não é possível se inscrever para outra conta do {{site.data.keyword.Bluemix_notm}}, mas ainda é possível acessar sua conta e quaisquer contas para as quais você é convidado.

Para reiniciar seus apps, converta sua conta para uma conta faturável fornecendo informações de cartão de crédito para uma conta pré-paga ou criando uma conta de assinatura. Será possível então continuar usando os abonos de cálculo e serviço grátis. Você pagará apenas pelo uso de serviços, contêineres e tempos de execução não incluídos no abono mensal grátis.

Se você não converter sua conta após a expiração da conta promocional, seus aplicativos e serviços serão removidos após 30 dias. No entanto, sua conta não será excluída e será possível efetuar login e fazer upgrade para uma conta faturável a qualquer momento. Além disso, você recebe notificações por e-mail para lembrá-lo de criar uma conta faturável e evitar perder suas configurações de app e configurações de serviço. Se preferir não receber notificações do {{site.data.keyword.Bluemix_notm}}, será possível cancelar a assinatura a qualquer momento.

Se você converter sua conta, seus abonos grátis serão limitados aos abonos normalmente fornecidos por serviço. Os abonos não são mais de uso ilimitado oferecidos por muitos dos serviços IBM durante a avaliação grátis.
