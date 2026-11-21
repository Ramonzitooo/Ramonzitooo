# 👋 Olá! Eu sou Ramon Cavalcanti (`@Ramonzitooo`)

**Product Builder · Design Engineering · Offline-First Web Apps & Adobe Illustrator Automation**

Desenvolvo ferramentas práticas focadas em **produtividade real, matemática determinística, design systems de alto contraste e privacidade client-side (Zero-Knowledge)** — prontas para usar no navegador ou instalar diretamente sem burocracia.

![React 19](https://img.shields.io/badge/React_19-TypeScript-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite_8-Tailwind_v4-646CFF?style=flat-square&logo=vite&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-Offline_First-25D366?style=flat-square)
![ExtendScript](https://img.shields.io/badge/ExtendScript-Adobe_Illustrator_ES3-FF9A00?style=flat-square&logo=adobeillustrator&logoColor=white)
![WCAG 2.2](https://img.shields.io/badge/WCAG_2.2-AA_Accessible-15803D?style=flat-square)

---

## 🚀 Projetos em Destaque (Acesso Online & Downloads)

| Projeto | Tipo | O que faz | Acesso / Download Direto |
| :--- | :--- | :--- | :--- |
| **[QR PRO](https://github.com/Ramonzitooo/GERADOR-DE-QR-CODE)** | Web App & PWA Offline (`HTML5` + `React 19`) | Gerador ISO/IEC 18004 (11 formatos incl. PIX CRC16, vCard, Wi-Fi), Studio de Cartões 90×50mm @ 300 DPI, Scanner Óptico, Lote Web Worker e Histórico Incógnito | 🌐 [Abrir Online](https://ramonzitooo.github.io/GERADOR-DE-QR-CODE/) · ⬇️ [Studio Standalone](https://github.com/Ramonzitooo/GERADOR-DE-QR-CODE/releases/latest/download/qr-pro-studio-standalone.html) · 📦 [PWA (.zip)](https://github.com/Ramonzitooo/GERADOR-DE-QR-CODE/releases/latest/download/qr-pro-vanilla-pwa-v3.8.zip) |
| **[FinTrack](https://github.com/Ramonzitooo/fintrack)** | App Financeiro (`React 19` + `TypeScript`) | Controle financeiro pessoal Zero-Knowledge: orçamento 50/30/20, Diária Segura, Bancos (% CDI composto), Caixinhas & FIRE, Contracheque CLT (INSS/IRRF + Horas de Vida), Cartões, Envelopes e Dívidas | 🌐 [Abrir Online](https://ramonzitooo.github.io/fintrack/) · ⬇️ [App Standalone (.html)](https://github.com/Ramonzitooo/fintrack/releases/latest/download/fintrack-standalone.html) · 🔒 [Edição Vault (.html)](https://github.com/Ramonzitooo/fintrack/releases/latest/download/fintrack-legacy-vault.html) |
| **[Suíte Scripts Illustrator](https://github.com/Ramonzitooo/illustrator-scripts-suite)** | 8 Scripts ExtendScript (`ES3` · `CS6 → CC 2026`) | Ecossistema de 8 ferramentas nativas para Adobe Illustrator com Live Preview, preservação de Pantone (`SpotColor`), CMYK `K:100` e Undo atômico (`Ctrl+Z`) | 📦 [Baixar Suíte Completa (.zip)](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/illustrator-scripts-suite-gold.zip) · 📂 [Ver Todos os Downloads](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest) |

---

## 🧩 Catálogo de Ferramentas & Recursos

### 1. ◼️ [QR PRO — Gerador, Studio de Cartões & Scanner Universal](https://github.com/Ramonzitooo/GERADOR-DE-QR-CODE)
Aplicação 100% client-side com duas versões sincronizadas (**Vanilla PWA single-file** + **React 19 Studio**):
- **`[01] GERADOR` (11 Protocolos)**: WhatsApp (com DDI `55` automático), URL segura, **PIX BACEN** (CRC16-CCITT `0xFFFF`), Wi-Fi, vCard 4.0, iCalendar, E-mail, SMS, Telefone, GPS e Texto; personalização de módulos, olhos, molduras, logotipo central (ECC `'H'` automático) e exportação SVG / PNG até `3600px`.
- **`[02] CARTÕES` (90×50mm @ 300 DPI)**: 4 temas prontos, sangria técnica de 3mm, marcas de corte, alternância vCard/WhatsApp e exportação de equipes em `.zip`.
- **`[03] SCANNER`**: Câmera ao vivo + filtro Alto Contraste 200% + captura nativa offline (`capture="environment"`) + decodificação reversa que preenche os campos do Gerador.
- **`[04] HISTÓRICO` & `[05] LOTE`**: Até 100 registros locais com Modo Incógnito, geração de até 5.000 códigos em lote via **Web Worker** e assistente Gemini opcional (sem chave embutida).

### 2. 💰 [FinTrack — Controle Financeiro Pessoal & Patrimonial](https://github.com/Ramonzitooo/fintrack)
Plataforma *Zero-Knowledge* que inicia zerada (`R$ 0,00`) e opera 100% localmente no dispositivo:
- **Visão Geral & Orçamento 50/30/20**: Saldo Livre Real, Patrimônio Líquido, Cobertura de Reserva e teto antifrágil da **Diária Segura**.
- **Bancos & Caixinhas CDI / FIRE**: Juros compostos exatos $(1+i)^{1/12}-1$ com IR regressivo, transferência Pix interna, Reserva de Emergência e Bússola FIRE.
- **Contracheque CLT & Anti-Impulso**: Cálculo automático de **INSS e IRRF oficiais** + calculadora de **Horas de Vida** para compras.
- **Cartões, Despesas, Envelopes & Dívidas**: Melhor cartão pelo prazo corte/vencimento, Simulador À Vista vs. Parcelado + CDI, molde mensal automático, `Ctrl + K` por linguagem natural e backups `.json` / `.csv` protegidos (ou cofre **AES-GCM 256-bit** na versão standalone clássica).

### 3. 🎨 [Suíte de Scripts Profissionais para Adobe Illustrator (8 Ferramentas)](https://github.com/Ramonzitooo/illustrator-scripts-suite)
| # | Ferramenta | O que ela tem | Download Direto |
| :---: | :--- | :--- | :---: |
| **1** | **Universal Grid Brockmann `v6.5`** | Grid suíço modular, *Snap to Baseline*, Modo Estúdio (`printable=false`), rótulos `A..Z, AA...` e múltiplas pranchetas | [`.jsx`](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/Universal-Grid-Brockmann.jsx) |
| **2** | **BentoGrid Generator `v4.5`** | Layouts Bento UI (Apple/Linear/Raycast), *Fit to Selection*, borda `1pt`, `SpotColor` e exportador CSS Grid / Tailwind | [`.jsx`](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/BENTOGRID.jsx) |
| **3** | **Color Shuffler Ultra `v3.0`** | Roda cromática, gradientes $0^\circ\text{–}360^\circ$, *Anti-Clumping* (Graph-Coloring), morfologia 3D, Smart Stroke e *Swatches* | [`.jsx`](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/Color-Shuffler.jsx) |
| **4** | **Gerador QR Pro `v4.5`** | Vetor puro ISO 18004, PIX EMVCo/CRC16, 11 tipos, CMYK `K:100`, Pantone, *Fit to Selection* e Lote CSV | [`.jsx`](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/gerador_qr_illustrator.jsx) |
| **5** | **Nuvem de Palavras Pro `v2.0`** | Espiral de Arquimedes + colisão AABB, **Modo Logo Central**, fontes do doc (`★`), Re-Seed, +250 stop words PT-BR e curvas | [`.jsx`](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/Nuvem-de-Palavras.jsx) |
| **6** | **Halftone Pro `v2.0`** | Grade hexagonal equilátera real, 6 geometrias, luminância real em `SpotColor` e unificação em `CompoundPath` | [`.jsx`](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/Halftone.jsx) |
| **7** | **Block Text `v3.0`** | Alinhamento tipográfico por largura com ritmo vertical rígido, auto-encaixe em caixa guia, *Swatches* e curvas | [`.jsx`](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/BLOCK-TEXT.jsx) |
| **8** | **Guias de Margem Pro `v3.0`** | Margens, sangria, marcas de corte reais (`0.5pt K:100`), páginas espelhadas (*Spreads*) e Cânone Van de Graaf | [`.jsx`](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/Guias-de-Margem.jsx) |

> Baixe a suíte completa com o instalador automático para Windows (`.bat`) aqui: **[illustrator-scripts-suite-gold.zip](https://github.com/Ramonzitooo/illustrator-scripts-suite/releases/latest/download/illustrator-scripts-suite-gold.zip)**

---

## 🛡️ Padrões de Engenharia & Segurança

- **Privacidade por Padrão**: Aplicações web 100% client-side, sem coleta de dados, sem trackers e sem credenciais embutidas.
- **Acessibilidade & Qualidade**: Conformidade **WCAG 2.2 AA**, suporte a temas Claro/Escuro, sanitização defensiva (OWASP XSS / CWE-1236 / Prototype Pollution) e suítes de testes automatizados em todos os projetos.
