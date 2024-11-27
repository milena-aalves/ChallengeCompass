Dia 8
No oitavo dia o conteúdo apresentado foi o NOSQL após consumir os materiais realizei as atividades e aprendi a consultar e obter informações das tabelas.

LISTAGEM DE COMANDOS

-- Comandos utilizados para consultar na tabela de 'usuarios' 

db.collection_name.countDocuments()

db.collection_name.updateOne(
  { "nome": "Teste Start" },
  { $set: { "nome": "Teste Finish" } }
)

db.collection_name.find(
  { "nome": "Bruce Wayne" }
)

db.collection_name.find(
  { "email": "ghost_silva@fantasma.com" }
)

db.collection_name.deleteOne(
  { "email": "peterparker@marvel.com" }
)

-- Comandos utilizados para consultar na tabela de 'produtos' 

db.collection_name.find(
  { "descricao": { $eq: "" } }
)

db.collection_name.find(
  { "categoria": "games" }
)

db.collection_name.find(
  { "preco": 0 }
)

db.collection_name.find(
  { "preco": { $gt: 100 } }
)

db.collection_name.find(
  { "preco": { $gte: 1000, $lte: 2000 } }
)

db.collection_name.find(
  { "nome": { $regex: "jogo", $options: "i" } }
)

