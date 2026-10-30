# Sunny · Comparativo entre briefing e entrega

Data: 30/10/2026. Versão corrigida para aderência ao briefing, antes do envio à aprovação do cliente.

## Base da análise

- Briefing: `assets/[Aiconiq] Sunny · Estrutura e copy da LP · profissionais.docx`.
- Entrega: `index.html` e os arquivos referenciados em `assets/`.
- Escopo: comparação de conteúdo, direção visual e implementação local. Não constitui validação clínica, regulatória ou homologação das integrações em produção.

## Avaliação geral

A entrega mantém o posicionamento B2B, a sequência de seções e os argumentos técnicos do briefing. O formulário qualifica o contato por CRM e especialidade, e os CTAs conduzem à apresentação técnica. A ausência de depoimento público segue a orientação expressa do documento.

O hero foi corrigido para seguir a direção do briefing: equipamento Sunny em composição de consultório clínico, com close da ponteira Quasar e identificação dos 25 pinos. Os recortes oficiais do equipamento e da ponteira são preservados; somente o fundo de consultório é uma imagem ilustrativa gerada por IA. A versão anterior com modelo foi substituída. A revisão visual não substitui a aprovação do cliente ou a confirmação das informações marcadas como pendentes no briefing.

## Comparação por requisito

| Item do briefing | Entrega observada | Avaliação |
| --- | --- | --- |
| Público: dermatologistas; venda da tecnologia para a clínica | Texto dirigido ao profissional, foco em controle de energia e protocolos; CRM obrigatório e seleção de especialidade | Atendido na implementação. O formulário aceita também Cirurgia plástica e Outra, como solicitado; não é uma restrição exclusiva a dermatologistas. |
| Tom técnico, sem citar tecnologias concorrentes nem prometer resultado garantido | Mecanismos, parâmetros e suporte descritos; sem marcas concorrentes ou antes/depois; aviso de variação dos resultados | Alinhado editorialmente. As alegações clínicas e de exclusividade reproduzidas ainda exigem confirmação do cliente. |
| 01 · Kicker, H1, subtexto, dois CTAs e reforço Aiconiq | Conteúdo preservado, com ênfase tipográfica no H1 e links para tecnologia e contato | Atendido. |
| 01 · Equipamento em clínica e close nos 25 pinos | Equipamento oficial completo sobre fundo ilustrativo de consultório; close oficial da Quasar com legenda dos 25 pinos na primeira dobra | Corrigido para seguir a direção do briefing. Fundo de consultório gerado; não representa uma instalação real. |
| 02 · Duas radiofrequências, mecanismo, SHENB/Coreia/27 anos/96 países | Textos implementados; vídeo da Quasar; contadores de 27 anos e 96 países | Atendido no conteúdo. Números de autoridade e exclusividade dependem de validação indicada no briefing. |
| 03 · IMCT, ACA, Hard/Soft e APRT | Quatro blocos com mídia, descrição técnica e CTA “Quero conhecer a Sunny na prática” | Atendido. Inclui os 25 pinos e os pulsos de 1 a 10 segmentos previstos. |
| 04 · Aplicações faciais e pescoço | Lista preservada e mapa facial interativo com quatro marcadores | Atendido na interface. Correspondência das indicações com o registro ANVISA ainda pendente. |
| 05 · Conforto, retorno à rotina, associação de protocolos e sessão de 30 minutos | Quatro itens e CTA implementados | Atendido no conteúdo. Tempo de sessão, downtime e compatibilidade clínica precisam da confirmação prevista no briefing. |
| 06 · SHENB e distribuição/suporte/treinamento Aiconiq | Texto institucional, imagem dos handpieces e identificação da origem sul-coreana | Parcial: suporte e treinamento descritos; não há número ANVISA nem afirmação explícita de treinamento incluso. |
| 07 · Depoimento com nome e CRM, somente quando disponível | Seção comentada no código e ausente da página pública | Conforme a condição do briefing. O exemplo comentado não é um depoimento real e não deve ser publicado como tal. |
| 08 · Apresentação técnica | Seção de próximo passo com texto previsto e CTA para contato | Atendido. |
| 09 · Formulário e qualificação | Nome, e-mail, WhatsApp, cidade, UF, CPF/CNPJ, CRM e especialidade obrigatórios; clínica opcional; consentimento obrigatório | Atendido na implementação dos campos. CRM é obrigatório, mas não há consulta a registro profissional; CPF/CNPJ é validado pelo comprimento, sem verificação de dígitos verificadores. |
| 09 · Consentimento e microcopy | Texto de consentimento, nota LGPD, mensagens de erro/sucesso e aviso sobre compatibilidade e agenda | Textos presentes. A existência dos avisos não equivale a uma avaliação de conformidade. O destino da política de privacidade precisa ser disponibilizado. |
| 10 · Cinco perguntas frequentes | Cinco perguntas/respostas preservadas em blocos expansíveis | Atendido na estrutura. Não se afirma que os dois handpieces vêm no padrão; composição comercial permanece pendente. |
| 11 · Identificação da empresa, marca, avisos e preferências | CNPJ e razão social, marca SHENB, uso profissional, variação de resultados e preferências de cookies | Atendido nos textos. Link `/privacidade/` aponta para página não incluída neste repositório. |
| URL sugerida sunny.aiconiq.com.br | Canonical, metadados sociais e dados estruturados usam o domínio sugerido | Configurado no código. Publicação e domínio não foram verificados nesta entrega. Push no GitHub não comprova implantação pública. |

## Implementações adicionais

- Navegação por âncoras e menu responsivo.
- Mapa facial interativo, FAQ expansível e contadores animados.
- Vídeo com poster e carregamento adiado; imagens com dimensões declaradas e carregamento adiado nas seções inferiores.
- Fontes locais, metadados de busca/compartilhamento e dados estruturados de organização, produto e FAQ.
- Preferência de movimento reduzido e elementos de acessibilidade, como labels, foco visível e mensagens de status.
- Código de conversão RD Station com identificador `sunny-lp-koko`, campos personalizados e atribuição por UTMs/click IDs.
- Configuração de GA4, Meta e gateway de tracking, além do banner de cookies. A configuração existente usa carregamento por padrão, com recusa posterior; o comportamento deve ser revisado pelos responsáveis antes da publicação.

Esses itens foram identificados no código. Não foram executados testes completos de acessibilidade, performance ou recebimento de conversões em serviços externos nesta revisão.

## Direção visual final

Paleta quente de bege e laranja Sunny, tipografia Sora, hierarquia editorial e CTAs com destaque. O hero mantém a altura controlada e mostra o equipamento inteiro e o close da Quasar, sem modelo e sem antes/depois.

O hero usa os recortes oficiais `sunny-equipamento.webp` e `ponteira-quasar.webp`, sem regenerar ou deformar o produto. O fundo `hero-consultorio-v1.jpg` é uma ilustração fotográfica gerada por IA de um consultório vazio; não é fotografia de uma clínica real. Os antigos JPGs com modelo permanecem no histórico/material do repositório, mas não são mais utilizados pela LP.

## Pendências antes da publicação e da ativação de mídia

### Confirmações do cliente previstas no briefing

1. **Indicações e ANVISA:** confirmar as aplicações autorizadas e fornecer o número do registro para inclusão na página.
2. **Parâmetros clínicos:** confirmar duração média por área, ausência de downtime, protocolo de referência, número/intervalo das sessões e composição padrão dos handpieces. O texto já apresenta “30 minutos” e ausência de afastamento; não há comprovação de validação desses pontos no material analisado.
3. **Autoridade e alegações técnicas:** confirmar 27 anos, 96 países e as afirmações de exclusividade. A copy implementada segue o briefing, mas não é uma verificação independente dessas alegações.
4. **Suporte:** confirmar treinamento incluso e escopo do suporte clínico/técnico/marketing.
5. **Prova social:** obter depoimento real, autorizado, com nome e CRM, somente se houver interesse em ativar a seção opcional.
6. **Imagem:** revisar a composição de consultório do hero; equipamento e ponteira usam recortes oficiais, e o ambiente é ilustrativo.

### Homologação técnica e operação

1. Disponibilizar a política de privacidade e confirmar a URL final; `/privacidade/` não existe neste repositório.
2. Testar uma conversão autorizada e confirmar o recebimento no RD Station, incluindo CRM, especialidade, telefone, origem e consentimento. Nesta revisão não foi enviado lead real ou fictício.
3. Homologar GA4, Meta/gateway e o comportamento de aceitar/recusar cookies no ambiente publicado. O comportamento de consentimento exige revisão específica; não foi certificado como adequado nesta análise.
4. Fazer revisão visual final em dispositivos móveis reais e navegadores de destino, além de verificar as interações e o formulário no ambiente publicado.
5. Confirmar domínio, HTTPS e arquivos de compartilhamento após a implantação.

## Verificação realizada nesta revisão

- Leitura do briefing completo por extração do DOCX e comparação com o HTML.
- Revisão visual local do hero clínico no Chrome em larguras de desktop e mobile após a correção para o briefing.
- Conferência estática de 20 referências locais de mídia/fontes/arquivos: sem arquivos ausentes.
- Conferência das âncoras internas: sem destinos ausentes.
- `git diff --check`: sem erros de whitespace.
- GitHub Pages ativado nesta entrega; a prévia pública da versão anterior foi verificada. A correção do hero exige nova verificação após o push. Nenhum teste de envio ao RD Station, consulta ANVISA, auditoria jurídica ou teste completo de tracking foi realizado.

## Encaminhamento

A versão está pronta para apresentação visual e revisão de conteúdo pelo cliente, com as pendências acima explicitadas. A liberação para produção e campanha depende das confirmações clínicas/comerciais e da homologação técnica. O depoimento pode continuar ausente, conforme autorizado pelo próprio briefing.
