# 🎓 EDUBOT - Totem Inteligente Acessível para Ambientes Educacionais

**Challenge FlexMedia - Sprint 1**

**Tecnólogo em Inteligência Artificial - FIAP**

*"Democratizando o acesso à informação educacional através da IA"*

---

## 👤 Informações do Projeto

**Aluno:** Fabrício Mouzer Brito  
**RM:** 566777  
**E-mail:** fabriciomouzer@hotmail.com  
**Turma:** R  
**Data:** Outubro de 2025

---

## 📋 Índice

1. [Visão Geral](#visão-geral)
2. [Justificativa do Problema](#justificativa-do-problema)
3. [Descrição da Solução](#descrição-da-solução)
4. [Funcionalidades Principais](#funcionalidades-principais)
5. [Tecnologias Utilizadas](#tecnologias-utilizadas)
6. [Arquitetura da Solução](#arquitetura-da-solução)
7. [Estratégia de Coleta de Dados](#estratégia-de-coleta-de-dados)
8. [Segurança e Privacidade](#segurança-e-privacidade)
9. [Acessibilidade Universal](#acessibilidade-universal)
10. [Integração WhatsApp](#integração-whatsapp)
11. [Plano de Desenvolvimento](#plano-de-desenvolvimento)
12. [Casos de Uso](#casos-de-uso)
13. [Diferenciais Competitivos](#diferenciais-competitivos)
14. [Referências](#referências)

---

## 🎯 Visão Geral

O **EDUBOT** é um totem inteligente equipado com Inteligência Artificial, projetado especificamente para ambientes educacionais como escolas, faculdades e bibliotecas. A solução combina tecnologias de ponta com foco total em acessibilidade universal, permitindo que todos os estudantes, independentemente de suas capacidades físicas ou cognitivas, tenham acesso facilitado a informações acadêmicas, horários, avisos e suporte educacional personalizado.

O projeto atende à crescente demanda por soluções tecnológicas inclusivas no ambiente educacional, alinhando-se com a Lei Brasileira de Inclusão (Lei 13.146/2015) e a Lei Geral de Proteção de Dados (LGPD - Lei 13.709/2018).

---

## 📊 Justificativa do Problema

### Contexto Atual

O ambiente educacional brasileiro enfrenta diversos desafios relacionados ao acesso à informação e à inclusão de estudantes com deficiência:

**1. Barreiras de Comunicação**

Estudantes frequentemente enfrentam dificuldades para obter informações básicas como horários de aulas, avisos importantes, localização de salas e serviços acadêmicos. Os métodos tradicionais de comunicação (murais físicos, e-mails institucionais) são ineficientes e não alcançam todos os públicos de forma equitativa.

**2. Exclusão de Pessoas com Deficiência**

Segundo o Censo da Educação Superior 2022 (INEP), apenas 0,56% dos estudantes universitários brasileiros declaram ter alguma deficiência, um número muito inferior à proporção de PcD na população geral (8,4% segundo IBGE 2019). Isso evidencia barreiras sistêmicas de acesso à informação e aos serviços educacionais.

**3. Sobrecarga das Secretarias Acadêmicas**

Secretarias e bibliotecas recebem diariamente centenas de consultas repetitivas sobre horários, prazos, localização de recursos e procedimentos administrativos. Isso sobrecarrega os funcionários e gera filas, reduzindo a eficiência do atendimento.

**4. Falta de Personalização**

Cada estudante tem necessidades específicas de aprendizado e comunicação. Sistemas tradicionais não oferecem personalização baseada no perfil, histórico ou preferências individuais, resultando em experiências genéricas e pouco eficazes.

**5. Dificuldade de Coleta de Feedback**

Instituições educacionais têm dificuldade em coletar feedback estruturado dos estudantes sobre serviços, infraestrutura e qualidade do ensino, perdendo oportunidades valiosas de melhoria contínua.

### Impacto do Problema

- **Exclusão educacional:** Estudantes com deficiência enfrentam barreiras adicionais para acessar informações básicas
- **Ineficiência operacional:** Tempo desperdiçado em consultas repetitivas que poderiam ser automatizadas
- **Experiência do estudante comprometida:** Frustração e desmotivação devido à dificuldade de acesso à informação
- **Perda de dados valiosos:** Falta de métricas sobre uso de serviços e necessidades dos estudantes

### Oportunidade

A implementação de um totem inteligente com IA e foco em acessibilidade representa uma oportunidade única de transformar a experiência educacional, tornando-a mais inclusiva, eficiente e centrada no estudante. A solução pode ser replicada em milhares de instituições de ensino em todo o Brasil, gerando impacto social significativo.

---

## 💡 Descrição da Solução

### O que é o EDUBOT?

O **EDUBOT** é um totem físico interativo equipado com:

- **Display touchscreen** de alta resolução (24 polegadas)
- **Câmera ESP32-CAM** para reconhecimento de QR Code e detecção de presença
- **Sensores de proximidade** para ativação automática
- **Alto-falantes** para feedback de áudio e leitura de tela
- **Botões táteis** com identificação em Braille
- **Conectividade WiFi** para integração com sistemas em nuvem
- **Processador embarcado** (Raspberry Pi 4 ou similar) para processamento local

### Como Funciona?

**Fluxo de Interação Básico:**

1. **Detecção de Presença:** Quando um estudante se aproxima, sensores detectam a presença e ativam o totem
2. **Identificação (Opcional):** Estudante pode escanear QR Code do cartão estudantil para personalização
3. **Escolha do Modo de Interação:** Interface oferece opções de interação por toque, voz ou QR Code
4. **Consulta:** Estudante faz perguntas ou navega por menus para acessar informações
5. **Resposta Inteligente:** IA processa a consulta e fornece resposta personalizada em múltiplos formatos
6. **Feedback:** Sistema coleta feedback opcional sobre a qualidade da interação
7. **Integração WhatsApp:** Estudante pode optar por continuar a conversa via WhatsApp

### Diferenciais Tecnológicos

**Inteligência Artificial Conversacional**

O EDUBOT utiliza modelos de linguagem avançados (OpenAI GPT-4 ou Gemini 2.5 Flash) para compreender perguntas em linguagem natural, contexto e intenção do usuário. Isso permite interações fluidas e naturais, sem necessidade de comandos específicos ou navegação complexa em menus.

**Acessibilidade Total**

Diferentemente de soluções convencionais, o EDUBOT foi projetado desde o início para ser 100% acessível:

- **Deficiência Visual:** Leitura de tela completa, navegação por voz, instruções em Braille, alto contraste
- **Deficiência Auditiva:** Tradução automática em Libras (VLibras), legendas em tempo real, feedback visual
- **Deficiência Cognitiva:** Interface simplificada, linguagem clara, tempo de resposta ajustável
- **Mobilidade Reduzida:** Altura ajustável, botões grandes, ativação por voz

**Integração WhatsApp**

Após a interação no totem, o estudante pode optar por receber um link via QR Code para continuar a conversa pelo WhatsApp. Isso permite:

- Acompanhamento de solicitações
- Recebimento de lembretes e notificações
- Consultas futuras sem necessidade de estar fisicamente no totem
- Histórico de conversas preservado

**Coleta Inteligente de Dados**

O sistema coleta dados anonimizados sobre:

- Horários de maior uso
- Tipos de consultas mais frequentes
- Recursos de acessibilidade mais utilizados
- Satisfação dos usuários (NPS)
- Tempo médio de interação

Esses dados geram insights valiosos para a gestão educacional tomar decisões baseadas em evidências.

---

## ⚙️ Funcionalidades Principais

### 1. Consulta de Informações Acadêmicas

**Descrição:** Estudantes podem consultar horários de aulas, grades curriculares, calendário acadêmico, prazos de matrícula e outras informações institucionais.

**Exemplo de Uso:**
- "Qual o horário da aula de Inteligência Artificial hoje?"
- "Quando é o prazo de matrícula para o próximo semestre?"
- "Onde fica a sala 305?"

### 2. Avisos e Notificações

**Descrição:** Exibição de avisos importantes da instituição, eventos acadêmicos, palestras, workshops e oportunidades de estágio.

**Exemplo de Uso:**
- "Há algum aviso importante para mim hoje?"
- "Quais eventos acontecem esta semana?"

### 3. Localização e Navegação

**Descrição:** Orientação sobre localização de salas, laboratórios, bibliotecas, secretarias e outros espaços do campus.

**Exemplo de Uso:**
- "Como chego à biblioteca?"
- "Onde fica o laboratório de informática?"

### 4. Suporte Acadêmico

**Descrição:** Informações sobre serviços de apoio ao estudante, tutoria, orientação acadêmica, suporte psicológico e programas de assistência.

**Exemplo de Uso:**
- "Como solicitar atendimento psicológico?"
- "Existe programa de monitoria para matemática?"

### 5. Biblioteca Digital

**Descrição:** Consulta ao acervo da biblioteca, disponibilidade de livros, reserva de materiais e acesso a recursos digitais.

**Exemplo de Uso:**
- "O livro 'Inteligência Artificial' está disponível?"
- "Como faço para reservar um livro?"

### 6. Feedback e Pesquisas

**Descrição:** Coleta de feedback dos estudantes sobre serviços, infraestrutura, qualidade das aulas e experiência geral.

**Exemplo de Uso:**
- "Como você avalia o atendimento da secretaria?"
- "Participe da pesquisa de satisfação do semestre"

### 7. Integração WhatsApp

**Descrição:** Continuidade da conversa via WhatsApp para acompanhamento de solicitações e recebimento de notificações personalizadas.

**Exemplo de Uso:**
- "Quero receber lembretes de prazos no WhatsApp"
- "Continue esta conversa no meu celular"

### 8. Modo Acessibilidade

**Descrição:** Ativação de recursos específicos de acessibilidade conforme necessidade do usuário.

**Exemplo de Uso:**
- "Ativar leitura de tela"
- "Ativar tradução em Libras"
- "Aumentar contraste"

---

## 🛠️ Tecnologias Utilizadas

### Hardware

**Componente Principal: ESP32-CAM**

O ESP32-CAM é um microcontrolador com câmera integrada, WiFi e Bluetooth, ideal para projetos IoT. No EDUBOT, ele é responsável por:

- Captura e reconhecimento de QR Codes
- Detecção de presença através da câmera
- Comunicação com o servidor backend via WiFi
- Baixo custo e consumo energético

**Especificações:**
- Processador: Xtensa dual-core 32-bit LX6
- Memória: 520 KB SRAM
- WiFi: 802.11 b/g/n
- Câmera: OV2640 (2MP)

**Sensor de Presença PIR (Passive Infrared)**

Detecta movimento e presença humana através de radiação infravermelha, ativando o totem automaticamente quando alguém se aproxima.

**Especificações:**
- Alcance: 3-7 metros
- Ângulo de detecção: 120°
- Consumo: 65mA

**Display Touchscreen**

Tela sensível ao toque de 24 polegadas para interação visual e tátil.

**Especificações:**
- Resolução: 1920x1080 (Full HD)
- Tecnologia: Capacitivo multi-toque
- Brilho: 300 cd/m²
- Contraste: 1000:1

**Alto-falantes**

Sistema de áudio estéreo para feedback sonoro e leitura de tela.

**Especificações:**
- Potência: 2x 10W
- Resposta de frequência: 80Hz - 20kHz

**Botões Táteis com Braille**

Botões físicos com identificação em Braille para navegação sem visão.

**Processador Embarcado: Raspberry Pi 4**

Computador de placa única que executa o sistema operacional e aplicações principais.

**Especificações:**
- CPU: Quad-core ARM Cortex-A72 (1.5GHz)
- RAM: 4GB LPDDR4
- Conectividade: WiFi 802.11ac, Bluetooth 5.0, Gigabit Ethernet
- Portas: 2x USB 3.0, 2x USB 2.0, HDMI

### Software e Linguagens

**Backend: Python 3.11**

Python foi escolhido como linguagem principal devido à:

- Vasta biblioteca de IA e Machine Learning (TensorFlow, PyTorch, scikit-learn)
- Facilidade de integração com APIs de IA (OpenAI, Google)
- Sintaxe clara e legível (ideal para manutenção)
- Grande comunidade e documentação

**Framework Backend: FastAPI**

FastAPI é um framework web moderno e de alta performance para construção de APIs.

**Vantagens:**
- Performance comparável a Node.js e Go
- Validação automática de dados com Pydantic
- Documentação automática (Swagger/OpenAPI)
- Suporte nativo a async/await

**Automação de Workflows: N8N**

N8N é uma ferramenta de automação visual que permite criar workflows complexos sem código.

**Uso no EDUBOT:**
- Integração entre diferentes sistemas (backend, WhatsApp, banco de dados)
- Automação de notificações e lembretes
- Processamento de webhooks
- Orquestração de tarefas agendadas

### Inteligência Artificial

**Modelo de Linguagem: OpenAI GPT-4**

GPT-4 é o modelo de linguagem mais avançado da OpenAI, capaz de compreender e gerar texto em linguagem natural com alta qualidade.

**Uso no EDUBOT:**
- Processamento de perguntas em linguagem natural
- Geração de respostas contextualizadas e personalizadas
- Compreensão de intenção e contexto
- Adaptação de linguagem ao perfil do usuário

**Alternativa: Gemini 2.5 Flash (Google)**

Gemini 2.5 Flash é uma alternativa mais rápida e econômica para casos de uso que não exigem o máximo de capacidade.

**Biblioteca de Processamento de Linguagem Natural: spaCy**

spaCy é usada para pré-processamento de texto, análise morfológica e extração de entidades.

**Uso no EDUBOT:**
- Tokenização e lematização
- Reconhecimento de entidades nomeadas (NER)
- Análise de sentimento
- Classificação de intenção

**Reconhecimento de Voz: Whisper (OpenAI)**

Whisper é um modelo de reconhecimento de fala de código aberto, robusto e multilíngue.

**Uso no EDUBOT:**
- Transcrição de comandos de voz em tempo real
- Suporte a múltiplos idiomas e sotaques
- Alta precisão mesmo em ambientes ruidosos

**Síntese de Voz: Google Text-to-Speech**

Conversão de texto em fala natural para leitura de tela e respostas em áudio.

**Uso no EDUBOT:**
- Leitura de todas as informações exibidas na tela
- Respostas em áudio para usuários com deficiência visual
- Suporte a múltiplas vozes e idiomas

### Banco de Dados

**Banco Principal: Supabase (PostgreSQL)**

Supabase é uma alternativa open-source ao Firebase, baseada em PostgreSQL.

**Vantagens:**
- Banco de dados relacional robusto (PostgreSQL)
- APIs REST e GraphQL automáticas
- Autenticação integrada
- Real-time subscriptions
- Storage para arquivos
- Hospedagem gratuita para desenvolvimento

**Estrutura de Dados:**

```sql
-- Tabela de Usuários
CREATE TABLE usuarios (
    id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    nome VARCHAR(255),
    email VARCHAR(255) UNIQUE,
    telefone VARCHAR(20),
    tipo_usuario VARCHAR(50), -- estudante, professor, funcionario
    preferencias_acessibilidade JSONB,
    created_at TIMESTAMP DEFAULT NOW()
);

-- Tabela de Interações
CREATE TABLE interacoes (
    id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    usuario_id UUID REFERENCES usuarios(id),
    tipo_interacao VARCHAR(50), -- consulta, feedback, navegacao
    conteudo TEXT,
    resposta TEXT,
    duracao_segundos INTEGER,
    recursos_acessibilidade_usados JSONB,
    satisfacao INTEGER, -- 1-5
    created_at TIMESTAMP DEFAULT NOW()
);

-- Tabela de Avisos
CREATE TABLE avisos (
    id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    titulo VARCHAR(255),
    conteudo TEXT,
    tipo VARCHAR(50), -- academico, evento, urgente
    data_inicio TIMESTAMP,
    data_fim TIMESTAMP,
    publico_alvo VARCHAR(100), -- todos, estudantes, professores
    created_at TIMESTAMP DEFAULT NOW()
);

-- Tabela de Horários
CREATE TABLE horarios (
    id UUID PRIMARY KEY DEFAULT uuid_generate_v4(),
    curso VARCHAR(100),
    disciplina VARCHAR(100),
    professor VARCHAR(255),
    sala VARCHAR(50),
    dia_semana INTEGER, -- 0-6
    horario_inicio TIME,
    horario_fim TIME,
    semestre VARCHAR(20)
);
```

**Cache: Redis**

Redis é usado para cache de respostas frequentes e sessões de usuário.

**Uso no EDUBOT:**
- Cache de consultas frequentes (horários, avisos)
- Sessões de usuário temporárias
- Rate limiting de APIs
- Fila de processamento de tarefas

### Cloud e Infraestrutura

**Plataforma Cloud: AWS (Amazon Web Services)**

AWS foi escolhida pela robustez, escalabilidade e variedade de serviços.

**Serviços Utilizados:**

**1. AWS EC2 (Elastic Compute Cloud)**
- Hospedagem do backend FastAPI
- Instância: t3.medium (2 vCPUs, 4GB RAM)
- Sistema operacional: Ubuntu 22.04 LTS

**2. AWS S3 (Simple Storage Service)**
- Armazenamento de arquivos estáticos
- Backup de dados
- Logs de sistema

**3. AWS CloudWatch**
- Monitoramento de métricas
- Logs centralizados
- Alertas de performance

**4. AWS Lambda**
- Processamento serverless de tarefas assíncronas
- Geração de relatórios
- Envio de notificações

**Containerização: Docker**

Toda a aplicação é containerizada para facilitar deployment e escalabilidade.

**Containers:**
- Backend FastAPI
- N8N
- Redis
- Nginx (reverse proxy)

**Orquestração: Docker Compose**

Docker Compose gerencia múltiplos containers e suas dependências.

### Frontend (Interface do Totem)

**Framework: React.js 18**

React foi escolhido pela componentização, performance e ecossistema maduro.

**Biblioteca de UI: TailwindCSS**

TailwindCSS permite criar interfaces responsivas e acessíveis rapidamente.

**Gerenciamento de Estado: Zustand**

Zustand é uma biblioteca leve para gerenciamento de estado global.

**Acessibilidade: React Aria**

React Aria fornece componentes acessíveis seguindo padrões WCAG 2.1 AA.

**Síntese de Voz: Web Speech API**

API nativa do navegador para reconhecimento e síntese de voz.

### Integração WhatsApp

**API: WhatsApp Business API**

Integração oficial do WhatsApp para empresas e instituições.

**Provedor: Twilio**

Twilio fornece infraestrutura para envio e recebimento de mensagens WhatsApp.

**Funcionalidades:**
- Envio de mensagens de texto
- Envio de imagens e documentos
- Templates de mensagens aprovados
- Webhooks para recebimento de mensagens

### Segurança

**Criptografia de Dados: TLS 1.3**

Todas as comunicações entre totem e servidor são criptografadas com TLS 1.3.

**Criptografia de Dados em Repouso: AES-256**

Dados sensíveis no banco de dados são criptografados com AES-256.

**Autenticação: OAuth 2.0**

Autenticação de usuários e integração com sistemas institucionais via OAuth 2.0.

**Gestão de Segredos: AWS Secrets Manager**

Chaves de API e credenciais são armazenadas de forma segura no AWS Secrets Manager.

**Firewall: AWS Security Groups**

Regras de firewall restringem acesso apenas a portas e IPs autorizados.

### Ferramentas de Desenvolvimento

**Controle de Versão: Git + GitHub**

Todo o código é versionado com Git e hospedado em repositório privado no GitHub.

**CI/CD: GitHub Actions**

Automação de testes, build e deploy através de GitHub Actions.

**Testes: pytest**

Framework de testes para Python, garantindo qualidade do código.

**Documentação: Swagger/OpenAPI**

Documentação automática de APIs gerada pelo FastAPI.

**Monitoramento: Sentry**

Rastreamento de erros em tempo real e alertas de problemas.

---

## 🏗️ Arquitetura da Solução

### Visão Geral da Arquitetura

O EDUBOT segue uma arquitetura em camadas, separando responsabilidades e facilitando manutenção e escalabilidade.

```
┌─────────────────────────────────────────────────────────────┐
│                     CAMADA DE APRESENTAÇÃO                   │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │   Display    │  │  Alto-falante│  │    Botões    │      │
│  │  Touchscreen │  │              │  │   Táteis     │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                   CAMADA DE INTERFACE (Frontend)             │
│  ┌──────────────────────────────────────────────────────┐   │
│  │              React.js + TailwindCSS                   │   │
│  │  • Interface Responsiva                               │   │
│  │  • Componentes Acessíveis (React Aria)                │   │
│  │  • Gerenciamento de Estado (Zustand)                  │   │
│  └──────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                   CAMADA DE HARDWARE/IoT                     │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │  ESP32-CAM   │  │  Sensor PIR  │  │ Raspberry Pi │      │
│  │  (QR Code)   │  │  (Presença)  │  │      4       │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                   CAMADA DE APLICAÇÃO (Backend)              │
│  ┌──────────────────────────────────────────────────────┐   │
│  │              FastAPI (Python 3.11)                    │   │
│  │  • APIs RESTful                                       │   │
│  │  • Lógica de Negócio                                  │   │
│  │  • Processamento de Requisições                       │   │
│  └──────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                   CAMADA DE INTELIGÊNCIA ARTIFICIAL          │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │  OpenAI      │  │   Whisper    │  │  Google TTS  │      │
│  │   GPT-4      │  │   (Speech)   │  │   (Voice)    │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                   CAMADA DE DADOS                            │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │  Supabase    │  │    Redis     │  │   AWS S3     │      │
│  │ (PostgreSQL) │  │   (Cache)    │  │  (Storage)   │      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                   CAMADA DE INTEGRAÇÃO                       │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │   WhatsApp   │  │     N8N      │  │  Sistemas    │      │
│  │  Business    │  │ (Automação)  │  │Institucionais│      │
│  └──────────────┘  └──────────────┘  └──────────────┘      │
└─────────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────────┐
│                   CAMADA DE SEGURANÇA                        │
│  ┌──────────────────────────────────────────────────────┐   │
│  │  • TLS 1.3 (Criptografia)                             │   │
│  │  • OAuth 2.0 (Autenticação)                           │   │
│  │  • AES-256 (Dados em Repouso)                         │   │
│  │  • AWS Security Groups (Firewall)                     │   │
│  │  • LGPD Compliance                                    │   │
│  └──────────────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────────────┘
```

### Pipeline de Dados

O fluxo de dados no EDUBOT segue o seguinte pipeline:

**1. COLETA**

```
Estudante → Interface (Toque/Voz/QR Code) → Frontend React
                                                    ↓
                                            Captura de Input
                                                    ↓
                                        Validação e Sanitização
                                                    ↓
                                        Envio para Backend (HTTPS)
```

**2. PROCESSAMENTO**

```
Backend FastAPI ← Requisição HTTPS
        ↓
Autenticação e Autorização
        ↓
Verificação de Cache (Redis)
        ↓
┌───────┴───────┐
│   Cache Hit?  │
└───────┬───────┘
        │
    ┌───┴───┐
    │  Sim  │ → Retorna Resposta em Cache
    └───────┘
        │
    ┌───┴───┐
    │  Não  │ → Processa Nova Requisição
    └───┬───┘
        ↓
Classificação de Intenção (spaCy)
        ↓
Consulta ao Banco de Dados (Supabase)
        ↓
Enriquecimento de Contexto
        ↓
Envio para IA (OpenAI GPT-4)
        ↓
Recebimento de Resposta
        ↓
Pós-processamento e Formatação
        ↓
Armazenamento em Cache (Redis)
        ↓
Registro de Interação (Supabase)
```

**3. ANÁLISE**

```
Dados de Interação (Supabase)
        ↓
Agregação e Análise (AWS Lambda)
        ↓
Geração de Métricas
        ↓
┌────────────────────────────────┐
│  • Horários de maior uso       │
│  • Consultas mais frequentes   │
│  • Recursos de acessibilidade  │
│  • Satisfação (NPS)            │
│  • Tempo médio de interação    │
└────────────────────────────────┘
        ↓
Dashboard de Analytics
```

**4. ARMAZENAMENTO**

```
Dados Estruturados → Supabase (PostgreSQL)
        ↓
Backup Diário → AWS S3
        ↓
Retenção: 2 anos (conforme LGPD)
        ↓
Após 2 anos: Anonimização ou Exclusão
```

**5. VISUALIZAÇÃO**

```
Dashboard Web (Admin)
        ↓
┌────────────────────────────────┐
│  • Gráficos de uso             │
│  • Relatórios de satisfação    │
│  • Análise de acessibilidade   │
│  • Exportação de dados         │
└────────────────────────────────┘
```

### Diagramas de Arquitetura

Os diagramas detalhados estão disponíveis na pasta `docs/diagramas/`:

- **arquitetura-geral.png:** Visão completa do sistema em camadas
- **fluxo-dados.png:** Pipeline detalhado de coleta, processamento e análise
- **pipeline-ia.png:** Fluxo específico de processamento com IA

---

## 📊 Estratégia de Coleta de Dados

### Dados Coletados

O EDUBOT coleta dados estruturados para melhorar a experiência do usuário e fornecer insights para a gestão educacional. Todos os dados são coletados em conformidade com a LGPD.

**1. Dados de Interação**

| Dado | Descrição | Finalidade | Retenção |
|------|-----------|------------|----------|
| **Timestamp** | Data e hora da interação | Análise de horários de pico | 2 anos |
| **Tipo de Consulta** | Categoria da pergunta (horário, aviso, localização) | Identificar demandas mais frequentes | 2 anos |
| **Conteúdo da Pergunta** | Texto ou transcrição da pergunta (anonimizado) | Melhorar respostas da IA | 2 anos |
| **Resposta Fornecida** | Texto da resposta gerada | Auditoria de qualidade | 2 anos |
| **Duração da Interação** | Tempo total em segundos | Otimizar fluxos | 2 anos |
| **Recursos de Acessibilidade Usados** | Lista de recursos ativados (áudio, Libras, etc.) | Melhorar acessibilidade | 2 anos |
| **Satisfação (NPS)** | Nota de 1 a 5 (opcional) | Medir qualidade do serviço | 2 anos |

**2. Dados de Identificação (Opcional)**

| Dado | Descrição | Finalidade | Retenção |
|------|-----------|------------|----------|
| **ID do Estudante** | Código único (via QR Code) | Personalização de respostas | 2 anos |
| **Curso** | Curso do estudante | Contextualizar informações | 2 anos |
| **Semestre** | Período atual | Filtrar horários relevantes | 2 anos |
| **Preferências de Acessibilidade** | Recursos preferidos salvos | Ativar automaticamente | 2 anos |

**3. Dados de Sistema**

| Dado | Descrição | Finalidade | Retenção |
|------|-----------|------------|----------|
| **ID do Totem** | Identificação do dispositivo | Monitorar performance por localização | Indefinido |
| **Status de Hardware** | Funcionamento de sensores e componentes | Manutenção preventiva | 1 ano |
| **Logs de Erro** | Erros de sistema | Debugging e melhorias | 6 meses |
| **Métricas de Performance** | Tempo de resposta, uso de CPU/memória | Otimização de infraestrutura | 3 meses |

### Como os Dados São Coletados

**1. Coleta Automática**

- **Sensores:** ESP32-CAM e sensor PIR detectam presença e ativam o totem
- **Interface:** Todas as interações na tela touchscreen são registradas
- **Voz:** Comandos de voz são transcritos pelo Whisper e armazenados (anonimizados)
- **QR Code:** Escaneamento de cartão estudantil captura ID para personalização (opcional)

**2. Coleta com Consentimento**

- **Identificação:** Estudante escolhe se deseja se identificar via QR Code
- **Feedback:** Ao final da interação, é solicitada avaliação opcional (NPS)
- **WhatsApp:** Estudante opta por fornecer número de telefone para integração

**3. Anonimização**

Dados sensíveis são anonimizados antes do armazenamento:

- **Perguntas:** Remoção de nomes próprios, CPFs, e-mails e outros identificadores
- **IDs:** Uso de hash criptográfico irreversível para IDs de estudantes
- **IPs:** Não são armazenados endereços IP

### Onde os Dados São Armazenados

**Banco de Dados Principal: Supabase (PostgreSQL)**

- Localização: Servidor na região São Paulo (AWS South America)
- Criptografia: AES-256 em repouso, TLS 1.3 em trânsito
- Backup: Diário, armazenado em AWS S3 com criptografia

**Cache: Redis**

- Dados temporários (sessões, cache de consultas)
- Retenção: Máximo 24 horas
- Sem dados sensíveis

**Logs: AWS CloudWatch**

- Logs de sistema e erros
- Retenção: 6 meses
- Acesso restrito a administradores

### Garantia de Privacidade (LGPD)

**Princípios Aplicados:**

**1. Finalidade**

Todos os dados coletados têm finalidade específica e explícita:
- Melhorar a experiência do usuário
- Fornecer insights para gestão educacional
- Garantir funcionamento adequado do sistema

**2. Adequação**

Coleta é compatível com as finalidades informadas e com o contexto educacional.

**3. Necessidade**

Apenas dados estritamente necessários são coletados. Não há coleta excessiva.

**4. Transparência**

Estudantes são informados sobre quais dados são coletados e para quê, através de:
- Aviso na primeira interação
- Política de privacidade acessível no totem
- Opção de não fornecer dados opcionais

**5. Segurança**

Medidas técnicas e administrativas protegem os dados:
- Criptografia (TLS 1.3, AES-256)
- Controle de acesso (OAuth 2.0)
- Firewall (AWS Security Groups)
- Monitoramento contínuo (CloudWatch, Sentry)

**6. Não Discriminação**

Dados não são usados para fins discriminatórios ou abusivos.

**7. Responsabilização**

A instituição é responsável pela proteção dos dados e deve demonstrar conformidade.

**Direitos dos Titulares:**

Estudantes têm direito a:

- **Confirmação de Tratamento:** Saber se seus dados estão sendo tratados
- **Acesso:** Obter cópia de seus dados
- **Correção:** Corrigir dados incompletos ou desatualizados
- **Anonimização/Bloqueio/Eliminação:** Solicitar anonimização, bloqueio ou exclusão
- **Portabilidade:** Receber dados em formato estruturado
- **Revogação de Consentimento:** Retirar consentimento a qualquer momento

**Exercício de Direitos:**

Solicitações podem ser feitas através de:
- Interface do totem (menu "Privacidade")
- E-mail institucional: privacidade@instituicao.edu.br
- Presencialmente na secretaria

Prazo de resposta: 15 dias úteis (conforme LGPD Art. 18 §3º)

---

## 🔒 Segurança e Privacidade

### Princípios de Segurança

O EDUBOT implementa segurança em múltiplas camadas (Defense in Depth):

**1. Segurança de Rede**

- **Firewall:** AWS Security Groups restringem acesso apenas a portas necessárias (443 HTTPS, 22 SSH)
- **VPC:** Virtual Private Cloud isola recursos na nuvem
- **DDoS Protection:** AWS Shield protege contra ataques de negação de serviço

**2. Segurança de Aplicação**

- **Input Validation:** Validação rigorosa de todas as entradas do usuário
- **SQL Injection Protection:** Uso de prepared statements e ORM (SQLAlchemy)
- **XSS Protection:** Sanitização de outputs e Content Security Policy
- **CSRF Protection:** Tokens CSRF em todas as requisições de estado

**3. Segurança de Dados**

- **Criptografia em Trânsito:** TLS 1.3 para todas as comunicações
- **Criptografia em Repouso:** AES-256 para dados sensíveis no banco
- **Hashing de Senhas:** bcrypt com salt para senhas de administradores
- **Gestão de Segredos:** AWS Secrets Manager para chaves de API

**4. Controle de Acesso**

- **Autenticação:** OAuth 2.0 para integração com sistemas institucionais
- **Autorização:** RBAC (Role-Based Access Control) para diferentes níveis de acesso
- **Princípio do Menor Privilégio:** Cada componente tem apenas as permissões necessárias

**5. Monitoramento e Auditoria**

- **Logs Centralizados:** AWS CloudWatch registra todas as ações
- **Alertas:** Notificações automáticas para atividades suspeitas
- **Auditoria:** Revisão periódica de logs e acessos

### Conformidade com LGPD

**Medidas Implementadas:**

**1. Consentimento**

- Aviso claro na primeira interação sobre coleta de dados
- Opção de recusar identificação via QR Code
- Consentimento explícito para integração WhatsApp

**2. Minimização de Dados**

- Coleta apenas de dados estritamente necessários
- Anonimização de dados sempre que possível
- Não coleta de dados sensíveis (raça, religião, saúde) sem necessidade

**3. Segurança**

- Implementação de todas as medidas técnicas descritas acima
- Treinamento de equipe sobre proteção de dados
- Plano de resposta a incidentes

**4. Transparência**

- Política de privacidade acessível e clara
- Informação sobre finalidade de cada dado coletado
- Canal de comunicação para dúvidas sobre privacidade

**5. Direitos dos Titulares**

- Interface para exercício de direitos (acesso, correção, exclusão)
- Processo documentado para atendimento de solicitações
- Prazo de 15 dias úteis para resposta

**6. Encarregado de Dados (DPO)**

- Designação de encarregado de proteção de dados
- Contato disponível: dpo@instituicao.edu.br
- Responsável por garantir conformidade

### Plano de Resposta a Incidentes

Em caso de vazamento ou incidente de segurança:

**1. Detecção (0-1h)**
- Monitoramento automático detecta anomalia
- Alerta enviado para equipe de segurança

**2. Contenção (1-4h)**
- Isolamento do sistema afetado
- Bloqueio de acessos suspeitos
- Preservação de evidências

**3. Investigação (4-24h)**
- Análise de logs para identificar causa
- Avaliação de extensão do incidente
- Documentação detalhada

**4. Notificação (até 72h)**
- Notificação à ANPD (Autoridade Nacional de Proteção de Dados)
- Comunicação aos titulares afetados
- Transparência sobre medidas tomadas

**5. Remediação (1-2 semanas)**
- Correção da vulnerabilidade
- Implementação de medidas adicionais
- Testes de segurança

**6. Pós-Incidente (contínuo)**
- Revisão de processos de segurança
- Atualização de políticas
- Treinamento adicional da equipe

---

## ♿ Acessibilidade Universal

O EDUBOT foi projetado desde o início para ser 100% acessível, seguindo as diretrizes da Lei Brasileira de Inclusão (Lei 13.146/2015) e WCAG 2.1 nível AA.

### Recursos para Deficiência Visual

**1. Leitura de Tela Completa**

- **Tecnologia:** Google Text-to-Speech
- **Funcionalidade:** Todo o conteúdo exibido na tela é lido em voz alta
- **Controle:** Usuário pode pausar, acelerar ou diminuir velocidade da leitura
- **Ativação:** Automática ao detectar uso de botões táteis, ou manual via comando de voz

**2. Navegação por Voz**

- **Tecnologia:** Whisper (OpenAI) para reconhecimento de fala
- **Funcionalidade:** Usuário pode navegar e fazer consultas apenas por voz
- **Comandos:** "Ativar leitura de tela", "Voltar", "Próximo", "Repetir", "Ajuda"

**3. Alto Contraste**

- **Modos:** Alto contraste claro (fundo branco, texto preto) e escuro (fundo preto, texto branco)
- **Ativação:** Botão físico dedicado ou comando de voz "Ativar alto contraste"
- **Conformidade:** Razão de contraste mínima 7:1 (WCAG AAA)

**4. Ampliação de Texto**

- **Níveis:** 100%, 150%, 200%, 300%
- **Ativação:** Botões físicos "+" e "-" ou gestos de pinça na tela
- **Reflow:** Texto se reorganiza automaticamente sem scroll horizontal

**5. Botões Táteis com Braille**

- **Localização:** Parte inferior do totem, ao alcance de cadeirantes
- **Identificação:** Cada botão tem etiqueta em Braille
- **Funções:** Ativar leitura de tela, aumentar/diminuir volume, ajuda, voltar

**6. Feedback Sonoro**

- **Sons de confirmação:** Bip para cada ação (toque, seleção, erro)
- **Descrição de imagens:** IA descreve verbalmente qualquer imagem exibida
- **Alertas:** Notificações importantes são lidas em voz alta

### Recursos para Deficiência Auditiva

**1. Tradução Automática em Libras**

- **Tecnologia:** VLibras (Governo Federal)
- **Funcionalidade:** Todo o conteúdo de áudio é traduzido para Libras em tempo real
- **Avatar:** Personagem 3D realiza sinais na tela
- **Ativação:** Botão "Libras" na interface ou comando manual

**2. Legendas em Tempo Real**

- **Funcionalidade:** Transcrição automática de qualquer áudio reproduzido
- **Posicionamento:** Parte inferior da tela, fundo semitransparente
- **Tamanho:** Ajustável (pequeno, médio, grande)

**3. Feedback Visual**

- **Confirmações:** Animações visuais para cada ação (checkmark, loading)
- **Alertas:** Notificações importantes exibidas com destaque visual
- **Indicadores:** Barra de progresso, ícones de status

**4. Modo Silencioso**

- **Funcionalidade:** Desativa todos os sons, mantendo apenas feedback visual
- **Ativação:** Automática ao detectar uso de recursos para surdez, ou manual

### Recursos para Deficiência Cognitiva

**1. Interface Simplificada**

- **Design:** Layout limpo, sem elementos desnecessários
- **Hierarquia:** Informações organizadas por ordem de importância
- **Consistência:** Mesma estrutura em todas as telas

**2. Linguagem Clara e Direta**

- **Vocabulário:** Palavras simples, frases curtas
- **Evita:** Jargões técnicos, termos complexos
- **Exemplos:** Instruções acompanhadas de exemplos práticos

**3. Ícones Universais**

- **Pictogramas:** Símbolos reconhecíveis internacionalmente
- **Acompanhamento:** Cada ícone tem texto descritivo
- **Tamanho:** Ícones grandes (mínimo 48x48px)

**4. Tempo de Resposta Ajustável**

- **Funcionalidade:** Usuário pode aumentar tempo para leitura e decisão
- **Padrão:** 30 segundos por tela
- **Ajuste:** 60, 90 ou 120 segundos
- **Sem timeout:** Opção de desativar timeout completamente

**5. Navegação Linear**

- **Fluxo:** Passo a passo, sem bifurcações complexas
- **Breadcrumbs:** Indicação clara de onde o usuário está
- **Voltar:** Botão "Voltar" sempre visível e acessível

**6. Confirmações Duplas**

- **Ações importantes:** Solicitam confirmação antes de executar
- **Exemplo:** "Tem certeza que deseja enviar este feedback?"
- **Cancelamento:** Sempre há opção de cancelar

### Recursos para Baixo Letramento

**1. Modo Pictográfico**

- **Funcionalidade:** Interface baseada em imagens, não em texto
- **Navegação:** Seleção de ícones grandes e coloridos
- **Exemplos:** Ícone de relógio para horários, livro para biblioteca

**2. Áudio Explicativo**

- **Funcionalidade:** Instruções em áudio para cada tela
- **Linguagem:** Simples e acolhedora
- **Repetição:** Usuário pode ouvir novamente quantas vezes quiser

**3. Vídeos Tutoriais**

- **Funcionalidade:** Vídeos curtos (30-60s) explicando como usar o totem
- **Localização:** Menu "Ajuda"
- **Formato:** Animações simples com narração

**4. Conversão Texto para Áudio**

- **Funcionalidade:** Qualquer texto pode ser ouvido
- **Ativação:** Toque longo em qualquer texto
- **Velocidade:** Ajustável (lenta, normal, rápida)

### Recursos para Mobilidade Reduzida

**1. Altura Ajustável**

- **Funcionalidade:** Totem pode ser ajustado verticalmente
- **Faixa:** 80cm a 120cm (acessível para cadeirantes e pessoas em pé)
- **Ativação:** Botão físico ou comando de voz

**2. Botões Grandes**

- **Tamanho:** Mínimo 60x60px na tela, 30mm nos botões físicos
- **Espaçamento:** Mínimo 10px entre botões (evita toques acidentais)
- **Posicionamento:** Ao alcance de cadeirantes

**3. Ativação por Voz**

- **Funcionalidade:** Todas as funções podem ser acionadas por voz
- **Comandos:** Intuitivos e em linguagem natural
- **Exemplo:** "Mostrar horários de hoje", "Onde fica a biblioteca?"

**4. Tempo Estendido**

- **Funcionalidade:** Mais tempo para interações físicas
- **Sem timeout agressivo:** Usuário não é desconectado rapidamente

### Conformidade Legal

**Lei Brasileira de Inclusão (Lei 13.146/2015)**

O EDUBOT atende aos seguintes artigos:

- **Art. 3º:** Acessibilidade como direito fundamental
- **Art. 27:** Direito à educação inclusiva
- **Art. 42:** Tecnologias assistivas
- **Art. 63:** Acessibilidade em sistemas de informação

**WCAG 2.1 (Web Content Accessibility Guidelines) - Nível AA**

Conformidade com os 4 princípios:

1. **Perceptível:** Informação apresentada em múltiplos formatos (visual, auditivo, tátil)
2. **Operável:** Navegação por teclado, voz, toque e botões físicos
3. **Compreensível:** Linguagem clara, feedback consistente
4. **Robusto:** Compatível com tecnologias assistivas

### Testes de Acessibilidade

**Planejamento de Testes:**

**Fase 1: Testes Automatizados**
- Ferramentas: WAVE, axe DevTools, Lighthouse
- Verificação: Contraste, estrutura HTML, ARIA labels

**Fase 2: Testes com Usuários Reais**
- Recrutamento de voluntários com diferentes deficiências
- Testes de usabilidade supervisionados
- Coleta de feedback qualitativo

**Fase 3: Ajustes e Iteração**
- Implementação de melhorias baseadas em feedback
- Novos testes para validação
- Documentação de aprendizados

---

## 📱 Integração WhatsApp

### Visão Geral

A integração com WhatsApp permite que estudantes continuem a interação iniciada no totem através do aplicativo de mensagens mais popular do Brasil (usado por 96% dos brasileiros com smartphone, segundo pesquisa Statista 2023).

### Como Funciona

**Fluxo de Integração:**

1. **Opt-in no Totem**
   - Ao final da interação, estudante vê opção "Continuar no WhatsApp"
   - QR Code é exibido na tela
   - Estudante escaneia com câmera do celular

2. **Redirecionamento**
   - QR Code contém link para WhatsApp Business da instituição
   - Mensagem pré-preenchida: "Olá, vim do totem EDUBOT e gostaria de continuar nossa conversa"
   - Estudante envia mensagem

3. **Vinculação**
   - Backend identifica estudante através de token único no link
   - Histórico da conversa no totem é recuperado
   - Contexto é mantido

4. **Conversa Contínua**
   - Estudante pode fazer novas perguntas
   - IA mantém mesmo nível de personalização
   - Notificações e lembretes podem ser enviados

### Funcionalidades via WhatsApp

**1. Consultas Assíncronas**

Estudante pode fazer perguntas a qualquer momento, sem precisar estar fisicamente no totem.

**Exemplos:**
- "Qual o horário da aula de amanhã?"
- "Há algum aviso importante para mim?"
- "Preciso renovar um livro da biblioteca"

**2. Notificações Personalizadas**

Sistema envia notificações relevantes baseadas no perfil do estudante.

**Exemplos:**
- "Lembrete: Prazo de matrícula termina em 3 dias"
- "Nova vaga de estágio disponível para seu curso"
- "Palestra sobre IA acontece hoje às 19h no auditório"

**3. Lembretes Agendados**

Estudante pode solicitar lembretes para datas importantes.

**Exemplos:**
- "Me lembre de devolver o livro na sexta-feira"
- "Avise-me quando abrir matrícula para optativas"

**4. Acompanhamento de Solicitações**

Estudante pode acompanhar status de solicitações feitas na secretaria.

**Exemplos:**
- "Qual o status do meu pedido de histórico escolar?"
- "Minha declaração de matrícula ficou pronta?"

### Tecnologia Utilizada

**WhatsApp Business API**

API oficial do WhatsApp para empresas e instituições.

**Provedor: Twilio**

Twilio fornece infraestrutura confiável para integração com WhatsApp.

**Custos:**
- Conversas iniciadas pelo usuário: Gratuitas nas primeiras 24h
- Conversas iniciadas pela instituição: ~R$ 0,10 por mensagem
- Templates de mensagem: Aprovação prévia do WhatsApp necessária

**Implementação Técnica:**

```python
# Exemplo de código Python para envio de mensagem via Twilio

from twilio.rest import Client

# Credenciais (armazenadas em AWS Secrets Manager)
account_sid = os.getenv('TWILIO_ACCOUNT_SID')
auth_token = os.getenv('TWILIO_AUTH_TOKEN')
client = Client(account_sid, auth_token)

# Envio de mensagem
message = client.messages.create(
    from_='whatsapp:+5511999999999',  # Número da instituição
    body='Lembrete: Prazo de matrícula termina em 3 dias!',
    to='whatsapp:+5511888888888'  # Número do estudante
)

print(f"Mensagem enviada: {message.sid}")
```

**Webhooks:**

Twilio envia webhooks para o backend quando estudante responde:

```python
# Endpoint FastAPI para receber mensagens

from fastapi import FastAPI, Form

app = FastAPI()

@app.post("/webhook/whatsapp")
async def whatsapp_webhook(
    From: str = Form(...),
    Body: str = Form(...),
    MessageSid: str = Form(...)
):
    # Processar mensagem recebida
    numero_estudante = From.replace('whatsapp:', '')
    mensagem = Body
    
    # Enviar para IA para processamento
    resposta = processar_com_ia(mensagem, numero_estudante)
    
    # Enviar resposta via Twilio
    enviar_resposta_whatsapp(numero_estudante, resposta)
    
    return {"status": "ok"}
```

### Privacidade e Consentimento

**Opt-in Explícito:**

- Estudante escolhe ativamente se deseja integração
- Informação clara sobre quais dados serão usados
- Opção de cancelar a qualquer momento

**Dados Compartilhados:**

- Número de telefone (fornecido pelo estudante)
- Histórico de conversas (criptografado)
- Preferências de notificação

**Não Compartilhados:**

- Dados pessoais sensíveis
- Informações de terceiros
- Dados financeiros

**Cancelamento:**

Estudante pode cancelar integração a qualquer momento:
- Enviando "PARAR" via WhatsApp
- Através da interface do totem
- Solicitando na secretaria

---

## 📅 Plano de Desenvolvimento

### Cronograma Geral

O desenvolvimento do EDUBOT está planejado para 6 meses, dividido em 6 sprints de 4 semanas cada.

### Sprint 1: Documentação e Planejamento (Atual - Outubro 2025)

**Objetivo:** Criar documentação completa e arquitetura da solução.

**Entregas:**
- ✅ Justificativa do problema
- ✅ Descrição da solução
- ✅ Definição de tecnologias
- ✅ Diagramas de arquitetura
- ✅ Estratégia de coleta de dados
- ✅ Plano de desenvolvimento
- ✅ Repositório GitHub privado

**Status:** ✅ Concluída

---

### Sprint 2: Backend e APIs (Novembro 2025)

**Objetivo:** Desenvolver backend FastAPI e integração com banco de dados.

**Tarefas:**

**Semana 1-2: Estrutura Base**
- [ ] Configurar ambiente de desenvolvimento (Python 3.11, FastAPI)
- [ ] Criar estrutura de pastas e módulos
- [ ] Configurar Docker e Docker Compose
- [ ] Implementar autenticação OAuth 2.0
- [ ] Conectar com Supabase (PostgreSQL)
- [ ] Criar modelos de dados (SQLAlchemy)

**Semana 3-4: APIs e Lógica de Negócio**
- [ ] Implementar endpoints RESTful
  - GET /api/horarios (consultar horários)
  - GET /api/avisos (listar avisos)
  - POST /api/interacoes (registrar interação)
  - GET /api/localizacao (buscar localização)
- [ ] Integrar com OpenAI GPT-4
- [ ] Implementar cache com Redis
- [ ] Criar testes unitários (pytest)

**Entregas:**
- Backend funcional com APIs documentadas (Swagger)
- Integração com banco de dados
- Testes unitários com cobertura >80%

---

### Sprint 3: Frontend e Interface (Dezembro 2025)

**Objetivo:** Desenvolver interface React acessível e responsiva.

**Tarefas:**

**Semana 1-2: Componentes Base**
- [ ] Configurar projeto React + TailwindCSS
- [ ] Criar componentes acessíveis (React Aria)
- [ ] Implementar navegação e roteamento
- [ ] Desenvolver tela inicial
- [ ] Desenvolver tela de consulta de horários
- [ ] Desenvolver tela de avisos

**Semana 3-4: Acessibilidade e Integração**
- [ ] Implementar leitura de tela (Web Speech API)
- [ ] Implementar reconhecimento de voz (Whisper)
- [ ] Integrar VLibras para tradução em Libras
- [ ] Implementar alto contraste e ampliação
- [ ] Conectar frontend com backend (APIs)
- [ ] Testes de usabilidade

**Entregas:**
- Interface completa e funcional
- Recursos de acessibilidade implementados
- Integração frontend-backend

---

### Sprint 4: Hardware e IoT (Janeiro 2026)

**Objetivo:** Integrar hardware (ESP32, sensores) com software.

**Tarefas:**

**Semana 1-2: Configuração de Hardware**
- [ ] Configurar ESP32-CAM
- [ ] Implementar reconhecimento de QR Code
- [ ] Configurar sensor PIR (presença)
- [ ] Testar comunicação WiFi com backend
- [ ] Configurar Raspberry Pi 4
- [ ] Instalar sistema operacional e dependências

**Semana 3-4: Integração e Testes**
- [ ] Integrar ESP32 com backend (MQTT ou HTTP)
- [ ] Implementar detecção automática de presença
- [ ] Testar escaneamento de QR Code
- [ ] Montar protótipo físico do totem
- [ ] Testes de hardware em ambiente controlado

**Entregas:**
- Protótipo físico funcional
- Hardware integrado com software
- Documentação técnica de hardware

---

### Sprint 5: Integração WhatsApp e N8N (Fevereiro 2026)

**Objetivo:** Implementar integração com WhatsApp e automações.

**Tarefas:**

**Semana 1-2: WhatsApp Business API**
- [ ] Configurar conta Twilio
- [ ] Obter aprovação de templates de mensagem
- [ ] Implementar envio de mensagens
- [ ] Implementar recebimento de mensagens (webhooks)
- [ ] Criar fluxo de opt-in via QR Code

**Semana 3-4: Automações com N8N**
- [ ] Configurar N8N
- [ ] Criar workflow de notificações
- [ ] Criar workflow de lembretes agendados
- [ ] Integrar N8N com backend e WhatsApp
- [ ] Testes de automações

**Entregas:**
- Integração WhatsApp funcional
- Automações configuradas
- Documentação de workflows

---

### Sprint 6: Testes, Ajustes e Lançamento (Março 2026)

**Objetivo:** Realizar testes com usuários reais, ajustes finais e lançamento piloto.

**Tarefas:**

**Semana 1: Testes de Acessibilidade**
- [ ] Recrutar voluntários com deficiência
- [ ] Realizar testes supervisionados
- [ ] Coletar feedback qualitativo
- [ ] Documentar problemas encontrados

**Semana 2: Ajustes e Melhorias**
- [ ] Implementar correções baseadas em feedback
- [ ] Otimizar performance
- [ ] Melhorar textos e instruções
- [ ] Testes de regressão

**Semana 3: Preparação para Lançamento**
- [ ] Configurar ambiente de produção (AWS)
- [ ] Deploy de backend e frontend
- [ ] Configurar monitoramento (CloudWatch, Sentry)
- [ ] Criar documentação para usuários finais
- [ ] Treinamento de equipe de suporte

**Semana 4: Lançamento Piloto**
- [ ] Instalar totem em localização piloto (biblioteca ou secretaria)
- [ ] Monitorar uso e performance
- [ ] Coletar feedback dos primeiros usuários
- [ ] Ajustes rápidos conforme necessário

**Entregas:**
- Sistema em produção
- Totem instalado e funcionando
- Documentação completa
- Relatório de lançamento piloto

---

### Pós-Lançamento (Abril 2026 em diante)

**Manutenção Contínua:**
- Monitoramento de performance e erros
- Atualizações de segurança
- Melhorias baseadas em feedback

**Expansão:**
- Instalação de totens adicionais
- Novas funcionalidades baseadas em demanda
- Integração com outros sistemas institucionais

---

## 📖 Casos de Uso

### Caso de Uso 1: Consulta de Horário

**Ator:** Estudante de Engenharia de Software, 3º semestre

**Cenário:**

Maria chega ao campus e não lembra o horário da aula de Banco de Dados. Ela se aproxima do totem EDUBOT na entrada do prédio.

**Fluxo:**

1. Sensor PIR detecta presença de Maria e ativa o totem
2. Tela exibe: "Olá! Como posso ajudar você hoje?"
3. Maria toca em "Consultar Horários"
4. Sistema oferece opção de identificação via QR Code
5. Maria escaneia cartão estudantil
6. Sistema reconhece Maria e exibe: "Olá, Maria! Seus horários de hoje:"
7. Tela mostra horários personalizados:
   - 08:00-10:00 - Banco de Dados - Prof. João - Sala 305
   - 10:20-12:00 - Engenharia de Software - Prof. Ana - Lab 2
8. Maria toca em "Enviar para WhatsApp"
9. QR Code é exibido
10. Maria escaneia e recebe horários no WhatsApp

**Resultado:** Maria encontrou a informação em menos de 30 segundos e pode consultar no celular a qualquer momento.

---

### Caso de Uso 2: Navegação com Acessibilidade

**Ator:** Estudante com deficiência visual

**Cenário:**

Carlos é calouro e tem deficiência visual total. Ele precisa encontrar a biblioteca para retirar um livro.

**Fluxo:**

1. Carlos se aproxima do totem e toca nos botões táteis com Braille
2. Sistema detecta uso de botões físicos e ativa automaticamente leitura de tela
3. Voz do sistema: "Olá! Bem-vindo ao EDUBOT. Como posso ajudar você?"
4. Carlos diz: "Onde fica a biblioteca?"
5. Sistema processa pergunta com IA
6. Voz do sistema: "A biblioteca fica no segundo andar do prédio central. Siga em frente por 50 metros, vire à direita e suba as escadas. Deseja que eu envie estas instruções para seu WhatsApp?"
7. Carlos: "Sim, por favor"
8. Sistema: "Por favor, aproxime seu celular do totem para escanear o QR Code"
9. Carlos escaneia com leitor de QR Code acessível
10. Instruções são enviadas para WhatsApp de Carlos

**Resultado:** Carlos recebeu orientação clara e pode consultar as instruções novamente no celular com leitor de tela.

---

### Caso de Uso 3: Feedback sobre Serviço

**Ator:** Estudante de Administração

**Cenário:**

Ana acabou de ser atendida na secretaria e quer dar feedback sobre o atendimento.

**Fluxo:**

1. Ana se aproxima do totem
2. Tela exibe menu principal
3. Ana toca em "Dar Feedback"
4. Sistema: "Sobre qual serviço você gostaria de dar feedback?"
5. Ana seleciona "Secretaria Acadêmica"
6. Sistema: "Como você avalia o atendimento? (1 a 5 estrelas)"
7. Ana seleciona 5 estrelas
8. Sistema: "Gostaria de deixar um comentário? (opcional)"
9. Ana digita: "Atendimento rápido e eficiente. Parabéns!"
10. Sistema: "Obrigado pelo seu feedback! Ele é muito importante para nós."

**Resultado:** Instituição recebe feedback estruturado e pode medir satisfação dos estudantes.

---

### Caso de Uso 4: Aviso Urgente

**Ator:** Estudante de Direito

**Cenário:**

Pedro está no campus e há um aviso urgente sobre cancelamento de aula.

**Fluxo:**

1. Pedro passa pelo totem
2. Sensor detecta presença
3. Tela exibe alerta vermelho: "⚠️ AVISO IMPORTANTE"
4. Pedro toca na tela
5. Sistema: "Atenção estudantes de Direito: A aula de Direito Constitucional das 14h foi cancelada devido a compromisso do professor. Reposição será agendada."
6. Pedro: "Quero receber avisos como este no WhatsApp"
7. Sistema exibe QR Code para opt-in
8. Pedro escaneia e confirma
9. Sistema: "Pronto! Você receberá avisos importantes no WhatsApp."

**Resultado:** Pedro foi informado em tempo real e agora receberá notificações futuras no celular.

---

## 🏆 Diferenciais Competitivos

### 1. Acessibilidade Total desde o Design

Diferente de soluções que adicionam acessibilidade como "recurso extra", o EDUBOT foi projetado desde o início para ser 100% acessível. Isso resulta em experiência superior para todos os usuários, não apenas PcD.

### 2. Inteligência Artificial Conversacional

Uso de modelos de linguagem avançados (GPT-4) permite interações naturais em linguagem humana, sem necessidade de comandos específicos ou navegação complexa em menus.

### 3. Integração WhatsApp Nativa

Continuidade da experiência do totem para o celular, permitindo acompanhamento de solicitações e recebimento de notificações personalizadas.

### 4. Coleta Inteligente de Dados

Geração de insights valiosos para gestão educacional através de análise de padrões de uso, consultas frequentes e satisfação dos usuários.

### 5. Modularidade e Escalabilidade

Arquitetura em camadas permite fácil expansão de funcionalidades e replicação para múltiplas instituições.

### 6. Conformidade Legal Total

Atendimento rigoroso à LGPD e Lei Brasileira de Inclusão, reduzindo riscos legais e demonstrando responsabilidade social.

### 7. Baixo Custo de Implementação

Uso de hardware acessível (ESP32, Raspberry Pi) e software open-source reduz custo inicial, tornando solução viável para instituições de todos os portes.

### 8. Impacto Social Mensurável

Métricas claras de inclusão (uso de recursos de acessibilidade, satisfação de PcD) permitem demonstrar impacto social real.

---

## 📚 Referências

### Legislação

1. **Lei Brasileira de Inclusão (Lei 13.146/2015)**  
   http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2015/lei/l13146.htm

2. **Lei Geral de Proteção de Dados - LGPD (Lei 13.709/2018)**  
   http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm

3. **Decreto 5.296/2004 (Acessibilidade)**  
   http://www.planalto.gov.br/ccivil_03/_ato2004-2006/2004/decreto/d5296.htm

### Normas e Diretrizes

4. **WCAG 2.1 (Web Content Accessibility Guidelines)**  
   https://www.w3.org/WAI/WCAG21/quickref/

5. **ISO/IEC 27001 (Segurança da Informação)**  
   https://www.iso.org/isoiec-27001-information-security.html

### Dados e Pesquisas

6. **Censo da Educação Superior 2022 (INEP)**  
   https://www.gov.br/inep/pt-br/areas-de-atuacao/pesquisas-estatisticas-e-indicadores/censo-da-educacao-superior

7. **Pesquisa Nacional de Saúde 2019 - PcD (IBGE)**  
   https://www.ibge.gov.br/estatisticas/sociais/saude/9160-pesquisa-nacional-de-saude.html

8. **Statista - WhatsApp Usage in Brazil 2023**  
   https://www.statista.com/statistics/

### Documentação Técnica

9. **OpenAI API Documentation**  
   https://platform.openai.com/docs

10. **FastAPI Documentation**  
    https://fastapi.tiangolo.com/

11. **Supabase Documentation**  
    https://supabase.com/docs

12. **ESP32 Documentation (Espressif)**  
    https://docs.espressif.com/projects/esp-idf/en/latest/esp32/

13. **Twilio WhatsApp API**  
    https://www.twilio.com/docs/whatsapp

14. **VLibras (Tradução em Libras)**  
    https://www.gov.br/governodigital/pt-br/vlibras

15. **N8N Documentation**  
    https://docs.n8n.io/

### Artigos e Recursos

16. **Challenge FlexMedia - Briefing Original**  
    Documento fornecido pela FIAP (Outubro 2025)

17. **React Aria - Accessible Components**  
    https://react-spectrum.adobe.com/react-aria/

18. **AWS Well-Architected Framework**  
    https://aws.amazon.com/architecture/well-architected/

---

## 📞 Contato

**Aluno:** Fabrício Mouzer Brito  
**RM:** 566777  
**E-mail:** fabriciomouzer@hotmail.com  
**Turma:** R  
**Instituição:** FIAP - Faculdade de Informática e Administração Paulista  
**Curso:** Tecnólogo em Inteligência Artificial

**Tutora:** Ana Cristana dos Santos (@anacrissantos)

---

## 📄 Licença

Este projeto é desenvolvido como parte do Challenge FlexMedia da FIAP e está sujeito às regras acadêmicas da instituição.

**Direitos Autorais:** © 2025 Fabrício Mouzer Brito

---

## ✅ Status do Projeto

- [x] Documentação inicial completa
- [x] Arquitetura definida
- [x] Tecnologias selecionadas
- [x] Estratégia de coleta de dados documentada
- [x] Plano de desenvolvimento estruturado
- [ ] Backend desenvolvido
- [ ] Frontend desenvolvido
- [ ] Hardware integrado
- [ ] Integração WhatsApp implementada
- [ ] Testes com usuários realizados
- [ ] Lançamento piloto

---

**Última atualização:** 28 de Outubro de 2025

**Versão do documento:** 1.0

---

## 🎯 Próximos Passos Imediatos

1. ✅ Criar repositório GitHub privado
2. ✅ Adicionar tutora como colaboradora
3. ✅ Criar estrutura de pastas
4. ✅ Escrever README.md completo
5. [ ] Criar diagramas de arquitetura
6. [ ] Submeter no portal FIAP até 31/10/2025, 23h59

---

**Agradecimentos especiais à FlexMedia pela oportunidade de desenvolver este projeto com impacto social real.**

🚀 **EDUBOT - Democratizando o acesso à informação educacional através da IA**
