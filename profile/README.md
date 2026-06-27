<div align="center">
  <img src="https://app.zervanor.com/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Fzervanor-logo.9bf18c90.png" alt="Zervanor Logo" width="60%" style="background-color:#0C0C0D; padding:15px" />
  
  <h3>Ready-made automations and the AI agents that run them, on one platform.</h3>
  <p><em>Hazır iş operasyonları ve bunları çalıştıran yapay zeka ajanları tek bir platformda.</em></p>

  <p>
    <a href="https://zervanor.com"><strong>Website</strong></a> •
    <a href="https://discord.gg/zervanor"><strong>Discord</strong></a> •
    <a href="https://www.linkedin.com/company/zervanor"><strong>LinkedIn</strong></a> •
    <a href="https://twitter.com/zervanor"><strong>Twitter / X</strong></a> •
    <a href="mailto:info@zervanor.com"><strong>Contact</strong></a>
  </p>
</div>

---

## 🚀 What is Zervanor?

**Zervanor** is a production-grade enterprise solution factory designed for seamless business operations. Where legacy automation systems (like Zapier, Make, and n8n) hand you a blank canvas to wire up yourself, Zervanor delivers **finished, ready-to-deploy operations** in a single click.

It brings together your applications, visual workflow engines, and autonomous AI agents into a unified, secure, and cost-effective runtime.

### 🌟 Key Pillars & Features

*   ⚡ **Finished Operations, Not a Blank Canvas**
    Skip the builder complexity. Browse a catalog of pre-built Solution Templates tailored to e-commerce, customer support, and sales, connect your apps, and deploy in minutes.
*   🧠 **Smart Model Routing & Gateway**
    A unified model catalog of cloud, platform, and local/on-device models. Includes named routers with automatic failovers and a server-side gateway that keeps your API keys secure and monitors token consumption.
*   💻 **Remote & Local Execution**
    Run the same agent on your own server or local machine using the **Zervanor Desktop App** or headless CLI. Outbound-only connectivity means it works seamlessly behind firewalls without public IPs.
*   🤖 **Governed AI Agent Workforce**
    Deploy long-running AI agents as isolated pods on a governed runtime. Archetypes, digital roles, and watchers work together with human-in-the-loop confirmation safety.
*   🔌 **Versioned Connector Catalog**
    Over 66+ certified, schema-validated integrations (Salesforce, Notion, Slack, Stripe, etc.) where every connector automatically projects as a tool for your AI agents.
*   💰 **Flat Outcome-Based Pricing**
    Flat monthly subscription plans with agent hosting included. No per-step or per-task billing taxes.

---

## 🚀 Zervanor Nedir?

**Zervanor**, işletmelerin operasyonel iş akışlarını uçtan uca otomatikleştiren kurumsal düzeyde bir çözüm fabrikasıdır. Geleneksel entegrasyon araçları (Zapier, Make veya n8n) size sıfırdan kurmanız gereken boş bir tuval sunarken, Zervanor **bitmiş ve hemen devreye alınmaya hazır iş operasyonları** sunar.

Uygulamalarınızı, görsel iş akışı motorlarını ve otonom yapay zeka ajanlarını (AI agents) güvenli ve ölçeklenebilir tek bir çalışma zamanında (runtime) birleştirir.

### 🌟 Temel Özellikler

*   ⚡ **Hazır Operasyonlar (Boş Tuval Değil)**
    Sıfırdan akış tasarlama karmaşasına son verin. E-ticaret, destek ve satış odaklı hazır Çözüm Şablonlarını seçin, uygulamalarınızı bağlayın ve tek tıkla çalıştırın.
*   🧠 **Akıllı Model Yönlendirme ve Gateway**
    Bulut ve cihaz-üstü modellerin tek kataloğu. Hata durumlarında otomatik olarak diğer modele geçiş sağlayan (fallback) isimli router'lar ve API anahtarlarınızı güvende tutan sunucu-taraflı gateway.
*   💻 **Uzak Cihazlar ve Yerel Çalıştırma**
    Aynı agent'ı bulutta veya **Zervanor Masaüstü Uygulaması** / CLI ile kendi makinenizde çalıştırın. Dışa-bağlantılı mimarisi sayesinde güvenlik duvarı (firewall) arkasında, port açmaya gerek kalmadan çalışır.
*   🤖 **Yönetilebilir Yapay Zeka İş Gücü**
    İzole Kubernetes pod'ları olarak çalışan bilişsel arketipler, dijital roller ve ortam gözcüleri. Bir veri değişmeden önce insan onay adımı ile maksimum güvenlik sağlar.
*   🔌 **Versiyonlu Konnektör Kataloğu**
    Kanonik şemalara göre doğrulanmış 66+ hazır bağlantı (Stripe, GitHub, Slack, Salesforce vb.). Sertifikalandırılmış her konnektör, yapay zeka ajanları için anında birer "araç" (tool) haline gelir.
*   💰 **Sabit Aylık Ücretlendirme**
    Adım veya görev başına sürpriz faturalar yok. Agent barındırma dahil sabit aylık planlarla operasyon maliyetlerinizi öngörülebilir kılın.

---

## 💡 Core Concepts / Temel Kavramlar

### 🤖 What is an Agent? / Agent (Ajan) Nedir?

*   **English:** In Zervanor, an **Agent** is the platform's atomic deployment unit. It is a manifest-defined (`agent.manifest.json`), deployable, and capability-advertising component running as an isolated container workload (managed via Kubernetes in the cloud or via the **Zervanor Desktop App / CLI** locally).
    *   **Autonomous & Event-Driven:** Declares its triggers, actions, and UI interaction surface in its manifest, and participates in workflows via `CloudEvents`.
    *   **Secure & Auth-Ready:** Accesses platform APIs using dedicated organization-scoped agent tokens (`zrv_agt_*`).
    *   **Hybrid AI Runtimes:** Can run inference globally in the cloud or leverage local, on-device LLMs (e.g., Llama 3) via the Desktop runtime outbound streams.
*   **Türkçe:** Zervanor'da bir **Agent (Ajan)**, platformun bağımsız olarak dağıtılabilen en küçük çalışma zamanı (runtime) birimidir. `agent.manifest.json` dosyasıyla tanımlanan bu birimler, bulutta izole Kubernetes pod'larında ya da yerelde **Zervanor Masaüstü Uygulaması / CLI** aracılığıyla çalışır.
    *   **Otonom ve Olay-Güdümlü:** Kendi tetikleyicilerini, eylemlerini ve arayüz yeteneklerini manifestiyle beyan eder; akışlara `CloudEvents` standartlarıyla katılır.
    *   **Güvenli Erişim:** Platform kaynaklarına erişmek için organizasyona özel olarak üretilen güvenli ajan token'larını (`zrv_agt_*`) kullanır.
    *   **Hibrit Çalışma:** Buluttaki LLM modellerini kullanabileceği gibi, Masaüstü uygulaması üzerinden bilgisayarınızdaki yerel modellerden (on-device LLMs) de yararlanabilir.

### 🔌 What is a Connector? / Connector (Konnektör) Nedir?

*   **English:** A **Connector** is a versioned, schema-validated integration pack built to an atomic-unit standard. Connectors dictate how the platform talks to third-party APIs (like Stripe, Slack, Salesforce, GitHub) and automatically transform raw inbound webhooks into system-wide events.
    *   **Definition vs. Connection:** A *Connector Pack* defines auth rules (OAuth2, API keys) and request mappings. When connected, it instantiates a runtime *Connector* holding encrypted credentials for that specific organization.
    *   **Automatic Agent Tooling:** A key architectural advantage is that **every certified Connector automatically projects as a tool for AI Agents**. If your organization has an active Salesforce connector, your AI agent can query leads using it instantly.
*   **Türkçe:** Bir **Connector (Konnektör)**, harici servislerle (Stripe, Slack, Salesforce, GitHub vb.) entegrasyon kurmayı sağlayan, şema doğrulamalı ve versiyonlanmış entegrasyon paketleridir. Gelen ham webhook verilerini normalize edilmiş sistem olaylarına dönüştürür.
    *   **Şablon vs. Canlı Bağlantı:** *Connector Pack* kimlik doğrulama kurallarını (OAuth2, API Anahtarları) ve istek şemalarını tanımlar. Bağlantı kurulduğunda ise şifrelenmiş kimlik bilgilerini barındıran canlı bir *Connector* nesnesi oluşur.
    *   **Ajan Yeteneğine Dönüşüm:** Zervanor mimarisinin en büyük avantajı, **sertifikalı her konnektörün yapay zeka ajanları için otomatik olarak çağrılabilir birer araca (tool) dönüşmesidir**. Aktif bir Salesforce konnektörünüz varsa, yapay zeka ajanınız bunu kullanarak doğrudan veri sorgulayabilir.

<!-- ---

## 🛠️ The Zervanor Open Source Stack

We build in public! Explore the repositories that power the Zervanor platform:

*   📂 **[zervanor-sdk](https://github.com/zervanor/zervanor-sdk)** — The official TypeScript/JavaScript SDK to build, test, and customize event-driven AI agents.
*   📂 **[agents](https://github.com/zervanor/agents)** — Core agent definitions, cognitive archetypes, and watcher templates.
*   📂 **[connectors](https://github.com/zervanor/connectors)** — Sourced and versioned API integrations built to an atomic-unit standard.
*   📂 **[zervanor-desktop](https://github.com/zervanor/zervanor-desktop)** — The Electron-based runtime host to run agents and local LLMs on your own machine.
*   📂 **[zervanor-host](https://github.com/zervanor/zervanor-host)** — Orchestrator and agent manager for cross-device remote execution.

--- -->
<div align="center">
  <sub>© 2026 Zervanor — a product of <strong><a href="https://github.com/inisiyatifdev">Inisiyatif Tech Studio</a></strong>. All rights reserved.</sub>
</div>
