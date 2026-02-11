# 📚 VeroClass AI - Documentação Oficial

![VeroClass AI](https://cdn.inglescurso.com.br/Veroclass/2026/01/logo-veroClass-light_1769605754.png)

## 🌐 Visualizar Documentação

**GitHub Pages:** [samucamg.github.io/VeroClassAi](https://samucamg.github.io/VeroClassAi)

**Cloudflare Pages (Recomendado):** Em breve

---

## 🎯 Sobre o VeroClass AI

O **VeroClass AI** é a evolução do Gateway Pro, transformando-se em uma plataforma educacional completa com recursos avançados de **Inteligência Artificial**. Desenvolvido especialmente para **escolas de idiomas** e instituições de ensino.

### ✨ Principais Recursos

- 🤖 **Emma AI Contextual** - Agente inteligente com memória completa
- 🎙️ **Reconhecimento de Voz** - Atividades de pronúncia com Whisper AI
- 🎬 **Bunny CDN Premium** - Streaming com DRM, Chromecast e AirPlay
- 💳 **7 Gateways Integrados** - Asaas, Stripe, PayPal, EFI, PushinPay, Woovi, Mercado Pago
- 🔄 **Automação Total** - Geração automática de resumos, quiz e atividades
- 📱 **100% Mobile** - Totalmente responsivo com players customizados

---

## 📂 Estrutura do Repositório

```
VeroClassAi/
├── index.html              # Documentação completa (GitHub Pages)
├── README.md               # Este arquivo
└── assets/                 # Imagens e recursos (futuro)
```

---

## 🚀 Como Usar no GitHub Pages

### 1. Publicar via GitHub Pages

```bash
# 1. Clone o repositório
git clone https://github.com/samucamg/VeroClassAi.git
cd VeroClassAi

# 2. Configure GitHub Pages
# Vá em: Settings → Pages → Branch: main → / (root) → Save
```

### 2. Acessar Documentação

Após configuração, acesse:
```
https://samucamg.github.io/VeroClassAi
```

---

## 🌐 Deploy em Cloudflare Pages (Recomendado)

### Por que Cloudflare Pages?

✅ **Domínio customizado grátis com SSL**  
✅ **CDN global automático**  
✅ **Deploy automático a cada push**  
✅ **Zero configuração**

### Passo a Passo:

1. **Acesse:** [dash.cloudflare.com](https://dash.cloudflare.com)
2. **Workers & Pages** → **Create application** → **Pages**
3. **Connect to Git** → Conecte GitHub
4. **Selecione:** `samucamg/VeroClassAi`
5. **Configure:**
   ```
   Production branch: main ou master
   Build command: (deixe vazio)
   Build output directory: /
   ```
6. **Save and Deploy**

### Domínio Customizado:

No Cloudflare Pages → **Custom domains** → Adicione: `docs.veroclass.com.br`

---

## 📊 Seções da Documentação

### 📋 Principais Seções

1. **Visão Geral** - Introdução e diferenciais
2. **IA & Automação** - Emma AI, Whisper, atividades automáticas
3. **Bunny CDN** - Streaming profissional com DRM e Chromecast
4. **Sistema Comercial** - Checkout, gateways, planos, combos
5. **Área do Aluno** - Interface moderna, vídeos multi-fonte
6. **Branding** - Personalização em 2 níveis (Admin + Infoprodutor)
7. **Integrações** - Evolution API, UTMfy, Webhooks
8. **Automações** - 5 automações via WhatsApp e Email
9. **Segurança** - 10 camadas de proteção
10. **Técnico** - Stack tecnológico e banco de dados

---

## 🎨 Visual e Design

### Paleta de Cores

- **Azul Primário:** `#1e3a8a`, `#1e40af`, `#60a5fa`
- **Verde (Sucesso):** `#065f46`, `#047857`, `#10b981`
- **Vermelho (Avisos):** `#7c2d12`, `#9a3412`, `#f97316`
- **Background:** `#0f1419`, `#1a1f2e`, `#111827`

### Responsividade

✅ **Desktop** - Layout completo com grid  
✅ **Tablet** - Grid adaptativo  
✅ **Mobile** - Single column com navegação simplificada

---

## 📱 Recursos Mobile

- **Player de áudio** com controle de velocidade (0.5x - 2x)
- **Gravação de áudio** nativa para pronúncia
- **Interface touch-friendly** otimizada
- **Progressive Web App (PWA)** ready

---

## 🔐 Segurança

### 10 Camadas de Proteção

1. Login único com detecção de múltiplas sessões
2. Proteção anti-DevTools (bloqueio F12)
3. Watermark dinâmico em vídeos e PDFs
4. URLs assinadas com token SHA256
5. MediaCage DRM (Widevine/FairPlay)
6. DRM em PDFs (bloqueio de impressão/cópia)
7. Rate limiting contra força bruta
8. Logs de segurança completos
9. CSRF protection em formulários
10. SQL injection prevention (PDO)

---

## 🔧 Stack Tecnológico

### Backend
- PHP 8.1+
- MySQL 8.0
- PDO (Prepared Statements)

### Frontend
- HTML5
- TailwindCSS
- JavaScript ES6+

### IA APIs
- OpenAI GPT-4
- Whisper AI
- Text-to-Speech (TTS)

### CDN & Streaming
- Bunny CDN
- MediaCage DRM
- Adaptive HLS

### Integrações
- Evolution API (WhatsApp)
- UTMfy (Tracking)
- Webhooks

---

## 📦 Banco de Dados

**45+ tabelas** incluindo:

- `produtos`, `produto_ofertas`, `cupons`, `produtos_combos`
- `cursos`, `modulos`, `aulas`, `aula_arquivos`
- `avaliacoes`, `avaliacoes_questoes`, `tentativas_pronuncia`
- `emma_conversations`, `atividades_h5p`
- `telemetria_sessoes`, `telemetria_eventos`
- `branding_config`, `smtp_config`
- `security_logs`, `login_attempts`

---

## 🗺️ Roadmap 2026

| Data | Funcionalidade | Status |
|------|---------------|---------|
| **11/02** | Branding + Controle de download | 🚧 Esta Semana |
| **11-13/02** | Automações Evolution API | 🚧 Esta Semana |
| **12/02** | Novos gateways | 🚧 Esta Semana |
| **13/02** | Gateway Woovi (PIX) | 🚧 Esta Semana |
| **Março-Abril** | Fórum, Chat, Gamificação | 📅 Planejado |
| **2º Semestre** | App Mobile, Afiliados | 🔮 Futuro |

---

## 💰 Bunny CDN - Diferencial Competitivo

### Por que Bunny CDN?

✅ **10x mais barato** que AWS/Azure  
✅ **CDN Global** - 127+ localizações  
✅ **DRM Incluído** - MediaCage (Widevine/FairPlay)  
✅ **Chromecast & AirPlay** nativos  

### Comparação de Custos

| Provedor | Streaming | Armazenamento |
|----------|-----------|---------------|
| **Bunny CDN** | $0.005/GB | $0.01/GB |
| AWS CloudFront | $0.085/GB | $0.023/GB |
| Azure CDN | $0.081/GB | $0.020/GB |

**Economia Real:** Para 1TB/mês → Bunny $5 vs AWS $85 (**17x mais barato!**)

---

## 📞 Contato

**Desenvolvedor:** Samuel de Sousa Santos  
**Email:** samuel@inglescurso.com.br  
**Website:** [cursos.inglescurso.com.br](https://cursos.inglescurso.com.br)  
**GitHub:** [@samucamg](https://github.com/samucamg)

---

## 📄 Licença

© 2026 VeroClass AI. Todos os direitos reservados.

---

## 🎯 Ideal Para

✅ **Escolas de Idiomas** - Pronúncia, ditado, Emma AI como tutora  
✅ **Cursos Online** - Checkout inteligente, 7 gateways  
✅ **Treinamentos Corporativos** - Telemetria, relatórios  
✅ **Infoprodutores** - Combos, cupons, branding próprio  

---

## 🌟 Diferenciais do VeroClass AI

1. **Emma AI Contextual** - Conhece cada aluno individualmente
2. **Atividades Automáticas** - Resumo, quiz, pronúncia, ditado
3. **Bunny CDN Premium** - Streaming ultra rápido e barato
4. **Branding em 2 Níveis** - Admin global + Infoprodutor
5. **Automações WhatsApp** - 5 tipos de mensagens automáticas
6. **100% Mobile** - Players de áudio com velocidade ajustável
7. **Segurança Máxima** - 10 camadas de proteção
8. **7 Gateways** - Todos os principais do mercado

---

**⭐ Se este projeto foi útil, deixe uma estrela!**
