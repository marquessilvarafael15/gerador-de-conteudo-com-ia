# gerador-de-conteudo-com-ia
Gerador de conteúdo com IA
## A dor escolhida e por que ela vale um negócio
O EngenIA resolve a dificuldade que engenheiros civis enfrentam para criar conteúdos profissionais, manter uma presença digital consistente e transformar seu conhecimento técnico em autoridade e oportunidades de novos clientes, mesmo sem tempo ou conhecimento em marketing digital.
Em resumo: o EngenIA transforma conhecimento técnico em conteúdo estratégico, economizando tempo e ajudando engenheiros a conquistar mais visibilidade e potenciais clientes.

O EngenIA vale como negócio porque atende a um público profissional específico, resolve uma dor recorrente e oferece uma solução escalável com Inteligência Artificial.
Seu potencial está em gerar receita recorrente por assinaturas, ter custos operacionais relativamente baixos e ajudar engenheiros civis a economizar tempo, fortalecer sua autoridade digital e atrair potenciais clientes.
## O tamanho de mercado e o Business Model Canvas
O EngenIA atua no mercado brasileiro de engenharia civil, marketing digital e inteligência artificial, com foco inicial em engenheiros autônomos, escritórios e pequenas construtoras.
O potencial é interessante porque o Brasil possui uma ampla base de profissionais de engenharia, mas nem todos precisam ou estão dispostos a pagar por ferramentas de criação de conteúdo.
O mercado deve ser avaliado em três níveis:
- TAM: todos os engenheiros civis e empresas de engenharia que poderiam utilizar a solução.
- SAM: profissionais e empresas que investem ou desejam investir em presença digital.
- SOM: parcela desse público que o EngenIA pode conquistar nos primeiros anos.

BUSINESS MODEL CANVAS

**1. Segmentos de Clientes**

Engenheiros civis autônomos, escritórios de engenharia, pequenas construtoras e profissionais que desejam fortalecer sua presença digital, divulgar serviços e captar potenciais clientes.

**2. Proposta de Valor**

Oferecer uma plataforma especializada em engenharia civil que utiliza Inteligência Artificial para criar conteúdos profissionais, legendas, carrosséis, roteiros e planejamentos editoriais, economizando tempo e ajudando engenheiros a construir autoridade digital.

**3. Canais**

Instagram, Google Ads, marketing de conteúdo, landing page, parcerias com influenciadores da engenharia, entidades profissionais, universidades e indicações de clientes.

**4. Relacionamento com Clientes**

Atendimento digital, onboarding personalizado, suporte online, tutoriais, automação de comunicação e estratégias de fidelização por meio de atualizações e melhorias contínuas.

**5. Fontes de Receita**

Assinaturas mensais e anuais, com planos diferenciados por quantidade de conteúdos, créditos de IA e funcionalidades disponíveis. Possibilidade futura de venda de créditos adicionais e planos empresariais.

**6. Recursos Principais**

Plataforma SaaS, Inteligência Artificial Generativa, infraestrutura tecnológica, banco de dados, biblioteca de templates, identidade da marca EngenIA e conhecimento especializado em engenharia civil e marketing digital.

**7. Atividades Principais**

Desenvolvimento e manutenção do aplicativo, aprimoramento dos modelos de geração de conteúdo, criação de templates, aquisição de clientes, marketing digital, suporte e monitoramento da experiência dos usuários.

**8. Parcerias Principais**

Provedores de Inteligência Artificial, serviços de hospedagem e infraestrutura, plataformas de pagamento, profissionais de marketing, influenciadores do setor, instituições de ensino e entidades ligadas à engenharia civil.

**9. Estrutura de Custos**

Consumo de APIs de Inteligência Artificial, hospedagem, armazenamento, desenvolvimento, manutenção, marketing, aquisição de clientes, processamento de pagamentos, atendimento e despesas administrativas.
## A tese que o MVP testa e o que ficou manual de propósito
1. Tese que o MVP testa

Validar se engenheiros civis estão dispostos a pagar uma assinatura recorrente por uma plataforma de IA que simplifica a criação de conteúdo, economiza tempo e ajuda a construir autoridade digital.

2. O que ainda permanece manual
- Revisão e aprovação técnica dos conteúdos pelo engenheiro.
- Publicação dos conteúdos nas redes sociais.
- Gravação e edição dos vídeos a partir dos roteiros gerados.
- Acompanhamento dos resultados e ajustes da estratégia digital.
## O mega prompt e as correções
# PRD — ENGENIA
## Plataforma de Criação de Conteúdo com Inteligência Artificial para Engenheiros Civis

**Nome do produto:** EngenIA  
**Slogan oficial:** Construindo sua autoridade digital.  
**Versão do PRD:** 1.0  
**Categoria:** SaaS com Inteligência Artificial Generativa  
**Plataforma:** Aplicativo web responsivo (desktop, tablet e smartphone)  
**Idioma:** Português do Brasil (pt-BR)  
**Mercado inicial:** Brasil  
**Ambiente de desenvolvimento:** Lovable  
**Objetivo:** Desenvolvimento de um MVP funcional, seguro, acessível e comercializável.

---

# 1. INSTRUÇÕES GERAIS PARA O LOVABLE

Desenvolva um aplicativo SaaS chamado EngenIA, com o slogan oficial "Construindo sua autoridade digital".

O EngenIA será uma plataforma especializada na criação de conteúdos para engenheiros civis, utilizando Inteligência Artificial Generativa para transformar conhecimentos técnicos em conteúdos profissionais, educativos, institucionais e comerciais.

O aplicativo deverá permitir que engenheiros civis criem conteúdos para redes sociais sem precisar dominar marketing digital, redação publicitária, design gráfico ou planejamento editorial.

O desenvolvimento deverá priorizar uma experiência intuitiva, moderna, responsiva e acessível.

O objetivo não é construir apenas uma interface demonstrativa. O MVP deverá possuir funcionalidades reais, autenticação, banco de dados, integração segura com IA, armazenamento de projetos, edição, exportação e controle de utilização.

Requisitos obrigatórios:

- Desenvolver uma aplicação web responsiva.
- Utilizar arquitetura modular e componentes reutilizáveis.
- Implementar autenticação real.
- Utilizar banco de dados persistente.
- Integrar uma API de Inteligência Artificial por meio de funções seguras no backend.
- Permitir criação, edição, salvamento e exportação de conteúdos.
- Aplicar a identidade visual oficial do EngenIA.
- Garantir isolamento de dados entre usuários.
- Implementar controles de segurança e privacidade.
- Seguir os princípios de Design Universal e os critérios aplicáveis da WCAG 2.2 AA.
- Preparar o aplicativo para monetização recorrente.
- Priorizar as funcionalidades do MVP.
- Não utilizar dados fictícios como se fossem informações reais.
- Não deixar botões sem funcionalidade.
- Não expor credenciais ou chaves de API no frontend.

A construção deverá ocorrer por etapas, preservando a consistência da arquitetura.

---

# 2. VISÃO GERAL DO PRODUTO

## 2.1. Descrição

O EngenIA será um aplicativo de criação de conteúdo com Inteligência Artificial desenvolvido especificamente para engenheiros civis, escritórios de engenharia e pequenas construtoras.

A plataforma permitirá transformar conhecimentos profissionais, especialidades, serviços, experiências de obra e objetivos comerciais em conteúdos digitais estrategicamente organizados.

O aplicativo reunirá:

1. Perfil profissional personalizado.
2. Identidade visual da marca.
3. Estratégia de comunicação.
4. Geração de ideias com IA.
5. Criação de legendas.
6. Criação de carrosséis.
7. Criação de roteiros para Reels.
8. Editor visual.
9. Planejamento editorial.
10. Calendário de publicações.
11. Biblioteca de conteúdos.
12. Revisão de informações técnicas.
13. Exportação de materiais.
14. Gerenciamento de assinatura e créditos.

O diferencial competitivo será a especialização na engenharia civil.

O EngenIA não deverá funcionar como um gerador genérico de textos. Suas respostas deverão considerar o contexto profissional, a especialidade, os serviços, o público-alvo e os objetivos comerciais do usuário.

## 2.2. Missão

Democratizar a criação de conteúdo profissional para engenheiros civis, utilizando Inteligência Artificial para facilitar a comunicação, fortalecer o posicionamento digital e apoiar a geração de oportunidades comerciais.

## 2.3. Visão

Tornar-se uma plataforma de referência para criação de conteúdo e posicionamento digital de profissionais e empresas de engenharia civil no Brasil.

## 2.4. Proposta de valor

Permitir que engenheiros civis transformem seu conhecimento técnico em conteúdos profissionais que fortaleçam sua autoridade e ampliem sua presença digital.

## 2.5. Slogan oficial

**EngenIA — Construindo sua autoridade digital.**

O slogan deverá aparecer na Landing Page, na apresentação institucional e em materiais de comunicação da marca.

## 2.6. Problemas que o produto pretende resolver

- Falta de tempo para produzir conteúdos.
- Dificuldade para desenvolver ideias.
- Dificuldade para transformar informações técnicas em linguagem acessível.
- Falta de conhecimento em marketing digital.
- Dificuldade para criar artes.
- Falta de identidade visual consistente.
- Ausência de planejamento editorial.
- Dificuldade para criar roteiros de vídeos.
- Falta de regularidade nas publicações.
- Dependência de várias ferramentas para executar a criação.

Esses problemas são hipóteses que deverão ser validadas com usuários reais.

## 2.7. Objetivo principal

Permitir que um engenheiro civil consiga criar, revisar, personalizar, organizar e exportar conteúdos profissionais para redes sociais em poucos minutos.

## 2.8. Objetivos secundários

- Reduzir o tempo de produção.
- Melhorar a consistência editorial.
- Facilitar a comunicação técnica.
- Fortalecer a autoridade profissional.
- Apoiar a divulgação de serviços.
- Estimular publicações recorrentes.
- Facilitar a organização do conteúdo.
- Padronizar a identidade visual.
- Apoiar a captação de potenciais clientes.
- Criar uma operação SaaS sustentável.

## 2.9. Indicadores de sucesso

Metas iniciais propostas:

- Pelo menos 70% dos usuários concluindo o onboarding.
- Pelo menos 60% dos novos usuários criando o primeiro conteúdo.
- Tempo mediano de até 3 minutos para gerar o primeiro rascunho.
- Pelo menos 75% dos conteúdos aprovados com até duas revisões.
- Pelo menos 75% de retenção dos assinantes pagos no segundo mês.
- Disponibilidade mensal de pelo menos 99,5%.

Essas metas deverão ser revisadas após a validação do MVP.

---

# 3. PÚBLICO-ALVO E PERSONAS

## 3.1. Público principal

Engenheiros civis autônomos que desejam utilizar redes sociais para fortalecer seu posicionamento profissional, divulgar serviços e atrair potenciais clientes.

## 3.2. Públicos secundários

- Engenheiros recém-formados.
- Escritórios de engenharia.
- Pequenas construtoras.
- Engenheiros especializados em projetos.
- Engenheiros especializados em obras.
- Profissionais de reformas.
- Engenheiros de gerenciamento de obras.
- Profissionais de inspeção predial.
- Especialistas em patologias das construções.
- Consultores de engenharia.
- Profissionais de marketing que atendem engenheiros.

## 3.3. Persona principal

**Nome fictício:** Carlos.

**Idade:** 35 anos.

**Profissão:** Engenheiro civil.

**Atuação:** Construção e gerenciamento de obras residenciais.

**Objetivo:** Captar clientes interessados em construir casas.

**Dificuldades:**

- Não sabe o que publicar.
- Tem pouco tempo.
- Não domina ferramentas de design.
- Não possui planejamento de conteúdo.
- Tem dificuldade para transformar conhecimentos técnicos em publicações.

**Necessidade:** Criar conteúdos profissionais rapidamente, com orientação estratégica e identidade visual consistente.

## 3.4. Especialidades disponíveis

O aplicativo deverá permitir a seleção de uma ou mais especialidades:

1. Construção residencial.
2. Construção de casas de alto padrão.
3. Projetos estruturais.
4. Reformas e ampliações.
5. Gerenciamento de obras.
6. Fiscalização de obras.
7. Regularização de imóveis.
8. Laudos e perícias.
9. Inspeção predial.
10. Patologias das construções.
11. Fundações e geotecnia.
12. Instalações hidrossanitárias.
13. Orçamento de obras.
14. Planejamento de obras.
15. Engenharia de segurança, conforme habilitação.
16. Infraestrutura.
17. Consultoria técnica.
18. Construção sustentável.
19. Compatibilização de projetos.
20. BIM.
21. Outra especialidade.

A seleção de especialidades não deverá ser interpretada como verificação de habilitação profissional.

---

# 4. PRINCÍPIOS DO PRODUTO

## 4.1. Simplicidade

O aplicativo deverá ser intuitivo para usuários sem conhecimento avançado de tecnologia ou marketing.

## 4.2. Personalização

A IA deverá utilizar as informações cadastradas pelo usuário para adaptar os conteúdos.

## 4.3. Especialização

As respostas deverão ser contextualizadas à engenharia civil.

## 4.4. Consistência

O aplicativo deverá preservar a identidade visual e o tom de comunicação configurados.

## 4.5. Controle humano

O usuário deverá revisar e aprovar os conteúdos antes da exportação final.

## 4.6. Responsabilidade técnica

A IA não poderá inventar normas, resultados de cálculos, projetos executados, depoimentos ou qualificações profissionais.

## 4.7. Acessibilidade

O aplicativo deverá seguir princípios de Design Universal e acessibilidade digital.

## 4.8. Privacidade

Dados e conteúdos deverão ser protegidos e isolados por conta ou organização.

---

# 5. ESTRUTURA GERAL DO APLICATIVO

O EngenIA deverá possuir:

1. Landing Page.
2. Cadastro e Login.
3. Onboarding.
4. Dashboard.
5. Criar Conteúdo.
6. Gerador de Ideias.
7. Gerador de Legendas.
8. Gerador de Carrosséis.
9. Gerador de Roteiros.
10. Editor Visual.
11. Planejamento Editorial.
12. Calendário.
13. Biblioteca.
14. Minha Marca.
15. Assinatura e Créditos.
16. Configurações.
17. Painel Administrativo.

O botão "Criar Conteúdo" deverá ser o principal CTA da interface interna.

---

# 6. IDENTIDADE VISUAL E DESIGN SYSTEM

## 6.1. Direção criativa

O EngenIA deverá apresentar identidade visual profissional, tecnológica, moderna e minimalista.

A aparência deverá transmitir:

- Engenharia.
- Precisão.
- Confiança.
- Inteligência.
- Inovação.
- Organização.
- Autoridade.

Evitar excesso de efeitos visuais, elementos infantis e interfaces poluídas.

## 6.2. Paleta de cores

**Azul estrutural:** #14243A  
Aplicação: cabeçalhos, navegação e elementos institucionais.

**Azul tecnológico:** #2763A6  
Aplicação: botões principais, links e estados ativos.

**Azul claro:** #DCE8F2  
Aplicação: fundos secundários e elementos informativos.

**Branco:** #FFFFFF  
Aplicação: cartões e superfícies.

**Cinza claro:** #F6F8FB  
Aplicação: fundo geral.

**Cinza escuro:** #18212F  
Aplicação: textos principais.

**Verde:** #228B5E  
Aplicação: sucesso.

**Vermelho:** #C0392B  
Aplicação: erros e alertas críticos.

A aplicação das cores deverá respeitar os critérios de contraste acessível.

## 6.3. Tipografia

Utilizar Inter ou fonte equivalente.

Escala sugerida:

- H1: 32 px.
- H2: 24 px.
- H3: 20 px.
- Texto principal: 16 px.
- Texto auxiliar: 14 px.

## 6.4. Componentes

Criar componentes reutilizáveis:

- Botões.
- Inputs.
- Selects.
- Checkboxes.
- Radio buttons.
- Cards.
- Modais.
- Abas.
- Menus.
- Dropdowns.
- Alertas.
- Tooltips.
- Toasts.
- Indicadores de progresso.
- Skeleton loading.
- Estados vazios.
- Calendário.
- Editor.
- Preview de conteúdo.
- Indicador de créditos.

## 6.5. Responsividade

**Desktop:**

- Sidebar.
- Cabeçalho superior.
- Área central.
- Cards em grid.
- Editor com painel lateral.

**Tablet:**

- Sidebar recolhível.
- Grids adaptáveis.
- Editor responsivo.

**Smartphone:**

- Navegação inferior.
- Cards em coluna.
- Formulários simplificados.
- Botões acessíveis ao toque.
- Editor adaptado para telas pequenas.

---

# 7. REQUISITOS FUNCIONAIS

## RF-001 — Autenticação

Funcionalidades:

- Cadastro.
- Login.
- Logout.
- Verificação de e-mail.
- Recuperação de senha.
- Alteração de senha.
- Exclusão de conta.

### Critérios de aceite

- O usuário consegue criar conta.
- O e-mail é único.
- O login funciona.
- A recuperação de senha funciona.
- Rotas privadas exigem autenticação.
- O logout encerra a sessão.
- Dados de outras contas não são acessíveis.

## RF-002 — Onboarding

O onboarding deverá possuir seis etapas.

### Etapa 1 — Dados profissionais

- Nome completo.
- Nome profissional.
- Empresa.
- CREA opcional.
- Estado do CREA.
- Cidade.
- Estado.
- Especialidades.

### Etapa 2 — Serviços

Permitir selecionar serviços e adicionar opções personalizadas.

### Etapa 3 — Público-alvo

- Famílias que desejam construir.
- Proprietários de terrenos.
- Proprietários que desejam reformar.
- Empresas.
- Construtoras.
- Condomínios.
- Investidores imobiliários.
- Outros.

### Etapa 4 — Objetivos

- Captar clientes.
- Construir autoridade.
- Aumentar reconhecimento.
- Divulgar serviços.
- Mostrar obras.
- Educar o público.
- Gerar engajamento.

### Etapa 5 — Comunicação

- Profissional.
- Técnico.
- Educativo.
- Premium.
- Próximo.
- Comercial.
- Personalizado.

### Etapa 6 — Identidade visual

- Logomarca.
- Cor principal.
- Cor secundária.
- Cor de destaque.
- Fonte.
- Instagram.
- WhatsApp.
- Site.

### Critérios de aceite

- Progresso por etapas.
- Validação de campos.
- Salvamento do progresso.
- Possibilidade de voltar.
- Possibilidade de editar depois.
- Dados utilizados pela IA.

## RF-003 — Dashboard

Elementos:

- Saudação personalizada.
- Nome da marca.
- Botão "Criar Conteúdo".
- Botão "Gerar Ideias".
- Botão "Criar Carrossel".
- Botão "Criar Roteiro".
- Conteúdos recentes.
- Próximas publicações.
- Quantidade de conteúdos.
- Créditos disponíveis.
- Sugestão de conteúdo.

### Critérios de aceite

- Dados reais do usuário.
- Atalhos funcionais.
- Indicadores atualizados.
- Estado vazio para contas novas.
- Navegação correta.

## RF-004 — Gerador de ideias

Campos:

- Especialidade.
- Serviço.
- Tema.
- Público.
- Objetivo.
- Formato.
- Quantidade.
- Tom.

Quantidades:

- 3 ideias.
- 5 ideias.
- 10 ideias.

Cada ideia deverá conter:

- Título.
- Gancho.
- Resumo.
- Pilar editorial.
- Formato.
- Objetivo.
- CTA.

Ações:

- Salvar.
- Favoritar.
- Regenerar.
- Transformar em legenda.
- Transformar em carrossel.
- Transformar em roteiro.
- Adicionar ao calendário.

### Critérios de aceite

- Ideias coerentes com a especialidade.
- Sem duplicações na mesma geração.
- Resultados salvos corretamente.
- Falhas recuperáveis.
- Consumo correto de créditos.

## RF-005 — Gerador de legendas

Campos:

- Tema.
- Objetivo.
- Público.
- Tom.
- Tamanho.
- CTA.
- Emojis.
- Hashtags.

Tamanhos:

- Curta.
- Média.
- Longa.

Estrutura:

1. Gancho.
2. Desenvolvimento.
3. Informação.
4. Benefício.
5. CTA.
6. Hashtags opcionais.

Funcionalidades:

- Gerar.
- Editar.
- Regenerar.
- Encurtar.
- Expandir.
- Alterar tom.
- Copiar.
- Salvar.
- Adicionar ao calendário.

### Critérios de aceite

- Texto editável.
- Personalização pelo perfil.
- Salvamento persistente.
- Cópia funcional.
- Revisão humana.
- Ausência de afirmações inventadas sobre o usuário.

## RF-006 — Gerador de carrosséis

Quantidade: 3 a 10 slides.

Formatos:

- 1080 × 1080 px.
- 1080 × 1350 px.

Estrutura:

- Capa.
- Problema.
- Desenvolvimento.
- Explicação.
- Síntese.
- CTA.

Funcionalidades:

- Gerar conteúdo.
- Escolher template.
- Editar textos.
- Alterar imagens.
- Alterar cores.
- Alterar fontes.
- Inserir logomarca.
- Reordenar slides.
- Visualizar.
- Salvar.
- Exportar PNG.
- Exportar ZIP.

### Critérios de aceite

- Quantidade correta de slides.
- Textos editáveis.
- Identidade visual preservada.
- Ausência de textos cortados.
- Exportação nas dimensões corretas.
- Revisão antes da aprovação.

## RF-007 — Gerador de roteiros para Reels

Durações:

- 15 segundos.
- 30 segundos.
- 45 segundos.
- 60 segundos.
- 90 segundos.

Estilos:

- Falando para câmera.
- Narração com imagens.
- Educativo.
- Comercial.
- Bastidores.
- Storytelling.
- Perguntas e respostas.

Estrutura:

- Gancho.
- Texto falado.
- Sugestões de cenas.
- Enquadramentos.
- Texto na tela.
- Duração aproximada.
- CTA.
- Legenda complementar.

### Critérios de aceite

- Roteiro organizado.
- Texto editável.
- Duração coerente.
- Salvamento.
- Cópia.
- Adição ao calendário.

## RF-008 — Editor visual

Recursos:

- Editar títulos.
- Editar textos.
- Trocar imagens.
- Alterar cores.
- Alterar fontes.
- Inserir logomarca.
- Ajustar elementos.
- Reordenar slides.
- Desfazer.
- Refazer.
- Salvar automaticamente.
- Pré-visualizar.
- Exportar.

### Critérios de aceite

- Alterações persistentes.
- Preview atualizado.
- Arquivos sem cortes.
- Logomarca sem distorção.
- Controles acessíveis.
- Exportação correspondente à pré-visualização.

## RF-009 — Planejamento editorial

Períodos:

- 7 dias.
- 15 dias.
- 30 dias.

Campos:

- Especialidade.
- Serviços.
- Objetivo.
- Público.
- Frequência.
- Pilares.
- Formatos.

Pilares:

1. Autoridade.
2. Educação.
3. Prova social.
4. Relacionamento.
5. Conversão.

Cada sugestão deverá conter:

- Data.
- Tema.
- Título.
- Pilar.
- Formato.
- Objetivo.
- CTA.

Funcionalidades:

- Gerar.
- Editar.
- Substituir sugestões.
- Alterar datas.
- Aprovar.
- Criar conteúdo.
- Salvar no calendário.

### Critérios de aceite

- Datas válidas.
- Frequência respeitada.
- Temas editáveis.
- Sem duplicações evidentes.
- Planejamento persistente.

## RF-010 — Calendário editorial

Funcionalidades:

- Visualização mensal.
- Visualização semanal.
- Adicionar conteúdo.
- Alterar data.
- Editar status.
- Filtrar.
- Abrir conteúdo.
- Remover item.
- Registrar publicação manual.

Status:

- Ideia.
- Rascunho.
- Em revisão.
- Aprovado.
- Agendado externamente.
- Publicado.

### Critérios de aceite

- Datas corretas.
- Alterações persistentes.
- Filtros funcionais.
- Navegação para editor.
- Atualização de status.

## RF-011 — Biblioteca

Funcionalidades:

- Listar.
- Pesquisar.
- Filtrar.
- Favoritar.
- Editar.
- Duplicar.
- Arquivar.
- Excluir.
- Consultar versões.

Filtros:

- Formato.
- Status.
- Data.
- Pilar.
- Favoritos.

### Critérios de aceite

- Conteúdos salvos aparecem.
- Pesquisa funciona.
- Filtros funcionam.
- Exclusão exige confirmação.
- Isolamento de dados.
- Histórico de versões acessível.

## RF-012 — Minha Marca

Campos editáveis:

- Nome profissional.
- Nome empresarial.
- Especialidades.
- Serviços.
- Público.
- Objetivos.
- Tom.
- Logomarca.
- Cores.
- Fonte.
- Instagram.
- WhatsApp.
- Site.

### Critérios de aceite

- Alterações persistentes.
- Novos conteúdos utilizam os dados atualizados.
- Conteúdos antigos não são modificados automaticamente.
- Identidade visual pode ser pré-visualizada.

## RF-013 — Revisão técnica

O EngenIA deverá apresentar alertas e uma etapa de revisão antes da aprovação.

Funcionalidades:

- Identificar afirmações técnicas verificáveis.
- Sinalizar incertezas.
- Alertar sobre referências ausentes.
- Permitir edição.
- Permitir remoção.
- Registrar confirmação.

A IA não deverá inventar:

- Normas.
- Números de normas.
- Resultados de cálculos.
- Laudos.
- Ensaios.
- Projetos.
- Obras executadas.
- Depoimentos.
- Habilitações profissionais.

### Critérios de aceite

- Alertas apresentados.
- Conteúdos editáveis.
- Pendências tratáveis.
- Confirmação registrada.
- Exportação final condicionada à aprovação.
- A aprovação não é apresentada como certificação técnica pelo EngenIA.

## RF-014 — Exportação

Formatos:

- Copiar texto.
- PNG.
- ZIP.
- TXT.

### Critérios de aceite

- Arquivos corretos.
- Dimensões preservadas.
- Textos sem cortes.
- Imagens sem distorções.
- Nomes de arquivo organizados.
- Aprovação exigida quando aplicável.

## RF-015 — Assinaturas e créditos

Funcionalidades:

- Visualizar plano.
- Consultar créditos.
- Consultar consumo.
- Contratar plano.
- Alterar plano.
- Cancelar assinatura.
- Consultar cobranças.

### Critérios de aceite

- Saldo correto.
- Consumo atualizado.
- Limites aplicados.
- Cobranças processadas com segurança.
- Eventos duplicados não geram cobranças duplicadas.
- Cancelamento funcional.

---

# 8. USER STORIES

US-001 — Como visitante, quero conhecer o EngenIA para entender seus benefícios.

US-002 — Como engenheiro, quero criar uma conta para utilizar a plataforma.

US-003 — Como usuário, quero recuperar minha senha.

US-004 — Como engenheiro, quero cadastrar especialidades para receber conteúdos relevantes.

US-005 — Como usuário, quero configurar minha identidade visual.

US-006 — Como usuário, quero definir meu público-alvo.

US-007 — Como usuário, quero gerar ideias para não depender de criatividade diária.

US-008 — Como usuário, quero gerar legendas para economizar tempo.

US-009 — Como usuário, quero criar carrosséis para explicar assuntos técnicos.

US-010 — Como usuário, quero gerar roteiros para gravar vídeos.

US-011 — Como usuário, quero editar conteúdos.

US-012 — Como usuário, quero salvar rascunhos.

US-013 — Como usuário, quero revisar informações técnicas.

US-014 — Como usuário, quero exportar conteúdos.

US-015 — Como usuário, quero criar planejamento editorial.

US-016 — Como usuário, quero visualizar o calendário.

US-017 — Como usuário, quero reutilizar conteúdos antigos.

US-018 — Como usuário, quero consultar créditos.

US-019 — Como usuário, quero gerenciar assinatura.

US-020 — Como usuário com deficiência, quero acessar as funcionalidades essenciais com tecnologias assistivas.

US-021 — Como usuário, quero preservar minha identidade visual.

US-022 — Como usuário, quero regenerar conteúdos.

US-023 — Como usuário, quero receber mensagens claras de erro.

US-024 — Como usuário, quero solicitar exclusão dos meus dados.

US-025 — Como administrador, quero acompanhar a operação sem acessar indevidamente conteúdos privados.

---

# 9. FLUXOS DO USUÁRIO

## 9.1. Cadastro

1. Acessar Landing Page.
2. Clicar em "Começar".
3. Abrir cadastro.
4. Informar dados.
5. Confirmar.
6. Verificar e-mail.
7. Realizar login.
8. Concluir onboarding.
9. Acessar Dashboard.

## 9.2. Criação de conteúdo

1. Acessar Dashboard.
2. Clicar em "Criar Conteúdo".
3. Escolher formato.
4. Informar tema.
5. Definir objetivo.
6. Confirmar público.
7. Selecionar tom.
8. Gerar com IA.
9. Visualizar resultado.
10. Editar.
11. Revisar tecnicamente.
12. Aprovar.
13. Salvar.
14. Exportar ou adicionar ao calendário.

## 9.3. Criação de carrossel

1. Selecionar carrossel.
2. Informar tema.
3. Escolher quantidade de slides.
4. Escolher formato.
5. Selecionar template.
6. Gerar.
7. Editar.
8. Revisar.
9. Aprovar.
10. Exportar.

## 9.4. Criação de roteiro

1. Selecionar roteiro.
2. Informar tema.
3. Escolher duração.
4. Escolher estilo.
5. Definir objetivo.
6. Gerar.
7. Editar.
8. Revisar.
9. Salvar.
10. Copiar ou adicionar ao calendário.

## 9.5. Planejamento editorial

1. Acessar Planejamento.
2. Escolher período.
3. Definir frequência.
4. Selecionar objetivos.
5. Selecionar pilares.
6. Gerar planejamento.
7. Revisar.
8. Editar.
9. Aprovar.
10. Salvar no calendário.

## 9.6. Revisão técnica

1. Conteúdo gerado.
2. Sistema identifica afirmações técnicas.
3. Sistema apresenta alertas.
4. Usuário verifica informações.
5. Usuário corrige ou remove afirmações inadequadas.
6. Usuário confirma revisão.
7. Sistema registra confirmação.
8. Conteúdo é aprovado.
9. Exportação é liberada.

---

# 10. MAPA DE NAVEGAÇÃO

EngenIA

- Landing Page
  - Apresentação
  - Benefícios
  - Funcionalidades
  - Planos
  - Cadastro
  - Login

- Autenticação
  - Cadastro
  - Login
  - Recuperação de senha
  - Verificação de e-mail

- Onboarding
  - Dados profissionais
  - Especialidades
  - Serviços
  - Público-alvo
  - Objetivos
  - Identidade visual

- Dashboard
  - Resumo
  - Criar conteúdo
  - Conteúdos recentes
  - Próximas publicações
  - Créditos

- Criar Conteúdo
  - Ideias
  - Legendas
  - Carrosséis
  - Roteiros

- Editor
  - Conteúdo
  - Templates
  - Identidade visual
  - Revisão
  - Pré-visualização
  - Exportação

- Planejamento
  - Estratégia editorial
  - Pilares
  - Planejamento de 7 dias
  - Planejamento de 15 dias
  - Planejamento de 30 dias

- Calendário
  - Mensal
  - Semanal
  - Publicações
  - Status

- Biblioteca
  - Todos
  - Favoritos
  - Rascunhos
  - Aprovados
  - Arquivados

- Minha Marca
  - Dados profissionais
  - Serviços
  - Público
  - Identidade visual
  - Redes sociais

- Assinatura
  - Plano
  - Créditos
  - Consumo
  - Pagamentos
  - Cancelamento

- Configurações
  - Conta
  - Segurança
  - Privacidade
  - Acessibilidade
  - Exclusão

- Administração
  - Usuários
  - Planos
  - Consumo de IA
  - Custos
  - Templates
  - Logs
  - Suporte

## 10.1. Rotas sugeridas

- /
- /login
- /cadastro
- /recuperar-senha
- /onboarding
- /app
- /app/criar
- /app/criar/ideias
- /app/criar/legenda
- /app/criar/carrossel
- /app/criar/roteiro
- /app/editor/:id
- /app/planejamento
- /app/calendario
- /app/biblioteca
- /app/marca
- /app/assinatura
- /app/configuracoes
- /admin

---

# 11. DESIGN UNIVERSAL E ACESSIBILIDADE

O EngenIA deverá seguir os sete princípios do Design Universal e os critérios aplicáveis da WCAG 2.2 AA.

## 11.1. Uso equitativo

As funcionalidades essenciais deverão ser utilizáveis por pessoas com diferentes capacidades.

## 11.2. Flexibilidade

Permitir uso por mouse, teclado, toque e leitores de tela.

## 11.3. Uso simples

- Navegação previsível.
- Linguagem clara.
- Fluxos guiados.
- Botões identificáveis.

## 11.4. Informação perceptível

- Contraste adequado.
- Feedback textual.
- Mensagens de erro.
- Indicadores de carregamento.

## 11.5. Tolerância ao erro

- Confirmação de exclusão.
- Desfazer.
- Refazer.
- Salvamento automático.
- Recuperação de rascunhos.

## 11.6. Baixo esforço físico

- Reduzir digitação repetitiva.
- Preencher campos com informações do perfil.
- Oferecer atalhos.

## 11.7. Dimensões adequadas

- Layout responsivo.
- Áreas de toque confortáveis.
- Controles com espaçamento adequado.

## 11.8. Critérios técnicos

- Contraste mínimo de 4,5:1 para texto normal.
- Contraste mínimo de 3:1 para texto grande e componentes relevantes.
- Navegação por teclado.
- Foco visível.
- Compatibilidade com leitores de tela.
- Ampliação de 200%.
- Reflow em largura equivalente a 320 CSS px, respeitadas as exceções aplicáveis.
- Labels associados aos formulários.
- Erros identificados.
- Texto alternativo para imagens informativas.
- Respeito à preferência por movimento reduzido.
- Alternativas ao arrastar e soltar.

## 11.9. Acessibilidade dos conteúdos gerados

O editor deverá oferecer:

- Verificação de contraste.
- Aviso de fontes pequenas.
- Sugestão de texto alternativo.
- Aviso de excesso de texto.
- Orientações sobre legendas de vídeos.

---

# 12. MODELO DE DADOS

Utilizar PostgreSQL com autenticação gerenciada, armazenamento de arquivos e políticas de acesso.

A arquitetura deverá ser preparada para múltiplas organizações, mesmo que o MVP permita apenas uma marca por conta.

## 12.1. users

- id: UUID.
- email: VARCHAR(255), único.
- full_name: VARCHAR(120).
- auth_provider_id: TEXT.
- status: ENUM.
- locale: VARCHAR(10).
- timezone: VARCHAR(64).
- created_at: TIMESTAMPTZ.
- updated_at: TIMESTAMPTZ.

## 12.2. organizations

- id: UUID.
- name: VARCHAR(120).
- owner_user_id: UUID.
- type: ENUM.
- status: ENUM.
- created_at: TIMESTAMPTZ.

## 12.3. organization_members

- id: UUID.
- organization_id: UUID.
- user_id: UUID.
- role: ENUM.
- status: ENUM.
- joined_at: TIMESTAMPTZ.

## 12.4. brand_profiles

- id: UUID.
- organization_id: UUID.
- display_name: VARCHAR(120).
- professional_name: VARCHAR(120).
- crea_number: VARCHAR(40).
- crea_state: CHAR(2).
- specialties: JSONB.
- services: JSONB.
- audience: JSONB.
- marketing_goals: JSONB.
- communication_tone: TEXT.
- city: VARCHAR(120).
- state: CHAR(2).
- instagram_handle: VARCHAR(100).
- whatsapp_number: VARCHAR(20).
- logo_asset_id: UUID.
- primary_color: CHAR(7).
- secondary_color: CHAR(7).
- updated_at: TIMESTAMPTZ.

## 12.5. contents

- id: UUID.
- organization_id: UUID.
- brand_profile_id: UUID.
- created_by: UUID.
- title: VARCHAR(200).
- format: ENUM.
- editorial_pillar: VARCHAR(40).
- objective: VARCHAR(60).
- status: ENUM.
- current_version_id: UUID.
- technical_review_status: ENUM.
- created_at: TIMESTAMPTZ.
- updated_at: TIMESTAMPTZ.
- deleted_at: TIMESTAMPTZ.

## 12.6. content_versions

- id: UUID.
- content_id: UUID.
- version_number: INTEGER.
- payload: JSONB.
- source: ENUM.
- created_by: UUID.
- created_at: TIMESTAMPTZ.

## 12.7. content_slides

- id: UUID.
- content_version_id: UUID.
- position: INTEGER.
- headline: TEXT.
- body: TEXT.
- layout_json: JSONB.
- background_asset_id: UUID.

## 12.8. assets

- id: UUID.
- organization_id: UUID.
- storage_key: TEXT.
- original_filename: TEXT.
- mime_type: VARCHAR(100).
- size_bytes: BIGINT.
- width: INTEGER.
- height: INTEGER.
- alt_text: TEXT.
- created_at: TIMESTAMPTZ.

## 12.9. generation_jobs

- id: UUID.
- organization_id: UUID.
- content_id: UUID.
- requested_by: UUID.
- generation_type: ENUM.
- input_json: JSONB.
- output_json: JSONB.
- model_id: VARCHAR(100).
- prompt_version: VARCHAR(40).
- status: ENUM.
- error_code: VARCHAR(80).
- estimated_cost: NUMERIC.
- actual_cost: NUMERIC.
- created_at: TIMESTAMPTZ.
- completed_at: TIMESTAMPTZ.

## 12.10. calendar_entries

- id: UUID.
- organization_id: UUID.
- content_id: UUID.
- planned_at: TIMESTAMPTZ.
- channel: ENUM.
- status: ENUM.
- notes: TEXT.

## 12.11. plans

- id.
- name.
- monthly_price.
- annual_price.
- currency.
- limits_json.
- is_active.
- created_at.

## 12.12. subscriptions

- id.
- organization_id.
- plan_id.
- provider.
- provider_subscription_id.
- status.
- current_period_start.
- current_period_end.
- cancel_at_period_end.

## 12.13. usage_ledger

- id.
- organization_id.
- generation_job_id.
- operation_type.
- units.
- billing_period.
- status.
- created_at.

## 12.14. technical_reviews

- id.
- content_version_id.
- reviewer_user_id.
- claims_json.
- status.
- confirmed_at.
- review_notes.

## 12.15. audit_logs

- id.
- organization_id.
- actor_user_id.
- action.
- resource_type.
- resource_id.
- metadata_json.
- created_at.

## 12.16. Regras de integridade

- Isolamento por organização.
- Row Level Security quando compatível.
- Validação de permissões no backend.
- Chaves estrangeiras.
- Índices.
- Proteção de dados pessoais.
- Versionamento.
- Controle de concorrência.
- Prevenção de consumo duplicado de créditos.

---

# 13. ARQUITETURA TÉCNICA

## 13.1. Stack recomendada

- React.
- TypeScript.
- Tailwind CSS.
- Componentes acessíveis.
- PostgreSQL.
- Autenticação gerenciada.
- Object Storage.
- API de IA.
- Funções server-side.
- Processamento assíncrono.
- Gateway de pagamento compatível com o Brasil.

A implementação deverá aproveitar as integrações disponíveis no Lovable.

## 13.2. Frontend

Organizar por módulos:

- Authentication.
- Onboarding.
- Dashboard.
- Content Generation.
- Editor.
- Planning.
- Calendar.
- Library.
- Brand.
- Billing.
- Settings.
- Administration.

## 13.3. Backend

Responsável por:

- Autenticação.
- Autorização.
- Persistência.
- Integração com IA.
- Créditos.
- Exportação.
- Assinaturas.
- Auditoria.

## 13.4. Integração com IA

Enviar contexto estruturado contendo:

- Especialidade.
- Serviços.
- Público.
- Objetivo.
- Tom.
- Formato.
- Tema.
- Restrições técnicas.
- Configurações editoriais.

Exigir respostas em JSON estruturado, validado por schema.

## 13.5. Módulos de IA

1. Contexto profissional.
2. Estratégia editorial.
3. Geração.
4. Validação.
5. Revisão humana.
6. Renderização.

## 13.6. Estados de geração

- queued.
- running.
- completed.
- failed.
- cancelled.

## 13.7. Tratamento de erros

- Mensagens claras.
- Preservação das entradas.
- Nova tentativa.
- Registro de erro.
- Prevenção de cobrança indevida.
- Proteção dos conteúdos salvos.

---

# 14. SEGURANÇA, PRIVACIDADE E LGPD

## 14.1. Segurança

- HTTPS em produção.
- Autenticação segura.
- Controle de acesso.
- Isolamento entre organizações.
- Proteção de chaves.
- Validação de entradas.
- Rate limiting.
- Upload seguro.
- Logs.
- Backups.
- Verificação de webhooks.
- Proteção de sessões.

## 14.2. LGPD

- Política de privacidade.
- Termos de uso.
- Definição de finalidades e bases legais.
- Minimização de dados.
- Solicitações de titulares.
- Exclusão conforme regras aplicáveis.
- Retenção.
- Controle de acesso.
- Resposta a incidentes.
- Avaliação de fornecedores.

## 14.3. Proteção de arquivos

Proteger:

- Logomarcas.
- Imagens.
- Projetos.
- Conteúdos.
- Informações profissionais.
- Dados de assinatura.

---

# 15. REQUISITOS NÃO FUNCIONAIS

RNF-001 — Performance: meta de LCP p75 de até 2,5 segundos nas páginas principais, sob condições de teste definidas.

RNF-002 — Responsividade: funcionamento em desktop, tablet e smartphone.

RNF-003 — Disponibilidade: meta de 99,5% ao mês.

RNF-004 — Escalabilidade: processamento assíncrono de gerações quando necessário.

RNF-005 — Manutenibilidade: código modular, tipado e reutilizável.

RNF-006 — Observabilidade: monitoramento de erros, latência, IA, custos e exportações.

RNF-007 — Compatibilidade: versões recentes de Chrome, Edge, Firefox e Safari.

RNF-008 — Acessibilidade: critérios aplicáveis WCAG 2.2 AA.

RNF-009 — Integridade: preservação de dados e versões.

RNF-010 — Recuperação: backup e restauração testados.

RNF-011 — Exportação: arquivos sem cortes ou distorções.

RNF-012 — Custos: monitoramento de consumo de IA por operação.

---

# 16. CRITÉRIOS GERAIS DE ACEITE

O sistema será considerado funcional quando:

1. O usuário conseguir criar conta.
2. Conseguir concluir onboarding.
3. Conseguir configurar a marca.
4. Conseguir gerar ideias.
5. Conseguir gerar legendas.
6. Conseguir criar carrosséis.
7. Conseguir gerar roteiros.
8. Conseguir editar conteúdos.
9. Conseguir salvar projetos.
10. Conseguir revisar informações técnicas.
11. Conseguir aprovar conteúdos.
12. Conseguir exportar arquivos.
13. Conseguir organizar publicações.
14. Conseguir acessar conteúdos antigos.
15. Conseguir consultar créditos.
16. Conseguir gerenciar assinatura.
17. Conseguir utilizar a plataforma no smartphone.
18. Conseguir navegar pelos fluxos essenciais com teclado.
19. Não conseguir acessar dados de terceiros sem autorização.
20. Receber mensagens claras em situações de erro.

---

# 17. MVP — PRODUTO MÍNIMO VIÁVEL

## 17.1. Objetivo do MVP

Desenvolver a primeira versão funcional e comercializável do EngenIA.

O MVP deverá permitir o ciclo completo:

Cadastro → Onboarding → Personalização → Geração com IA → Edição → Revisão Técnica → Aprovação → Salvamento → Exportação.

O MVP deverá validar:

- Interesse do mercado.
- Utilidade do produto.
- Qualidade dos conteúdos.
- Facilidade de uso.
- Frequência de utilização.
- Disposição de pagamento.
- Sustentabilidade dos custos de IA.

## 17.2. Funcionalidades obrigatórias

### MVP-001 — Autenticação

- Cadastro.
- Login.
- Logout.
- Recuperação de senha.
- Proteção de rotas.

### MVP-002 — Onboarding

- Dados profissionais.
- Especialidades.
- Serviços.
- Público.
- Objetivos.
- Tom.
- Identidade visual.

### MVP-003 — Dashboard

- Saudação.
- Ações rápidas.
- Conteúdos recentes.
- Indicadores.
- Créditos.

### MVP-004 — Gerador de ideias

- IA funcional.
- Personalização.
- Salvamento.
- Favoritos.
- Transformação em outros formatos.

### MVP-005 — Gerador de legendas

- Geração.
- Edição.
- Regeneração.
- Cópia.
- Salvamento.

### MVP-006 — Gerador de carrosséis

- 3 a 10 slides.
- Templates.
- Edição.
- Identidade visual.
- Exportação.

### MVP-007 — Gerador de roteiros

- Durações configuráveis.
- Estrutura por cenas.
- Narração.
- CTA.
- Edição.
- Salvamento.

### MVP-008 — Editor visual

- Templates estruturados.
- Edição de textos.
- Cores.
- Fontes.
- Imagens.
- Logomarca.
- Pré-visualização.
- Salvamento.

### MVP-009 — Revisão técnica

- Alertas.
- Identificação de afirmações técnicas.
- Edição.
- Confirmação.
- Aprovação.

### MVP-010 — Biblioteca

- Conteúdos salvos.
- Pesquisa.
- Filtros.
- Favoritos.
- Edição.
- Exclusão.

### MVP-011 — Planejamento e calendário

- Planejamento editorial de 7, 15 e 30 dias.
- Calendário mensal.
- Calendário semanal.
- Adição manual.
- Alteração de datas.
- Status de publicação.

### MVP-012 — Exportação

- Copiar textos.
- PNG.
- ZIP.
- TXT.

### MVP-013 — Assinaturas

- Planos configuráveis.
- Controle de créditos.
- Histórico de consumo.
- Integração de cobrança.
- Cancelamento.

### MVP-014 — Segurança e acessibilidade

- Controle de acesso.
- Isolamento de dados.
- Proteção de arquivos.
- Privacidade.
- Navegação por teclado.
- Compatibilidade com leitores de tela.
- Responsividade.

## 17.3. Funcionalidades fora do MVP

Não implementar na primeira versão:

- Publicação automática no Instagram.
- Agendamento automático via APIs de redes sociais.
- Analytics de redes sociais.
- Geração de vídeos completos.
- Editor avançado de vídeo.
- Geração avançada de imagens com IA.
- Aplicativos nativos Android e iOS.
- Múltiplas marcas por conta.
- Colaboração em tempo real.
- Aprovação por equipes externas.
- Marketplace de templates.
- Integração com CRM.
- Automação de WhatsApp.
- Recomendações baseadas em métricas reais de redes sociais.

## 17.4. Ordem de implementação

**Fase 1 — Fundação**

- Estrutura do projeto.
- Design system.
- Autenticação.
- Banco de dados.
- Permissões.
- Onboarding.
- Dashboard.

**Fase 2 — Inteligência Artificial**

- Integração segura com IA.
- Contexto profissional.
- Gerador de ideias.
- Gerador de legendas.
- Gerador de roteiros.
- Gerador de carrosséis.

**Fase 3 — Criação e edição**

- Templates.
- Editor visual.
- Biblioteca.
- Versionamento.
- Revisão técnica.

**Fase 4 — Organização**

- Planejamento editorial.
- Calendário.
- Exportação.

**Fase 5 — Monetização**

- Planos.
- Créditos.
- Pagamentos.
- Assinaturas.

**Fase 6 — Qualidade e lançamento**

- Testes funcionais.
- Testes de segurança.
- Testes de acessibilidade.
- Testes de responsividade.
- Testes de performance.
- Validação com usuários.

## 17.5. Critérios de conclusão do MVP

O MVP estará pronto para lançamento quando:

- Os fluxos obrigatórios estiverem funcionais.
- A autenticação estiver segura.
- O onboarding persistir corretamente.
- A IA gerar respostas estruturadas.
- Os conteúdos puderem ser editados.
- Os carrosséis puderem ser exportados.
- A revisão técnica estiver implementada.
- A biblioteca funcionar.
- O planejamento e o calendário funcionarem.
- Os créditos forem contabilizados corretamente.
- A cobrança e o cancelamento estiverem operacionais.
- Os dados estiverem protegidos.
- A interface funcionar em desktop e smartphone.
- Os fluxos essenciais atenderem aos requisitos de acessibilidade.
- Não existirem falhas críticas conhecidas sem mitigação.

## 17.6. Resultado esperado

Ao concluir o MVP, um engenheiro civil deverá conseguir entrar no EngenIA, configurar seu perfil profissional e produzir uma publicação completa com auxílio de Inteligência Artificial.

O usuário deverá conseguir:

1. Escolher um tema.
2. Gerar ideias.
3. Criar legenda, carrossel ou roteiro.
4. Personalizar o conteúdo.
5. Revisar informações técnicas.
6. Aprovar a publicação.
7. Salvar o projeto.
8. Exportar o material.
9. Organizar a publicação no calendário.

A experiência deverá transmitir a percepção de uma plataforma especializada em engenharia civil, com foco em profissionalismo, praticidade e posicionamento digital.
## O endereço da aplicação publicada
https://engenia-digital-authority.lovable.app/
## Prints do app
<img width="1557" height="770" alt="image" src="https://github.com/user-attachments/assets/3b2354c8-9ce0-4d9f-abe5-29c297f48082" />
<img width="1893" height="796" alt="image" src="https://github.com/user-attachments/assets/003669b6-5b54-419c-b7a4-dade50ddd954" />

