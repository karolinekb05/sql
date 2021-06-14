-- 1-	Inserir 10 primeiros clientes na tabela ator.
INSERT INTO ator (primeiro_nome, ultimo_nome)
            SELECT primeiro_nome, ultimo_nome FROM cliente 
            WHERE cliente_id<=10


-- 2-	Inserir com apenas um insert os atores Tom Cavalcante, Edson Motorola, Djair do Caminhão.
INSERT INTO ator (primeiro_nome, ultimo_nome)
            VALUES ('Tom', 'Cavalcante'),
                   ('Edson', 'Motorola'),
                   ('Djair', 'do Caminhão')
		
-- 3-	Faça um comando INSERT que insira no banco o atriz Maria Odete.
INSERT INTO ator (primeiro_nome, ultimo_nome)
            VALUES (‘Maria’, ‘Odete’)

-- 4-	Faça um comando que insira como ator todos os clientes que tenham o primeiro nome WILLIE
INSERT INTO ator (primeiro_nome, ultimo_nome)
        SELECT FROM clientes primeiro_nome, ultimo_nome
        WHERE primeiro_nome = ‘Willie’

-- 5-	Faça um comando que mude o primeiro nome dos atores de UMA para DUAS
UPDATE ator
       SET primeiro_nome = ‘Duas’
    WHERE primeiro_nome = ‘Uma’

-- 6-	Faça uma limpeza na tabela ator, limpando todos os registros que foram inseridos posteriormente ao registro 200
DELETE FROM ator
       WHERE ator_id <=200
