# Geracão Tech Unimed-BH Esquema Conceitual de Banco de Dados - OS

# Objetivo:
Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

# Narrativa:
Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica

    1. Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
    2. Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
    3. A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
    4. O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
    5. A mesma equipe avalia e executa os serviços
    6. Os mecânicos possuem código, nome, endereço e especialidade
    7. Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.