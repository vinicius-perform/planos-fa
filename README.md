# Landing Page de Planos Comerciais — FAZENDO ACONTECER®

Uma landing page de página única (single page), moderna, premium, ultra-rápida e totalmente responsiva, desenvolvida sob medida para a apresentação dos planos comerciais da **FAZENDO ACONTECER®**.

---

## 🎯 Objetivo & Proposta de Valor
Apresentar de forma ultra-direta, limpa e com alto impacto visual os dois formatos de parceria comercial da **FAZENDO ACONTECER®**, posicionando os planos imediatamente após o cabeçalho oficial:
- **Performance (Plano de Entrada):** Estrutura essencial para operação, marketing e acompanhamento.
- **Exclusivo (Plano Premium & Mais Estratégico):** Operação mais robusta, com estrutura comercial ampliada e modelo premium.

---

## 💎 Identidade Visual & Design System
- **Paleta de Cores:**
  - **Verde-Lima Neon (`#CCFF00`):** Ponto focal de alta energia e inovação, característico da marca.
  - **Preto Nobre / Grafite (`#0B0F17` / `#111827`):** Autoridade, contraste e sofisticação institucional.
  - **Branco Puro (`#FFFFFF`):** Cards e áreas de respiro com máxima clareza.
  - **Cinza Suave (`#F8FAFC`):** Superfície de fundo com malha geométrica sutil (dot pattern).
  - **Cinzas Neutros (`#64748B` / `#E2E8F0`):** Textos secundários, bordas milimétricas e divisórias.
- **Tipografia:** **Plus Jakarta Sans** (Google Fonts), sans-serif geométrica de padrão internacional para marcas de SaaS e Growth.
- **Microinterações:** Efeitos sutis de elevação ao passar o mouse (`hover:-translate-y-1`), transições com curva de aceleração refinada e feedback visual nos CTAs.

---

## 📋 Comparativo dos Planos Apresentados

| Característica | **Performance** | **Exclusivo** (Destaque) |
| :--- | :--- | :--- |
| **Posicionamento** | Plano de Entrada | Plano Premium & Mais Estratégico |
| **Investimento** | **R$ 4.488/mês** | **R$ 7.488/mês** + variável de 5% |
| **Tráfego Meta** | ✅ Incluso | ✅ Incluso |
| **Comercial Interno** | — | ✅ **Incluso (Diferencial Exclusivo)** |
| **Social media** | ✅ Incluso | ✅ Incluso |
| **Implementação de CRM**| ✅ Incluso | ✅ Incluso |
| **Mensalidade dot.Sales**| ✅ Incluso | ✅ Incluso |
| **Acompanhamento em Tempo Real** | ✅ Incluso | ✅ Incluso |
| **CTA Principal** | `Quero o Performance` | `Quero o Exclusivo` |

---

## 🛠️ Descritivo dos Serviços Inclusos (Seção Abaixo da Tabela)
Abaixo dos cards de preços, foi implementada uma grade modular com 6 cards detalhando o escopo operacional de cada serviço:
1. **Tráfego Meta:** Gestão e otimização contínua de anúncios no ecossistema Meta Ads (Facebook & Instagram), segmentação estratégica e geração de leads prontos para compra.
2. **Comercial Interno (Exclusivo):** Estrutura dedicada de qualificação, atendimento e fechamento ativo de leads com aplicação de scripts comerciais e follow-up ágil.
3. **Social media:** Construção de autoridade de marca, posicionamento visual e narrativas de conteúdo alinhadas ao momento de compra do cliente.
4. **Implementação de CRM:** Mapeamento completo da jornada do lead, padronização do pipeline de vendas e automações para eliminar perdas de oportunidades.
5. **Mensalidade do dot.Sales:** Plataforma e infraestrutura tecnológica já incluídas no plano para operação comercial integrada, sem surpresas na fatura.
6. **Acompanhamento em Tempo Real:** Dashboards dinâmicos e métricas vitais (CPL, conversão por etapa, receita) para decisões orientadas a dados.

---

## 🚀 Como Executar Localmente

### Opção 1: Via Servidor Local Node.js (Recomendado)
O servidor já está configurado. Para iniciar quando quiser:
```bash
npm start
# ou
node server.js
```
Acesse no seu navegador: **[http://localhost:3000](http://localhost:3000)**

### Opção 2: Abrir diretamente no Navegador (Zero dependências)
Dê um duplo clique no arquivo `index.html` ou abra com o seu navegador favorito (Chrome, Edge, Firefox, Safari).

---

## 📲 Como Configurar o WhatsApp de Destino

Os botões de CTA já vêm pré-formatados com mensagens comerciais personalizadas para cada plano.

### Forma 1: Pela URL (Dinâmico)
Você pode enviar um link com o número desejado diretamente na URL:
```text
https://suapagina.com/?phone=5511999999999
```
A página atualizará todos os botões automaticamente!

### Forma 2: No Código
Abra o arquivo `index.html` e edite a linha que contém:
```javascript
const DEFAULT_PHONE = "5511999999999"; // Substitua pelo número com DDI e DDD
```

---

## 🌐 Publicação / Hospedagem em 1 Clique

Como o projeto é 100% estático (HTML5 + Tailwind CSS via CDN + Google Fonts), você pode hospedá-lo gratuitamente em qualquer plataforma:
- **Vercel:** Arraste a pasta ou conecte seu repositório no GitHub.
- **Netlify:** Arraste a pasta diretamente para o dashboard do Netlify Drop.
- **GitHub Pages:** Ative a branch `main` nas configurações do repositório.
- **Servidor Próprio / WordPress / cPanel:** Basta subir o arquivo `index.html` na raiz do domínio ou subdomínio (ex: `precos.fazendoacontecer.com.br`).
