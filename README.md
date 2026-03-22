## 🧠 Conceito do Produto

**Álbum + Scrapbook Digital Interativo**

* Álbum: armazenamento organizado de fotos (tipo Google Photos, mas mais “afetivo”)
* Scrapbook: páginas customizadas (estilo colagem, diário, viagem, relacionamento)
* Diferencial: **memória sensorial (foto + música)** via Spotify

---

## 🔥 Funcionalidade Core (MVP)

### 1. Álbum de Fotos

* Upload de fotos
* Organização por:

  * Evento
  * Data
  * Pessoas
* Capa do álbum

### 2. Scrapbook (principal valor)

* Criar páginas livres (drag-and-drop)
* Adicionar:

  * Fotos
  * Textos (legendas, histórias)
  * Stickers / elementos visuais
* Templates prontos (viagem, namoro, aniversário)

### 3. Integração com Spotify

* Escolher uma música por:

  * Página
  * Álbum inteiro
* Ao abrir:

  * toca automaticamente (preview ou embed)
* Exibir:

  * Capa da música
  * Nome / artista

---

## 💡 Diferenciais (onde você ganha mercado)

### ✨ 1. “Memória Viva”

* Linha do tempo animada (tipo stories)
* Auto-play com música + transições

### ✨ 2. Modo Compartilhamento

* Link público do scrapbook
* Privado com senha
* Compartilhar como:

  * “presente digital”

### ✨ 3. QR Code (ponte físico ↔ digital)

* Gerar QR:

  * Para página específica
  * Para música no Spotify
* Ideal para:

  * imprimir scrapbook físico
  * colar em álbuns reais

---

## 🚀 Funcionalidades que elevam MUITO o produto

### 🤖 1. IA de criação automática

* Usuário sobe fotos → sistema gera scrapbook automático:

  * seleciona melhores fotos
  * cria layout
  * sugere música

### 🎵 2. Sugestão inteligente de música

* Baseado em:

  * data (ex: anos 2000)
  * tipo de evento (viagem, festa)
  * sentimento do texto

### 👫 3. Scrapbook colaborativo

* Várias pessoas editam o mesmo álbum
* Perfeito pra:

  * casamentos
  * viagens em grupo

### 📦 4. Exportação física

* Gerar PDF pronto para impressão
* Ou integração com gráfica futuramente

---

## 💰 Monetização

* Freemium:

  * grátis com limite de álbuns
* Premium:

  * templates exclusivos
  * músicas ilimitadas
  * exportação HD/PDF
* Venda de:

  * “álbuns presenteáveis”

---

## 🧩 Stack (pensando no seu contexto Laravel)

* Backend: Laravel (multi-tenant futuramente)
* Front:

  * Livewire + Alpine (rápido pra MVP)
  * ou Vue se quiser algo mais fluido (drag-drop melhor)
* Storage:

  * S3 ou compatível
* Integração:

  * API do Spotify

---

## ⚠️ Pontos de atenção

* Autoplay do Spotify tem limitações (browser bloqueia som automático)
* Direitos de música → usar embed oficial / preview
* Performance (muitas imagens + animação)

---

## 🧨 Ideia bônus (diferencial forte mesmo)

“**Revivência**”:

* botão “reviver momento”
* toca música + anima scrapbook como um mini filme
