# ⚡ Matheus Boeira Pedroso

**AI Systems • Cybersecurity • Data Engineering • Software Architecture**

Desenvolvimento de projetos com foco em **IA aplicada, segurança, engenharia de software, dados, sistemas distribuídos, automação e performance**.

O perfil reúne projetos acadêmicos, experimentais e de engenharia, mantendo uma distinção explícita entre **protótipo, PoC, execução medida e hipótese**.

## 🧭 Áreas de atuação e estudo

- 🧠 **AI Systems & Experimentation** — prototipação, avaliação e benchmarking
- 🛡️ **Cybersecurity** — secure-by-design, desenvolvimento seguro e gestão de riscos
- ⚙️ **Software Architecture** — sistemas modulares, integração e evolução incremental
- 📊 **Data Engineering** — pipelines, streaming, CDC e processamento de eventos
- 🌿 **Environmental & Geospatial Systems** — monitoramento ambiental, GeoJSON e SIG
- 🚀 **Automation & DevOps** — GitHub Actions, CI/CD, infraestrutura como código e Vercel
- 🌐 **Web Engineering** — aplicações web leves, interfaces e APIs

## 🛠️ Tecnologias

| Área | Tecnologias |
| --- | --- |
| **Linguagens** | Python • JavaScript • TypeScript • SQL • C |
| **IA & Computação** | NumPy • álgebra linear • benchmarking • offloading computacional |
| **Web & APIs** | HTML5 • CSS3 • React / Next.js • FastAPI • REST |
| **Dados & Streaming** | PostgreSQL • Apache Kafka • Confluent Cloud • Apache Flink SQL • Debezium |
| **Sistemas** | ZeroMQ • TCP • Linux • BLAS |
| **Geoespacial** | GeoJSON • Leaflet • SIG |
| **Cloud & DevOps** | Vercel • GitHub Actions • Terraform • Docker |

# 🚀 Projetos

## 🧠 [PROJECT-NEURO-K](https://github.com/Matheus-dotcom-bot/PROJECT-NEURO-K)

**Adaptive Computational Offloading — Proof of Concept**

PoC experimental que investiga quando uma carga de álgebra linear deve ser executada localmente ou transferida para um worker remoto. Utiliza **Python, NumPy, ZeroMQ/TCP, calibração, estimativa de memória, testes automatizados e benchmark**.

- decisão adaptativa baseada em medições de calibração;
- transporte binário de buffers NumPy;
- worker remoto funcional;
- API FastAPI como baseline cloud na Vercel;
- testes unitários e de integração;
- separação explícita entre dados `SIMULATED` e `MEASURED`.

**Estado:** PoC funcional / experimental. Os resultados simulados não são apresentados como evidência experimental.

---

## 💳 [Pipeline de Pagamentos — Confluent Cloud](https://github.com/Matheus-dotcom-bot/pipeline-pagamentos-confluent-cloud)

**Real-Time Payment Data Pipeline**

Projeto de engenharia de dados para processamento de pagamentos em streaming, estruturado de ponta a ponta com **PostgreSQL, CDC/Debezium, Apache Kafka, Confluent Cloud e Flink SQL**.

Arquitetura principal:

```text
PostgreSQL
    ↓
CDC / Debezium
    ↓
Confluent Cloud / Kafka
    ↓
Apache Flink SQL
    ├── enriquecimento
    ├── classificação de risco
    └── detecção de suspeitas
    ↓
Consumer
```

Inclui infraestrutura como código com Terraform, consumidor Python, validações operacionais e estrutura para evidências reais de execução.

**Estado:** infraestrutura base implementada; integração real com Confluent Cloud e evidências de execução são a próxima etapa.

---

## 🛡️ [Hyperion Cybersecurity Brasil](https://github.com/Matheus-dotcom-bot/Matheus-dotcom-bot-Hyperion-Cybersecurity-Brasil)

**Landing Page — Cybersecurity**

Landing page estática experimental para uma proposta de atuação em cybersecurity, com foco em **S-SDLC, gestão de vulnerabilidades e práticas relacionadas à LGPD**.

- HTML5 + CSS3 + JavaScript mínimo;
- arquitetura estática e responsiva;
- escopo separado de plataformas operacionais de segurança;
- documentação de limites e requisitos para produção;
- demonstração hospedada na Vercel.

**Estado:** protótipo web ativo.

---

## 🌿 [Monitoramento de Biomas — UERGS Litoral Norte](https://github.com/Matheus-dotcom-bot/monitoramento-biomas-uergs)

**Protótipo acadêmico — Monitoramento ambiental e geoespacial**

Aplicação client-side para organização de observações ambientais, integração com **GeoJSON** e visualização cartográfica com **Leaflet**, com foco acadêmico em Imbé/RS.

- cadastro local de observações;
- tabela dinâmica;
- camadas GeoJSON;
- mapa interativo;
- validação básica de dados;
- cuidados contra XSS na renderização dos registros.

**Estado:** protótipo acadêmico funcional; ainda sem backend, autenticação ou persistência de produção.

---

## 🔗 [Connect Hub — Profile](https://github.com/Matheus-dotcom-bot/Profile)

**Hub profissional pessoal**

Landing page estática para centralizar conexões profissionais, GitHub, LinkedIn e portfólio.

**Estado:** aplicação web estática / Connect Hub.

---

## 👤 [Repositório de perfil](https://github.com/Matheus-dotcom-bot/matheus-dotcom-bot)

Este próprio repositório funciona como **índice técnico do portfólio**, reunindo os projetos e as principais áreas de estudo e desenvolvimento.

## 🔬 Princípio de desenvolvimento

> **Construir → medir → revisar → melhorar.**

A documentação procura deixar claro:

- o que foi realmente implementado;
- o que foi medido;
- o que é simulação;
- quais são as limitações;
- quais etapas ainda dependem de validação real.

## 📈 O que o portfólio demonstra

- desenvolvimento de artefatos executáveis;
- integração entre software, dados e infraestrutura;
- preocupação com testes e reprodutibilidade;
- uso de CI/CD e automação;
- experimentação técnica documentada;
- desenvolvimento web e cloud;
- aplicações acadêmicas com dados ambientais e geoespaciais.

## 🌐 Demonstrações

**Hyperion Cybersecurity**  
https://matheus-dotcom-bot-hyperse-cyberse-six.vercel.app/

## 📫 Contato

- **LinkedIn:** https://www.linkedin.com/in/matheus-boeira-pedroso
- **GitHub:** https://github.com/Matheus-dotcom-bot

---

**Matheus Boeira Pedroso**  
*AI Systems • Cybersecurity • Data Engineering • Software Architecture*