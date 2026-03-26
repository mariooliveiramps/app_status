# AppFoodKadu - Sistema de Autoatendimento (Totem)

O **AppFoodKadu** é um aplicativo Android desenvolvido para funcionar como um totem de autoatendimento em empórios e lojas de produtos naturais. O projeto foca em simplicidade para o cliente final e controle total para o administrador.

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as ferramentas mais modernas do ecossistema Android:

- **Linguagem:** Java.
- **Banco de Dados:** [Room SQLite] - Utilizado para persistência local de produtos, estoque e histórico de vendas.
- **Interface (UI):** Material Design Components - Garante uma interface moderna, limpa e responsiva.
- **Relatórios:** [PdfDocument API] - Geração de relatórios detalhados de vendas diretamente em formato PDF.
- **QR Code:** [ZXing (Zebra Crossing)] - Utilizado para a geração dinâmica do QR Code de pagamento (Pix).
- **Notificações:** [Telegram Bot API] - Integração via HTTP para notificações instantâneas de vendas em tempo real.
- **Persistência de Imagens:** [Scoped Storage & URI Persistable Permissions] - Garante que as fotos dos produtos cadastradas pelo administrador permaneçam acessíveis mesmo após reiniciar o dispositivo.

---

## 🚀 Principais Funcionalidades

- **Carrinho de Compras:** Interface intuitiva para seleção de produtos com trava automática de estoque.
- **Painel Administrativo:** Área restrita por senha para gestão de catálogo.
- **Gestão de Estoque:** Controle automático que diminui a quantidade disponível a cada compra finalizada.
- **Relatórios Profissionais:** Exportação de vendas agrupadas por compra e filtradas por data, com alinhamento em grid para facilitar a leitura.
- **Notificação Automática:** Envio silencioso de todos os detalhes da compra para o Telegram do proprietário.
- **Interface Safe Area:** Layout totalmente adaptado para ficar abaixo da barra de notificações e acima da barra de navegação em qualquer aparelho.

---

## 🤖 Desenvolvimento com auxilio de IA (Agents)

---
*Desenvolvido com foco em eficiência.*
