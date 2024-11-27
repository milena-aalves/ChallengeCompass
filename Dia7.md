Dia 7
No sétimo dia da Sprint, o tema abordado foi SQL. Estudei o conteúdo, realizei os exercícios propostos e aprendi a executar consultas em tabelas, assim podendo obter e manipular informações de maneira eficiente.

LISTAGEM DE COMANDOS

-- Comandos utilizados para consultar na tabela de 'usuarios' 
SELECT COUNT (*) as total_usuarios FROM Usuarios;
SELECT * FROM usuarios WHERE id=10;
SELECT * from usuarios WHERE nome = 'Bruce Wayne';
SELECT * from usuarios WHERE email = 'ghost_silva@fantasma.com';
DELETE FROM usuarios WHERE email = 'peterparker@marvel.com';


-- Comandos utilizados para consultar na tabela de 'produtos' 
SELECT * FROM produtos where descricao = '';
SELECT * FROM produtos WHERE categoria = 'games';
SELECT * FROM produtos WHERE preco = 0;
SELECT * FROM produtos WHERE preco > 100.00;
SELECT * from produtos where preco BETWEEN 1000.00 AND 2000.00;
SELECT * FROM produtos WHERE nome LIKE '%jogo%';
