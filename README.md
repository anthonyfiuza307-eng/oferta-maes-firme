# 🌸 Protocolo Mães Firmes - Landing Page de Alta Conversão (Clean Health)

Página de vendas de alta conversão (Direct Response / CRO) refinada para o infoproduto **Protocolo Mães Firmes** (reabilitação de diástase pós-parto, ativação neuromuscular MANP e recuperação corporal feminina).

---

## 🚀 Como Visualizar a Página

1. Abra a pasta do projeto: `oferta MAES FIRME`.
2. Dê **dois cliques** no arquivo [`index.html`](./index.html) para abrir diretamente no seu navegador (Chrome, Edge, Safari, etc.).
3. Não requer instalação de servidores ou dependências para rodar.

---

## 🛠️ Como Inserir Seus Links de Checkout (Kiwify, Hotmart, Braip, etc.)

No final do arquivo [`index.html`](./index.html), localize o bloco de script com a constante `CHECKOUT_CONFIG`:

```javascript
const CHECKOUT_CONFIG = {
  basico: "https://pay.kiwify.com.br/SEU_LINK_34",   // Plano Básico (R$ 34,90)
  premium: "https://pay.kiwify.com.br/SEU_LINK_47"   // Plano Completo (R$ 47,90)
};
```

Basta substituir as URLs com as suas chaves/links de checkout e salvar o arquivo.

---

## 💎 Refatoração de UI/UX, CRO e Responsividade

1. **Barra de Escassez e Timer (Topo):**
   - Fundo nobre em vinho escuro com gradiente sutil.
   - Mensagem: *"⏱️ Último dia para garantir o desconto de lançamento de R$ 500 por apenas R$ 34,90"*.
   - **Countdown Regressivo Dinâmico:** Sincronizado com o **Horário de Brasília (UTC-3)**, encerrando automaticamente às 23:59:59 do dia atual no formato de badges `[HH] : [MM] : [SS]`.

2. **Harmonia Visual & Paleta Clean Health:**
   - **Fundo Principal:** Bege neutro / Off-white suave (`#FDFBF7`) que transmite calma, cuidado materno e autoridade médica/científica.
   - **Tipografia:** Grafite escuro (`#1F2937`) para contraste absoluto e leitura confortável.
   - **Tons de Apoio:** Vinho suave e rosé queimado elegante (`#881337`, `#BE123C`).
   - **Botões de CTA:** Verde esmeralda de alta conversão (`#10B981` / `#059669`) com animação de pulsar suave.

3. **Tabela de Preços com Efeito Decoy:**
   - **Plano Básico (R$ 34,90):** Design minimalista, bordas neutras, sem destaque visual excessivo. Apenas o essencial (Protocolo + Desinflamação + Diástase). Botão secundário sóbrio.
   - **Plano Completo (R$ 47,90) [DESTAQUE MÁXIMO]:** Card elevado (`shadow-card-pop`), borda destacada em vinho/dourado, badge *"ESCOLHA MAIS POPULAR / MELHOR CUSTO-BENEFÍCIO"*, incluindo Todos os Módulos + Glúteos + Bônus 1 + Bônus 2 + Acesso Vitalício + Atualizações. Botão verde vibrante *"QUERO O PLANO COMPLETO"*.

4. **Seção de Garantia Blindada (Redesign de Confiança):**
   - Card moderno com cantos arredondados (`rounded-3xl`), sombra suave e acabamento premium.
   - Selo dourado de 7 dias com anel protetor.
   - Título: *"Risco Zero: Garantia Incondicional de 7 Dias"*.
   - Micro-ícones de segurança: *Compra 100% Segura*, *Reembolso Imediato*, *Privacidade Garantida*.

5. **Seção Pré-Rodapé (CTA Final) e FAQ:**
   - Seção final reformulada com fundo vinho nobre de alto contraste e tipografia branca/marfim perfeitamente legível.
   - FAQ organizado em acordeão moderno com animação suave de abertura.

6. **Otimização Mobile-First:**
   - Container centralizado (`max-w-4xl mx-auto px-4 sm:px-6`).
   - Todos os botões ocupam largura total (`w-full`) em telas móveis para facilitar o toque com o polegar.
   - Escala tipográfica adaptada para evitar quebras de linhas desproporcionais na Hero.
