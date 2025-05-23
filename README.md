## Correção de vunerabilidade:


**1- Validação de Entrada**

* Adição de required, type, pattern nos campos do formulário.
(Evita envio de dados inválidos ou maliciosos)

**2- Prevenção de XSS**

* Escapou os dados com escapeHTML() antes de exibir no HTML.
(Impede execução de scripts injetados pelo usuário)

**3- Proteção contra Reverse Tabnabbing**

* Usou noopener,noreferrer ao abrir nova aba.
(Impede que a nova aba controle ou redirecione a aba original)
