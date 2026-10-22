Atue como um especialista em N8N.

Crie uma automação para registrar automaticamente chamados de suporte técnico recebidos por formulário.

Público:
Analista de suporte técnico (atendimento a clientes domésticos e pequenas empresas).

Ferramentas envolvidas:
Google Forms, Google Sheets, Gmail e Telegram.

Fluxo:
1. Receber uma nova resposta do formulário de abertura de chamado.
2. Validar os dados (e-mail válido e descrição preenchida).
3. Gerar um número de chamado único e registrar os dados na planilha.
4. Enviar um e-mail de confirmação ao cliente com o número do chamado.
5. Enviar uma notificação ao analista com nome, contato, tipo de problema e urgência.

Regras:
- Ignorar registros sem e-mail válido.
- Chamados "Urgentes" devem ser notificados imediatamente e destacados na planilha.
- Evitar duplicidade: não registrar dois chamados idênticos do mesmo e-mail em menos de 10 minutos.
- Em caso de erro em qualquer etapa, enviar um alerta ao analista.

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.