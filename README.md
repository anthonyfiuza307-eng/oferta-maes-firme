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
  basico: "https://pay.kiwify.com.br/SEU_LINK_34",    // Plano Básico (R$ 34,90)
  upgrade: "https://pay.kiwify.com.br/SEU_LINK_42",   // Oferta de Upgrade Downsell (R$ 42,90)
  premium: "https://pay.kiwify.com.br/SEU_LINK_47"    // Plano Completo (R$ 47,90)
};
```

Basta substituir as URLs com as suas chaves/links de checkout e salvar o arquivo.

---

## 💎 Recursos de UI/UX, CRO e Interatividade Implementados

1. **Barra de Escassez e Timer (Topo):**
   - Texto refinado: *"⏱️ Último dia para garantir o acesso exclusivo com desconto de lançamento"*.
   - **Contador Sincronizado com Brasília:** Blocos discretos em tom marfim/branco semi-transparente com números em vinho escuro (`[HH] : [MM] : [SS]`).
2. **Estrutura Limpa (Sem Rótulos Didáticos):**
   - Removidas todas as tags e demarcações internas (como "Público-Alvo", "Dores", "Módulo", "Planos"). Títulos e conteúdos fluem com naturalidade e autoridade.
3. **Efeito de Relevo (Hover Lift):**
   - Cards, botões e caixas de oferta possuem elevação suave (`hover:-translate-y-1 hover:shadow-lg`).
   - Botão do Plano Completo estático e sólido em verde esmeralda premium (sem piscar).
4. **Redesign Aberto da Garantia de 7 Dias:**
   - Integração fluida ao fundo da página (sem bordas duras de container), com selo dourado limpo e ícones sutis de segurança.
5. **Modal de Upgrade Downsell (Ao Clicar no Plano Básico):**
   - Ao clicar no Plano Básico, abre uma janela especial oferecendo o upgrade para o Plano Completo por apenas R$ 42,90 (mais R$ 8,00), com opção clara de aceitar ou manter o básico.
6. **Modal de Inatividade (150 segundos):**
   - Monitor de inatividade que dispara um popup elegante de retenção caso a usuária fique 2,5 minutos sem interação (com limite de exibição de 1x por sessão).
7. **Microcopy de Segurança e Credibilidade:**
   - Textos de segurança (Criptografia 256 bits, Acesso Imediato, LGPD) reforçados abaixo dos botões e no rodapé.
