# Sunny · Comparativo entre briefing e entrega

Data: 30/10/2026. Versão visual aprovada nesta revisão pela responsável pelo projeto, antes do envio à aprovação do cliente.

## Base da análise

- Briefing: `assets/[Aiconiq] Sunny · Estrutura e copy da LP · profissionais.docx`.
- Entrega: `index.html` e os arquivos referenciados em `assets/`.
- Escopo: comparação de conteúdo, direção visual e implementação local. Não constitui validação clínica, regulatória ou homologação das integrações em produção.

## Avaliação geral

A entrega mantém o posicionamento B2B, a sequência de seções e os argumentos técnicos do briefing. O formulário qualifica o contato por CRM e especialidade, e os CTAs conduzem à apresentação técnica. A ausência de depoimento público segue a orientação expressa do documento.

A principal adaptação é a imagem da primeira dobra: a entrega adota uma composição editorial com modelo, equipamento e luz prismática, em vez do equipamento em ambiente clínico com close da Quasar solicitado no briefing. O close técnico está representado nas seções de tecnologia e diferenciais. O header foi aprovado visualmente na revisão de 30/10; essa aprovação não substitui a aprovação do cliente ou a confirmação das informações marcadas como pendentes no briefing.

## Comparação por requisito

| Item do briefing | Entrega observada | Avaliação |
| --- | --- | --- |
| Público: dermatologistas; venda da tecnologia para a clínica | Texto dirigido ao profissional, foco em controle de energia e protocolos; CRM obrigatório e seleção de especialidade | Atendido na implementação. O formulário aceita também Cirurgia plástica e Outra, como solicitado; não é uma restrição exclusiva a dermatologistas. |
| Tom técnico, sem citar tecnologias concorrentes nem prometer resultado garantido | Mecanismos, parâmetros e suporte descritos; sem marcas concorrentes ou antes/depois; aviso de variação dos resultados | Alinhado editorialmente. As alegações clínicas e de exclusividade reproduzidas ainda exigem confirmação do cliente. |
| 01 · Kicker, H1, subtexto, dois CTAs e reforço Aiconiq | Conteúdo preservado, com ênfase tipográfica no H1 e links para tecnologia e contato | Atendido. |
| 01 · Equipamento em clínica e close nos 25 pinos | Hero com modelo e Sunny, fundo fotográfico contínuo; Quasar detalhada em outras seções | Adaptado visualmente e aprovado nesta revisão. A cena clínica e o close no hero não foram reproduzidos literalmente. |
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

Paleta quente de bege e laranja Sunny, tipografia Sora, hierarquia editorial e CTAs com destaque. A composição aprovada aproxima texto, modelo e equipamento e mantém a altura da primeira dobra controlada. O fundo fotográfico continua atrás do texto; a transição da imagem fica restrita à borda, antes do rosto.

O hero desktop usa `hero-sunny-wide-v3.jpg`; o fundo usa `hero-sunny-panorama-v4.jpg`; o mobile mantém `hero-sunny-amplo-v2.webp`. As duas versões JPG são adaptações geradas por IA a partir da imagem existente: devem ser tratadas como peças visuais, não como evidência técnica ou documentação do equipamento. Não se deve afirmar fidelidade técnica absoluta da representação gerada sem revisão do cliente.

## Pendências antes da publicação e da ativação de mídia

### Confirmações do cliente previstas no briefing

1. **Indicações e ANVISA:** confirmar as aplicações autorizadas e fornecer o número do registro para inclusão na página.
2. **Parâmetros clínicos:** confirmar duração média por área, ausência de downtime, protocolo de referência, número/intervalo das sessões e composição padrão dos handpieces. O texto já apresenta “30 minutos” e ausência de afastamento; não há comprovação de validação desses pontos no material analisado.
3. **Autoridade e alegações técnicas:** confirmar 27 anos, 96 países e as afirmações de exclusividade. A copy implementada segue o briefing, mas não é uma verificação independente dessas alegações.
4. **Suporte:** confirmar treinamento incluso e escopo do suporte clínico/técnico/marketing.
5. **Prova social:** obter depoimento real, autorizado, com nome e CRM, somente se houver interesse em ativar a seção opcional.
6. **Imagem:** aprovar a adaptação editorial do hero e revisar a representação do equipamento nas imagens geradas.

### Homologação técnica e operação

1. Disponibilizar a política de privacidade e confirmar a URL final; `/privacidade/` não existe neste repositório.
2. Testar uma conversão autorizada e confirmar o recebimento no RD Station, incluindo CRM, especialidade, telefone, origem e consentimento. Nesta revisão não foi enviado lead real ou fictício.
3. Homologar GA4, Meta/gateway e o comportamento de aceitar/recusar cookies no ambiente publicado. O comportamento de consentimento exige revisão específica; não foi certificado como adequado nesta análise.
4. Fazer revisão visual final em dispositivos móveis reais e navegadores de destino, além de verificar as interações e o formulário no ambiente publicado.
5. Confirmar domínio, HTTPS e arquivos de compartilhamento após a implantação.

## Verificação realizada nesta revisão

- Leitura do briefing completo por extração do DOCX e comparação com o HTML.
- Revisão visual local do hero no Chrome durante os ajustes; a aprovação visual da responsável refere-se à versão final desta conversa.
- Conferência estática de 22 referências locais de mídia/fontes/arquivos: sem arquivos ausentes.
- Conferência das âncoras internas: sem destinos ausentes.
- `git diff --check`: sem erros de whitespace.
- Nenhum teste de envio ao RD Station, consulta ANVISA, auditoria jurídica, teste completo de tracking ou implantação pública foi realizado.

## Encaminhamento

A versão está pronta para apresentação visual e revisão de conteúdo pelo cliente, com as pendências acima explicitadas. A liberação para produção e campanha depende das confirmações clínicas/comerciais e da homologação técnica. O depoimento pode continuar ausente, conforme autorizado pelo próprio briefing.
