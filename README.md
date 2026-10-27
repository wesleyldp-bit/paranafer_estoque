# 📖 Manual de Utilização — Painel de Estoque PARANAFER (Vendas)

Este manual orienta a equipa de vendas na utilização do **Painel de Posicionamento de Estoque**, garantindo consultas rápidas e seguras para negociações com clientes.

---

## 1. Cabeçalho e Auditoria de Dados

No topo do painel, você encontra o selo de segurança e os botões de ação:

* 🟢 **Atualizado no Sheets em (Data e Hora):** Indica o momento exato em que a planilha oficial de estoque foi modificada pela última vez na fábrica. Sempre confira este horário para garantir que os dados estão frescos.
* 🔄 **Sincronizar Google Sheets:** Clique neste botão verde para forçar a atualização imediata dos dados na tela sem precisar recarregar o navegador.
* 📥 **Exportar CSV:** Baixa uma cópia dos dados filtrados para formato de tabela (Excel).

---

## 2. Resumo Executivo (Cartões de KPI)

* **TOTAL DE ITENS:** Número total de produtos monitorados.
* **CRÍTICOS / RUPTURA (Vermelho):** Itens com cobertura abaixo de 30% ou com saldo negativo (indica que os agendamentos superam o físico). **Atenção redobrada ao vender.**
* **EM ATENÇÃO (Amarelo):** Produtos com cobertura entre 30% e 70%.
* **ITENS OK (Verde):** Produtos com cobertura igual ou superior a 70%. Pronta entrega garantida.
* **CARGAS AGENDADAS:** Volume total de peças já comprometidas para entrega.
* **FALTA P/ EST. MÁX.:** Quantidade em toneladas necessária para repor o estoque até o teto máximo.

---

## 3. Como Usar os Filtros

* **Buscar produto:** Digite o código do produto (ex: `EQ45`, `Q92`, `H8SLE`) para isolá-lo instantaneamente.
* **Todas as Famílias:** Permite separar entre *Telas*, *Treliças* ou *Outros / Rolo / Barra*.
* **Todos os Status:** Filtre apenas os itens *Críticos*, em *Atenção* ou *OK*.

---

## 4. O que significam os Gráficos?

1. **Saldo Disponível vs. Estoque Máximo (Peças):**
   * *Barra Azul:* Volume de peças prontas e livres no pátio.
   * *Barra Cinza Escuro:* Capacidade máxima de armazenamento daquele item.
2. **Nível de Cobertura de Estoque (%):**
   * Mostra o percentual de atendimento do estoque em barras coloridas.
   * *Barras para a esquerda (Vermelhas):* Sinalizam ruptura de estoque (comprometimento superior ao físico).

---

## 5. Tabela Detalhada e Significado das Cores

A tabela é a ferramenta principal para o fechamento de vendas:

* **Saldo Disponível (Cores de Fundo):**
  * 🟩 **Fundo Verde:** Saldo positivo e confortável. Produto disponível para venda imediata.
  * 🟥 **Fundo Vermelho com aviso `RUPTURA`:** Saldo negativo ou zerado. Os compromissos agendados ultrapassam o estoque físico. Consulte a produção antes de fechar o prazo com o cliente!
* **Status:** Mostra o semáforo do produto (`OK`, `Atenção` ou `Crítico`).
* **Observação:** Avisos importantes vindos da fábrica (ex: *Em produção*).
