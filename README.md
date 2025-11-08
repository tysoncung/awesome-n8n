# Awesome N8N [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A comprehensive awesome list for n8n - the workflow automation platform for technical people.

n8n is a free and open-source workflow automation tool that allows you to connect different services and automate tasks. Unlike other automation tools, n8n is self-hostable, provides source-available code, and gives you full control over your data.

## Contents

- [Official Resources](#official-resources)
- [Getting Started](#getting-started)
- [Community Nodes](#community-nodes)
- [Workflow Templates](#workflow-templates)
- [Enterprise Integrations](#enterprise-integrations)
- [AI & LLM Integrations](#ai--llm-integrations)
- [Hosting & Deployment](#hosting--deployment)
- [Development Tools](#development-tools)
- [Security & Compliance](#security--compliance)
- [Monitoring & Observability](#monitoring--observability)
- [Best Practices & Patterns](#best-practices--patterns)
- [Learning Resources](#learning-resources)
- [Community & Support](#community--support)
- [Alternatives & Comparisons](#alternatives--comparisons)
- [Tools & Utilities](#tools--utilities)
- [Contribute](#contribute)

## Official Resources

Official documentation and resources from n8n.

- [n8n Official Website](https://n8n.io/) - Official n8n website with product information.
- [n8n Documentation](https://docs.n8n.io/) - Comprehensive official documentation.
- [n8n GitHub Repository](https://github.com/n8n-io/n8n) - Main n8n source code repository.
- [n8n Community Forum](https://community.n8n.io/) - Official community discussion forum.
- [n8n Blog](https://blog.n8n.io/) - Official blog with tutorials and announcements.
- [n8n YouTube Channel](https://www.youtube.com/c/n8n-io) - Video tutorials and demos.
- [n8n Changelog](https://docs.n8n.io/release-notes/) - Latest updates and release notes.
- [n8n Cloud](https://n8n.io/cloud/) - Managed n8n hosting service.

## Getting Started

Resources to help you get started with n8n.

### Installation Guides

- [Docker Installation](https://docs.n8n.io/hosting/installation/docker/) - Run n8n with Docker and Docker Compose.
- [npm Installation](https://docs.n8n.io/hosting/installation/npm/) - Install n8n globally using npm.
- [n8n Desktop App](https://docs.n8n.io/hosting/installation/desktop-app/) - Desktop application for Windows, macOS, and Linux.
- [Kubernetes Deployment](https://github.com/n8n-io/n8n-kubernetes) - Helm charts for deploying n8n on Kubernetes.
- [Railway Template](https://railway.app/template/n8n) - One-click deployment on Railway.
- [Render Template](https://render.com/docs/deploy-n8n) - Deploy n8n on Render.
- [DigitalOcean Marketplace](https://marketplace.digitalocean.com/apps/n8n) - Pre-configured n8n droplet.

### Tutorials

- [Building Your First Workflow](https://docs.n8n.io/getting-started/building-workflows/) - Step-by-step guide to creating workflows.
- [Understanding Nodes](https://docs.n8n.io/nodes/) - Learn about n8n's node system.
- [Working with Data](https://docs.n8n.io/data/) - Data manipulation and transformation.
- [Using Expressions](https://docs.n8n.io/code-examples/expressions/) - JavaScript expressions in n8n.
- [Error Handling](https://docs.n8n.io/workflows/error-handling/) - Building robust workflows with error handling.
- [Migrating from Zapier](https://blog.n8n.io/migrate-from-zapier-to-n8n/) - Guide to migrating from Zapier to n8n.
- [Migrating from Make](https://blog.n8n.io/migrate-from-make-integromat-to-n8n/) - Guide to migrating from Make (Integromat).

## Community Nodes

Popular community-created nodes extending n8n's capabilities.

### Communication & Messaging

- [WhatsApp Business](https://www.npmjs.com/package/n8n-nodes-whatsapp) - API integration for messaging platform.
- [Telegram Advanced](https://www.npmjs.com/package/n8n-nodes-telegram-advanced) - Extended Telegram functionality.
- [Discord Advanced](https://www.npmjs.com/package/n8n-nodes-discord-advanced) - Enhanced Discord integration.
- [Chatwoot](https://www.npmjs.com/package/n8n-nodes-chatwoot) - Open-source customer engagement platform.
- [Twilio Advanced](https://www.npmjs.com/package/n8n-nodes-twilio-advanced) - Extended Twilio capabilities.
- [Zalo](https://www.npmjs.com/package/n8n-nodes-zalo) - Vietnamese messaging platform integration.
- [Matrix](https://www.npmjs.com/package/n8n-nodes-matrix) - Decentralized communication protocol.
- [Mattermost](https://www.npmjs.com/package/n8n-nodes-mattermost) - Open-source team collaboration.
- [RocketChat](https://www.npmjs.com/package/n8n-nodes-rocketchat) - Team chat platform integration.

### Document Generation

- [PDF Generation](https://www.npmjs.com/package/n8n-nodes-pdf-generator) - Generate PDFs from HTML templates.
- [Docx Generator](https://www.npmjs.com/package/n8n-nodes-docx) - Create Word documents programmatically.
- [QR Code Generator](https://www.npmjs.com/package/n8n-nodes-qrcode) - Generate QR codes.
- [Digital Signatures](https://www.npmjs.com/package/n8n-nodes-docusign) - DocuSign integration for e-signatures.
- [PDFKit](https://www.npmjs.com/package/n8n-nodes-pdfkit) - Advanced PDF manipulation.
- [PDF.co](https://www.npmjs.com/package/n8n-nodes-pdfco) - PDF conversion and processing.

### Browser Automation

- [Puppeteer](https://www.npmjs.com/package/n8n-nodes-puppeteer) - Headless Chrome automation.
- [Playwright](https://www.npmjs.com/package/n8n-nodes-playwright) - Cross-browser automation.
- [Firecrawl](https://www.npmjs.com/package/n8n-nodes-firecrawl) - Web scraping and crawling.
- [Browserless](https://www.npmjs.com/package/n8n-nodes-browserless) - Scalable browser automation.
- [Selenium](https://www.npmjs.com/package/n8n-nodes-selenium) - Web browser automation framework.

### Data Processing

- [Text Processing](https://www.npmjs.com/package/n8n-nodes-text-manipulation) - Advanced text manipulation.
- [JSON Tools](https://www.npmjs.com/package/n8n-nodes-json-tools) - JSON parsing and transformation.
- [CSV Parser](https://www.npmjs.com/package/n8n-nodes-csv-advanced) - Advanced CSV operations.
- [XML Parser](https://www.npmjs.com/package/n8n-nodes-xml-parser) - XML parsing and conversion.
- [YAML Parser](https://www.npmjs.com/package/n8n-nodes-yaml) - YAML file processing.
- [OCR](https://www.npmjs.com/package/n8n-nodes-ocr) - Optical character recognition.
- [Tesseract OCR](https://www.npmjs.com/package/n8n-nodes-tesseract) - Open-source OCR engine.
- [Data Validation](https://www.npmjs.com/package/n8n-nodes-validator) - Schema validation and data cleaning.

### AI & Machine Learning

- [OpenAI Advanced](https://www.npmjs.com/package/n8n-nodes-openai-advanced) - Extended OpenAI capabilities.
- [Anthropic Claude](https://www.npmjs.com/package/n8n-nodes-anthropic) - Claude AI integration.
- [LangChain](https://www.npmjs.com/package/n8n-nodes-langchain) - Framework for building LLM applications.
- [ElevenLabs](https://www.npmjs.com/package/n8n-nodes-elevenlabs) - AI voice generation.
- [DeepSeek](https://www.npmjs.com/package/n8n-nodes-deepseek) - AI language models integration.
- [Perplexity AI](https://www.npmjs.com/package/n8n-nodes-perplexity) - Perplexity search integration.
- [MCP Nodes](https://www.npmjs.com/package/n8n-nodes-mcp) - Model Context Protocol integration.
- [Replicate](https://www.npmjs.com/package/n8n-nodes-replicate) - Run AI models in the cloud.
- [Cohere](https://www.npmjs.com/package/n8n-nodes-cohere) - NLP and text generation models.
- [HuggingFace](https://www.npmjs.com/package/n8n-nodes-huggingface) - Access to thousands of ML models.

### CRM & Sales

- [HubSpot Advanced](https://www.npmjs.com/package/n8n-nodes-hubspot-advanced) - Extended HubSpot functionality.
- [Salesforce Advanced](https://www.npmjs.com/package/n8n-nodes-salesforce-advanced) - Enhanced Salesforce integration.
- [Pipedrive Extended](https://www.npmjs.com/package/n8n-nodes-pipedrive-extended) - Additional Pipedrive features.
- [Zoho CRM](https://www.npmjs.com/package/n8n-nodes-zoho-crm) - Customer relationship management platform.
- [Kommo CRM](https://www.npmjs.com/package/n8n-nodes-kommo) - Kommo (amoCRM) integration.
- [Freshsales](https://www.npmjs.com/package/n8n-nodes-freshsales) - Modern CRM for high-velocity sales.
- [Close CRM](https://www.npmjs.com/package/n8n-nodes-close) - Sales engagement CRM platform.
- [Monday CRM](https://www.npmjs.com/package/n8n-nodes-monday) - Work operating system with CRM capabilities.

### Analytics & BI

- [Google Analytics 4](https://www.npmjs.com/package/n8n-nodes-ga4) - GA4 reporting and data export.
- [Power BI](https://www.npmjs.com/package/n8n-nodes-powerbi) - Microsoft Power BI integration.
- [Tableau](https://www.npmjs.com/package/n8n-nodes-tableau) - Business intelligence data connector.
- [Mixpanel](https://www.npmjs.com/package/n8n-nodes-mixpanel) - Product analytics integration.
- [Amplitude](https://www.npmjs.com/package/n8n-nodes-amplitude) - Digital analytics platform.

## Workflow Templates

Pre-built workflows for common use cases.

### Marketing Automation

- [Email Drip Campaigns](https://n8n.io/workflows/email-drip-campaign) - Automated email sequences.
- [Social Media Scheduler](https://n8n.io/workflows/social-media-scheduler) - Schedule posts across platforms.
- [Lead Scoring](https://n8n.io/workflows/lead-scoring-automation) - Automated lead qualification.
- [Content Publishing Pipeline](https://n8n.io/workflows/content-publishing) - Multi-channel content distribution.
- [Marketing Attribution](https://n8n.io/workflows/marketing-attribution) - Track campaign performance.

### Sales Operations

- [Lead Enrichment](https://n8n.io/workflows/lead-enrichment) - Automatically enrich lead data.
- [Quote Generation](https://n8n.io/workflows/quote-generator) - Generate sales quotes automatically.
- [Pipeline Automation](https://n8n.io/workflows/sales-pipeline) - Automated deal progression.
- [Meeting Scheduler](https://n8n.io/workflows/meeting-scheduler) - Calendar coordination automation.

### DevOps & IT

- [Incident Response](https://n8n.io/workflows/incident-response) - Automated incident management.
- [Server Monitoring](https://n8n.io/workflows/server-monitoring) - Infrastructure health checks.
- [Deployment Pipeline](https://n8n.io/workflows/deployment-automation) - CI/CD workflow automation.
- [Backup Automation](https://n8n.io/workflows/backup-automation) - Automated backup workflows.
- [Log Aggregation](https://n8n.io/workflows/log-aggregation) - Centralized log collection.

### Customer Support

- [Ticket Routing](https://n8n.io/workflows/ticket-routing) - Intelligent ticket assignment.
- [Customer Onboarding](https://n8n.io/workflows/customer-onboarding) - Automated onboarding sequences.
- [Feedback Collection](https://n8n.io/workflows/feedback-automation) - Survey and feedback workflows.
- [SLA Monitoring](https://n8n.io/workflows/sla-monitoring) - Track and alert on SLA violations.

### E-commerce

- [Order Processing](https://n8n.io/workflows/order-processing) - Automated order fulfillment.
- [Inventory Sync](https://n8n.io/workflows/inventory-sync) - Multi-channel inventory management.
- [Abandoned Cart](https://n8n.io/workflows/abandoned-cart) - Cart recovery campaigns.
- [Product Catalog Sync](https://n8n.io/workflows/product-sync) - Sync products across platforms.

## Enterprise Integrations

Integrations for enterprise systems and tools.

### ERP Systems

- [SAP Integration](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.sap/) - SAP ERP connectivity.
- [Oracle NetSuite](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-netsuite/) - NetSuite ERP integration.
- [Microsoft Dynamics 365](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.microsoftdynamics/) - Dynamics 365 connector.
- [Odoo](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-odoo/) - Open-source ERP integration.

### Enterprise CRM

- [Salesforce](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.salesforce/) - Enterprise CRM with custom object support.
- [Microsoft Dynamics CRM](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.microsoftdynamicscrm/) - Dynamics CRM connector.
- [ServiceNow](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.servicenow/) - IT service management platform.
- [Zendesk](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.zendesk/) - Customer support ticketing system.

### HR & Workforce

- [Workday](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-workday/) - Human capital management system.
- [BambooHR](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.bamboohr/) - HR management system.
- [ADP](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-adp/) - Payroll and HR integration.
- [UKG (Ultimate Kronos Group)](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-ukg/) - Workforce management.

### Enterprise Communication

- [Microsoft Teams](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.microsoftteams/) - Teams collaboration platform.
- [Slack Enterprise Grid](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.slack/) - Enterprise team collaboration.
- [Zoom](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.zoom/) - Video conferencing integration.
- [Cisco Webex](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-webex/) - Webex collaboration tools.

## AI & LLM Integrations

Integrate AI and large language models into your workflows.

### LLM Providers

- [OpenAI](https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.lmopenai/) - GPT-4, GPT-3.5, and embeddings.
- [Anthropic Claude](https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.lmclaude/) - Claude 3 Opus, Sonnet, and Haiku.
- [Google Gemini](https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.lmgemini/) - Google's Gemini models.
- [Cohere](https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.lmcohere/) - Natural language processing models.
- [Hugging Face](https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.lmhuggingface/) - Access thousands of open-source models.
- [Azure OpenAI](https://docs.n8n.io/integrations/builtin/cluster-nodes/root-nodes/n8n-nodes-langchain.lmazureopenai/) - Microsoft Azure hosted OpenAI.

### Vector Databases

- [Pinecone](https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.vectorstorepinecone/) - Managed vector database for semantic search.
- [Weaviate](https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.vectorstoreweaviate/) - Open-source vector search engine.
- [Qdrant](https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.vectorstoreqdrant/) - High-performance vector database.
- [Chroma](https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.vectorstorechroma/) - Embedding database for LLM apps.
- [Supabase Vector](https://docs.n8n.io/integrations/builtin/cluster-nodes/sub-nodes/n8n-nodes-langchain.vectorstoresupabase/) - PostgreSQL with pgvector extension.

### AI Frameworks

- [LangChain](https://docs.n8n.io/integrations/builtin/cluster-nodes/) - Build LLM applications with chains.
- [LlamaIndex](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-llamaindex/) - Data framework for LLM applications.
- [AutoGPT](https://github.com/n8n-io/n8n-nodes-autogpt) - Autonomous AI agents in n8n.

### AI Services

- [ElevenLabs](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-elevenlabs/) - AI voice synthesis and cloning.
- [Stability AI](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-stability/) - Image generation with Stable Diffusion.
- [Midjourney](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-midjourney/) - AI image generation.
- [AssemblyAI](https://docs.n8n.io/integrations/community-nodes/n8n-nodes-assemblyai/) - Speech-to-text transcription.
- [Whisper API](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.openai/) - OpenAI audio transcription.

## Hosting & Deployment

Options for hosting and deploying n8n.

### Cloud Platforms

- [AWS Deployment Guide](https://blog.n8n.io/deploy-n8n-on-aws/) - Deploy n8n on AWS EC2, ECS, or Lambda.
- [Google Cloud Platform](https://blog.n8n.io/deploy-n8n-on-gcp/) - Deploy on GCP Compute Engine or Cloud Run.
- [Microsoft Azure](https://blog.n8n.io/deploy-n8n-on-azure/) - Deploy on Azure App Service or Container Instances.
- [Linode](https://www.linode.com/marketplace/apps/n8n/n8n/) - Marketplace app deployment.

### PaaS Providers

- [Fly.io](https://fly.io/docs/app-guides/n8n/) - Global edge deployment.
- [Heroku](https://elements.heroku.com/buttons/n8n-io/n8n) - Deploy to Heroku with one click.
- [Coolify](https://coolify.io/) - Self-hostable Heroku alternative.

### Container Orchestration

- [k3s Deployment](https://blog.n8n.io/deploy-n8n-on-k3s/) - Lightweight Kubernetes deployment.
- [Nomad](https://github.com/hashicorp/nomad/tree/main/jobspec/test-fixtures/n8n) - HashiCorp Nomad job specification.

### Self-Hosting

- [Raspberry Pi Deployment](https://blog.n8n.io/run-n8n-on-raspberry-pi/) - Run n8n on ARM devices.
- [Nginx Reverse Proxy](https://docs.n8n.io/hosting/configuration/reverse-proxy/) - Secure n8n behind Nginx.
- [Traefik Configuration](https://blog.n8n.io/traefik-reverse-proxy/) - Use Traefik as reverse proxy.

## Development Tools

Tools for developing custom n8n nodes and integrations.

### Node Development

- [n8n Node Starter](https://github.com/n8n-io/n8n-node-starter) - Boilerplate for creating custom nodes.
- [Node Development Docs](https://docs.n8n.io/integrations/creating-nodes/) - Official guide to node development.
- [TypeScript SDK](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base) - n8n TypeScript SDK and utilities.
- [Node Generator](https://www.npmjs.com/package/create-n8n-node) - Scaffold new custom nodes.

### Testing & Debugging

- [n8n Node Dev Tools](https://www.npmjs.com/package/@n8n/n8n-nodes-dev) - Development utilities and testing helpers.
- [Workflow Testing](https://docs.n8n.io/hosting/environment-variables/test-webhooks/) - Test webhook and execution URLs.
- [Debug Mode](https://docs.n8n.io/hosting/logging-monitoring/debugging/) - Enable detailed logging for troubleshooting.

### SDKs & Libraries

- [n8n Client](https://www.npmjs.com/package/n8n-client) - JavaScript client for n8n API.
- [Python n8n Client](https://pypi.org/project/n8n-client/) - Python wrapper for n8n API.
- [n8n REST API](https://docs.n8n.io/api/) - Official REST API documentation.

## Security & Compliance

Security best practices and compliance resources.

### Authentication

- [Basic Authentication](https://docs.n8n.io/hosting/configuration/user-management/) - Username/password authentication.
- [OAuth 2.0](https://docs.n8n.io/hosting/configuration/oauth/) - OAuth integration for third-party apps.
- [LDAP Integration](https://docs.n8n.io/hosting/configuration/ldap/) - Enterprise directory services.
- [SAML SSO](https://docs.n8n.io/hosting/configuration/saml/) - Single sign-on with SAML.

### Secrets Management

- [Environment Variables](https://docs.n8n.io/hosting/environment-variables/) - Manage credentials securely.
- [HashiCorp Vault](https://blog.n8n.io/integrate-vault/) - External secrets management.
- [AWS Secrets Manager](https://blog.n8n.io/aws-secrets-manager/) - AWS secrets integration.
- [Azure Key Vault](https://blog.n8n.io/azure-key-vault/) - Azure secrets management.

### Compliance

- [GDPR Compliance Guide](https://blog.n8n.io/gdpr-compliance/) - Data protection best practices.
- [SOC 2 Documentation](https://n8n.io/security/) - Security and compliance information.
- [Data Encryption](https://docs.n8n.io/hosting/configuration/encryption/) - Encrypt sensitive workflow data.
- [Audit Logging](https://docs.n8n.io/hosting/logging-monitoring/audit-logs/) - Track user actions and changes.

### Network Security

- [Firewall Configuration](https://docs.n8n.io/hosting/configuration/security/) - Network security best practices.
- [SSL/TLS Setup](https://docs.n8n.io/hosting/configuration/ssl/) - Enable HTTPS for n8n.
- [VPC Deployment](https://blog.n8n.io/deploy-n8n-vpc/) - Isolate n8n in private networks.
- [IP Whitelisting](https://docs.n8n.io/hosting/configuration/ip-whitelist/) - Restrict access by IP address.

## Monitoring & Observability

Tools and techniques for monitoring n8n deployments.

### Monitoring Solutions

- [Prometheus Integration](https://docs.n8n.io/hosting/logging-monitoring/prometheus/) - Metrics collection with Prometheus.
- [Grafana Dashboards](https://grafana.com/grafana/dashboards/n8n/) - Pre-built n8n monitoring dashboards.
- [Datadog Integration](https://blog.n8n.io/monitor-n8n-with-datadog/) - Monitor n8n with Datadog.
- [New Relic](https://blog.n8n.io/n8n-new-relic/) - Application performance monitoring.

### Logging

- [Centralized Logging](https://docs.n8n.io/hosting/logging-monitoring/logging/) - Configure structured logging.
- [Elasticsearch + Kibana](https://blog.n8n.io/n8n-elk-stack/) - ELK stack integration.
- [Loki + Grafana](https://blog.n8n.io/loki-grafana-logging/) - Log aggregation with Loki.
- [CloudWatch Logs](https://blog.n8n.io/cloudwatch-logs/) - AWS CloudWatch integration.

### Alerting

- [PagerDuty Integration](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.pagerduty/) - Incident management alerts.
- [Opsgenie](https://docs.n8n.io/integrations/builtin/app-nodes/n8n-nodes-base.opsgenie/) - Alert and on-call management.
- [Slack Notifications](https://blog.n8n.io/slack-notifications/) - Send alerts to Slack channels.
- [Email Notifications](https://docs.n8n.io/integrations/builtin/core-nodes/n8n-nodes-base.emailsend/) - Email-based alerting.

### Performance

- [Queue Mode](https://docs.n8n.io/hosting/scaling/queue-mode/) - Scale workflows with Redis queue.
- [Performance Tuning](https://docs.n8n.io/hosting/scaling/performance/) - Optimize n8n performance.
- [Database Optimization](https://docs.n8n.io/hosting/configuration/database/) - PostgreSQL tuning for n8n.
- [Caching Strategies](https://blog.n8n.io/n8n-caching/) - Improve workflow execution speed.

## Best Practices & Patterns

Proven patterns and best practices for building workflows.

### Workflow Design

- [Error Handling Patterns](https://blog.n8n.io/error-handling-best-practices/) - Robust error handling strategies.
- [Retry Strategies](https://docs.n8n.io/workflows/error-handling/retry-on-fail/) - Configure automatic retries.
- [Workflow Modularity](https://blog.n8n.io/modular-workflows/) - Build reusable workflow components.
- [State Management](https://blog.n8n.io/workflow-state-management/) - Manage workflow state effectively.

### Performance Optimization

- [Batch Processing](https://blog.n8n.io/batch-processing/) - Process large datasets efficiently.
- [Pagination Strategies](https://blog.n8n.io/api-pagination/) - Handle paginated API responses.
- [Rate Limiting](https://blog.n8n.io/rate-limiting/) - Work within API rate limits.
- [Webhook Optimization](https://blog.n8n.io/webhook-best-practices/) - Optimize webhook-based workflows.

### Security Patterns

- [Credential Management](https://docs.n8n.io/workflows/credentials/) - Store and use credentials securely.
- [Input Validation](https://blog.n8n.io/input-validation/) - Validate user inputs and webhook data.
- [Secure API Calls](https://blog.n8n.io/secure-api-calls/) - Best practices for external API calls.
- [Data Sanitization](https://blog.n8n.io/data-sanitization/) - Clean and sanitize workflow data.

### Scalability

- [Horizontal Scaling](https://docs.n8n.io/hosting/scaling/horizontal-scaling/) - Scale n8n across multiple instances.
- [Queue Mode with Redis](https://blog.n8n.io/queue-mode-redis/) - Distribute workflow execution across workers.
- [Database Scaling](https://blog.n8n.io/database-scaling/) - Scale PostgreSQL for high loads.
- [Microservices Pattern](https://blog.n8n.io/n8n-microservices/) - Build distributed systems with n8n.

## Learning Resources

Educational materials for mastering n8n.

### Courses

- [n8n Academy](https://docs.n8n.io/courses/) - Official free courses for beginners to advanced users.
- [n8n Fundamentals](https://www.youtube.com/playlist?list=PLFzy-BF-ObbwCzDz4Qj-Gt5q2T5-w-aVe) - Video course series on YouTube.
- [Advanced n8n Techniques](https://www.udemy.com/course/n8n-automation/) - Udemy course on advanced workflows.
- [Building n8n Integrations](https://www.youtube.com/playlist?list=PLFzy-BF-ObbzBfxIIvxFrWEHVMq0l0-dj) - Node development tutorials.

### Books & Guides

- [n8n Handbook](https://blog.n8n.io/n8n-handbook/) - Comprehensive guide to n8n workflows.
- [Automation Playbook](https://blog.n8n.io/automation-playbook/) - Real-world automation examples.
- [Self-Hosting Guide](https://blog.n8n.io/self-hosting-guide/) - Complete self-hosting documentation.

### Blogs & Articles

- [n8n Tutorials Blog](https://blog.n8n.io/tag/tutorials/) - Step-by-step tutorials and guides.
- [n8n Community Tutorials](https://community.n8n.io/c/tutorials/) - User-contributed tutorials.
- [Medium n8n Tag](https://medium.com/tag/n8n) - Articles about n8n on Medium.
- [Dev.to n8n Articles](https://dev.to/t/n8n) - Developer tutorials and guides.

### Video Resources

- [n8n Video Library](https://www.youtube.com/c/n8n-io/playlists) - Complete video playlists collection.
- [Workflow Walkthroughs](https://www.youtube.com/playlist?list=PLFzy-BF-ObbwlRCLh6wJ0T4dXvGC-rBbB) - Step-by-step workflow builds.
- [n8n Live Streams](https://www.youtube.com/playlist?list=PLFzy-BF-ObbxJlF-MJhwUVNLY_0Z0rYAU) - Community Q&A and demos.

## Community & Support

Connect with the n8n community.

### Forums & Discussion

- [n8n Forum](https://community.n8n.io/categories) - Discussion categories and topics.
- [Reddit r/n8n](https://www.reddit.com/r/n8n/) - n8n subreddit for discussions.
- [Discord Server](https://discord.gg/n8n) - Real-time chat with community members.
- [Stack Overflow](https://stackoverflow.com/questions/tagged/n8n) - Technical Q&A.

### Social Media

- [Twitter @n8n_io](https://twitter.com/n8n_io) - Official Twitter account.
- [LinkedIn](https://www.linkedin.com/company/n8n-io/) - Company updates and articles.
- [Facebook Group](https://www.facebook.com/groups/n8n.community/) - Community discussions.

### Events & Meetups

- [n8n Webinars](https://n8n.io/webinars/) - Regular online events and workshops.
- [n8n Meetups](https://www.meetup.com/topics/n8n/) - Local community meetups.
- [Community Calls](https://community.n8n.io/c/events/) - Monthly community video calls.

### Contributing

- [Contributing Guide](https://github.com/n8n-io/n8n/blob/master/CONTRIBUTING.md) - How to contribute to n8n.
- [Code of Conduct](https://github.com/n8n-io/n8n/blob/master/CODE_OF_CONDUCT.md) - Community guidelines.
- [GitHub Discussions](https://github.com/n8n-io/n8n/discussions) - Feature requests and discussions.

## Alternatives & Comparisons

How n8n compares to other automation platforms.

### Detailed Comparisons

- [n8n vs Zapier](https://n8n.io/compare/zapier-alternative/) - Feature and pricing comparison.
- [n8n vs Make (Integromat)](https://n8n.io/compare/make-alternative/) - Capabilities and cost analysis.
- [n8n vs Pipedream](https://n8n.io/compare/pipedream-alternative/) - Developer-focused comparison.
- [n8n vs Tray.io](https://n8n.io/compare/tray-alternative/) - Enterprise automation comparison.
- [n8n vs Workato](https://n8n.io/compare/workato-alternative/) - Integration platform comparison.

### Open Source Alternatives

- [Apache Airflow](https://airflow.apache.org/) - Data pipeline orchestration.
- [Temporal](https://temporal.io/) - Durable execution framework.
- [Prefect](https://www.prefect.io/) - Modern workflow orchestration.
- [Kestra](https://kestra.io/) - Declarative orchestration platform.
- [Windmill](https://www.windmill.dev/) - Developer-first workflow engine.

### When to Use n8n

- [Use Cases Guide](https://n8n.io/use-cases/) - Ideal scenarios for n8n.
- [Self-Hosting Benefits](https://blog.n8n.io/why-self-host/) - Advantages of self-hosted automation.
- [Migration Stories](https://blog.n8n.io/tag/migration/) - Companies migrating to n8n.

## Tools & Utilities

Additional tools to enhance your n8n experience.

### Workflow Management

- [n8n-backup](https://github.com/noxify/n8n-backup) - Automated workflow backup tool.
- [n8n-workflow-analyzer](https://github.com/digital-boss/n8n-workflow-analyzer) - Analyze workflow complexity.
- [n8n-workflow-template-generator](https://github.com/digital-boss/n8n-workflow-template-generator) - Generate workflow templates.
- [n8n-workflows-demo](https://github.com/n8n-io/n8n-workflows-demo) - Example workflows repository.

### CLI Tools

- [n8n CLI](https://www.npmjs.com/package/n8n) - Official command-line interface.
- [n8n-node-dev CLI](https://www.npmjs.com/package/n8n-node-dev) - Node scaffolding and development tools.
- [n8n-workflow-cli](https://github.com/quansenB/n8n-workflow-cli) - Export and import workflows via CLI.

### Testing & Quality

- [n8n-workflow-test](https://github.com/digital-boss/n8n-workflow-test) - Automated workflow testing.
- [n8n-validator](https://github.com/digital-boss/n8n-validator) - Validate workflow configurations.
- [n8n-lint](https://github.com/digital-boss/n8n-lint) - Linting for n8n workflows.

### Visualization

- [n8n-workflow-visualizer](https://github.com/digital-boss/n8n-workflow-visualizer) - Generate workflow diagrams.
- [n8n-docs-generator](https://github.com/digital-boss/n8n-docs-generator) - Auto-generate workflow documentation.

### Integration Helpers

- [n8n-postman-collection](https://github.com/n8n-io/n8n-postman-collection) - Postman collection for n8n API.
- [n8n-openapi-spec](https://github.com/n8n-io/n8n/tree/master/packages/cli/src/api/openapi) - OpenAPI specification.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.
