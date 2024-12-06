use.Atividade;  
  
  
db.produtos.insertMany([  
  {  
    "_id": ObjectId("67521e72ce1d5e8b1851a908"),  
    "nome": "SmartPhone S31",  
    "estoque": 20,  
    "preco": 1200.00,  
    "categoria": "Eletronicos",  
    "loja": ObjectId("675202089b0a4ef3273de3c8")  
  },  
  {  
    "_id": ObjectId("67521effce1d5e8b1851a909"),  
    "nome": "Limpa tudo",  
    "estoque": 100,  
    "preco": 5.99,  
    "categoria": "Limpeza",  
    "loja": ObjectId("675205519b0a4ef3273de3ca")  
  },  
  {  
    "_id": ObjectId("67521f03ce1d5e8b1851a90a"),  
    "nome": "Brigadeiro de panela",  
    "estoque": 500,  
    "preco": 1.99,  
    "categoria": "Doces",  
    "loja": ObjectId("6752055b9b0a4ef3273de3cb")  
  },  
  {  
    "_id": ObjectId("67521f07ce1d5e8b1851a90b"),  
    "nome": "Mouse LT220",  
    "estoque": 50,  
    "preco": 69.99,  
    "categoria": "Eletronicos",  
    "loja": ObjectId("675205cc9b0a4ef3273de3cc")  
  },  
  {  
    "_id": ObjectId("67521f0dce1d5e8b1851a90c"),  
    "nome": "Esponja",  
    "estoque": 800,  
    "preco": 1.99,  
    "categoria": "Limpeza",  
    "loja": ObjectId("675205d19b0a4ef3273de3cd")  
  },  
  {  
    "_id": ObjectId("67521f14ce1d5e8b1851a90d"),  
    "nome": "Brigadeiro de Pistache",  
    "estoque": 300,  
    "preco": 4.99,  
    "categoria": "Doces",  
    "loja": ObjectId("675207429b0a4ef3273de3ce")  
  },  
  {  
    "_id": ObjectId("675221f3ce1d5e8b1851a916"),  
    "nome": "Sofa",  
    "estoque": 15,  
    "preco": 2200.00,  
    "categoria": "Movéis",  
    "loja": ObjectId("675207489b0a4ef3273de3cf")  
  },  
  {  
    "_id": ObjectId("6752225bce1d5e8b1851a917"),  
    "nome": "Camiseta de Time Retro",  
    "estoque": 50,  
    "preco": 199.99,  
    "categoria": "Camisetas",  
    "loja": ObjectId("6752074e9b0a4ef3273de3d0")  
  },  
  {  
    "_id": ObjectId("675222dcce1d5e8b1851a918"),  
    "nome": "Sh.Figuarts Goku Black",  
    "estoque": 35,  
    "preco": 399.99,  
    "categoria": "Figura de Ação",  
    "loja": ObjectId("675207539b0a4ef3273de3d1")  
  },  
  {  
    "_id": ObjectId("67522343ce1d5e8b1851a919"),  
    "nome": "Camisinha",  
    "estoque": 30,  
    "preco": 4.99,  
    "categoria": "Protetor",  
    "loja": ObjectId("675207589b0a4ef3273de3d2")  
  }  
]);  
  
db.lojas.insertMany([  
  {  
    "_id": ObjectId("675202089b0a4ef3273de3c8"),  
    "nome": "Eletronicos Forever",  
    "endereco": "Rua A, 456, São Paulo, SP",  
    "categoria": "Eletronicos",  
    "clientes": [],  
    "data_criacao": ISODate("2023-07-08T12:00:00Z")  
  },  
  {  
    "_id": ObjectId("675205519b0a4ef3273de3ca"),  
    "nome": "Mr.Musculo",  
    "endereco": "Av.Rotaria, 431, São Paulo, SP",  
    "categoria": "Limpeza",  
    "clientes": [],  
    "data_criacao": ISODate("2023-01-09T12:00:00Z")  
  },  
  {  
    "_id": ObjectId("6752055b9b0a4ef3273de3cb"),  
    "nome": "Mais Doce que Pão Doce",  
    "endereco": "Rua Rio, 221, Rio de Janeiro, RJ",  
    "categoria": "Doces",  
    "clientes": [],  
    "data_criacao": ISODate("2023-10-12T13:03:00Z")  
  },  
  {  
    "_id": ObjectId("675205cc9b0a4ef3273de3cc"),  
    "nome": "Tec Gamer",  
    "endereco": "Rua A, 401, São Paulo, SP",  
    "categoria": "Eletronicos",  
    "clientes": [],  
    "data_criacao": ISODate("2023-04-08T10:00:00Z")  
  },  
  {  
    "_id": ObjectId("675205d19b0a4ef3273de3cd"),  
    "nome": "Loja de 1,99",  
    "endereco": "Rua Boa Noite, 231, Ribeirão Preto, SP",  
    "categoria": "Geral",  
    "clientes": [],  
    "data_criacao": ISODate("2023-05-10T08:00:00Z")  
  },  
  {  
    "_id": ObjectId("675207429b0a4ef3273de3ce"),  
    "nome": "Doceria Bom Fim",  
    "endereco": "Rua Longitude, 631, Rio de Janeiro, RJ",  
    "categoria": "Doces",  
    "clientes": [],  
    "data_criacao": ISODate("2023-01-08T08:00:00Z")  
  },  
  {  
    "_id": ObjectId("675207489b0a4ef3273de3cf"),  
    "nome": "Moveis Para sua Casa",  
    "endereco": "Rua Bom Dia, 131, São Paulo, SP",  
    "categoria": "Mobilha",  
    "clientes": [],  
    "data_criacao": ISODate("2023-06-08T08:00:00Z")  
  },  
  {  
    "_id": ObjectId("6752074e9b0a4ef3273de3d0"),  
    "nome": "Roupas Usadas",  
    "endereco": "Rua Sacola, 701, São Paulo, SP",  
    "categoria": "Moda",  
    "clientes": [],  
    "data_criacao": ISODate("2023-05-08T07:00:00Z")  
  },  
  {  
    "_id": ObjectId("675207539b0a4ef3273de3d1"),  
    "nome": "Model Toys",  
    "endereco": "Rua Aladin, 320, São Paulo, SP",  
    "categoria": "Brinquedos",  
    "clientes": [],  
    "data_criacao": ISODate("2023-05-08T08:00:00Z")  
  },  
  {  
    "_id": ObjectId("675207589b0a4ef3273de3d2"),  
    "nome": "Alegria 24h",  
    "endereco": "Rua Lagotin, 696, Rolandia, PR",  
    "categoria": "SexShop",  
    "clientes": [],  
    "data_criacao": ISODate("2023-05-08T08:00:00Z")  
  }  
]);  
  
  
db.clientes.insertMany([  
  {  
    "_id": ObjectId("675300a2ce1d5e8b1851a921"),  
    "nome": "Carlos Silva",  
    "email": "carlos.silva@email.com",  
    "telefone": "(11) 98765-4321",  
    "data_nascimento": ISODate("1990-04-15T00:00:00Z"),  
    "endereco": "Rua Fictícia, 125, São Paulo, SP",  
    "compras": [ObjectId("675400a2ce1d5e8b1851a931")]  
  },  
  {  
    "_id": ObjectId("675300b3ce1d5e8b1851a922"),  
    "nome": "Ana Souza",  
    "email": "ana.souza@email.com",  
    "telefone": "(21) 91234-5678",  
    "data_nascimento": ISODate("1985-07-25T00:00:00Z"),  
    "endereco": "Av. Mundo, 322, Rio de Janeiro, RJ",  
    "compras": [ObjectId("675400a2ce1d5e8b1851a933")]  
  },  
  {  
    "_id": ObjectId("675300c4ce1d5e8b1851a923"),  
    "nome": "João Oliveira",  
    "email": "joao.oliveira@email.com",  
    "telefone": "(31) 99987-6543",  
    "data_nascimento": ISODate("1993-02-10T00:00:00Z"),  
    "endereco": "Rua B, 789, Belo Horizonte, MG",  
    "compras": []  
  },  
  {  
    "_id": ObjectId("675300d5ce1d5e8b1851a924"),  
    "nome": "Mariana Alves",  
    "email": "mariana.alves@email.com",  
    "telefone": "(61) 98672-5432",  
    "data_nascimento": ISODate("1982-12-11T00:00:00Z"),  
    "endereco": "Quadra 5, Lote 12, Brasília, DF",  
    "compras": [ObjectId("675400a2ce1d5e8b1851a932")]  
  },  
  {  
    "_id": ObjectId("675300e6ce1d5e8b1851a925"),  
    "nome": "Lucas Pereira",  
    "email": "lucas.pereira@email.com",  
    "telefone": "(41) 99876-4321",  
    "data_nascimento": ISODate("1995-03-18T00:00:00Z"),  
    "endereco": "Rua da Paz, 456, Curitiba, PR",  
    "compras": [ObjectId("675400a2ce1d5e8b1851a933")]  
  },  
  {  
    "_id": ObjectId("675300f7ce1d5e8b1851a926"),  
    "nome": "Fernanda Costa",  
    "email": "fernanda.costa@email.com",  
    "telefone": "(48) 91234-8765",  
    "data_nascimento": ISODate("1992-06-20T00:00:00Z"),  
    "endereco": "Rua 10, 987, Florianópolis, SC",  
    "compras": []  
  },  
  {  
    "_id": ObjectId("67530108ce1d5e8b1851a927"),  
    "nome": "Gustavo Lima",  
    "email": "gustavo.lima@email.com",  
    "telefone": "(71) 92222-2222",  
    "data_nascimento": ISODate("1988-08-14T00:00:00Z"),  
    "endereco": "Av. Liberdade, 3000, Salvador, BA",  
    "compras": [ObjectId("675400a2ce1d5e8b1851a932")]  
  },  
  {  
    "_id": ObjectId("67530119ce1d5e8b1851a928"),  
    "nome": "Patrícia Rocha",  
    "email": "patricia.rocha@email.com",  
    "telefone": "(62) 99765-4321",  
    "data_nascimento": ISODate("1991-01-02T00:00:00Z"),  
    "endereco": "Rua Goiás, 850, Goiânia, GO",  
    "compras": [ObjectId("675400a2ce1d5e8b1851a931")]  
  },  
  {  
    "_id": ObjectId("6753012ace1d5e8b1851a929"),  
    "nome": "Ricardo Santos",  
    "email": "ricardo.santos@email.com",  
    "telefone": "(21) 93877-6543",  
    "data_nascimento": ISODate("1987-04-11T00:00:00Z"),  
    "endereco": "Rua Amazonas, 145, Rio de Janeiro, RJ",  
    "compras": [ObjectId("675400a2ce1d5e8b1851a932")]  
  },  
  {  
    "_id": ObjectId("6753013bce1d5e8b1851a930"),  
    "nome": "Bruna Oliveira",  
    "email": "bruna.oliveira@email.com",  
    "telefone": "(61) 93333-3333",  
    "data_nascimento": ISODate("1989-11-30T00:00:00Z"),  
    "endereco": "Q.6 Bloco 5, Brasília, DF",  
    "compras": [ObjectId("675400a2ce1d5e8b1851a933")]  
  }  
]);  
  
db.compras.insertMany([  
  {  
    "_id": ObjectId("675400a2ce1d5e8b1851a931"),  
    "cliente_id": ObjectId("675300a2ce1d5e8b1851a921"),  
    "data_compra": ISODate("2023-09-15T15:30:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67521e72ce1d5e8b1851a908"),  
        "quantidade": 1,  
        "preco_unitario": 1200.00  
      },  
      {  
        "produto_id": ObjectId("67521f03ce1d5e8b1851a90a"),  
        "quantidade": 3,  
        "preco_unitario": 1.99  
      }  
    ],  
    "total": 1207.97  
  },  
  {  
    "_id": ObjectId("675400a2ce1d5e8b1851a932"),  
    "cliente_id": ObjectId("675300a2ce1d5e8b1851a921"),  
    "data_compra": ISODate("2023-09-18T10:00:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67521f14ce1d5e8b1851a90d"),  
        "quantidade": 2,  
        "preco_unitario": 4.99  
      }  
    ],  
    "total": 9.98  
  },  
  {  
    "_id": ObjectId("675400a2ce1d5e8b1851a933"),  
    "cliente_id": ObjectId("675300b3ce1d5e8b1851a922"),  
    "data_compra": ISODate("2023-10-02T17:20:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67522343ce1d5e8b1851a919"),  
        "quantidade": 10,  
        "preco_unitario": 4.99  
      }  
    ],  
    "total": 49.90  
  },  
  {  
    "_id": ObjectId("675400b3ce1d5e8b1851a934"),  
    "cliente_id": ObjectId("675300c4ce1d5e8b1851a923"),  
    "data_compra": ISODate("2023-08-12T14:00:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67521f14ce1d5e8b1851a90d"),  
        "quantidade": 1,  
        "preco_unitario": 10.00  
      }  
    ],  
    "total": 10.00  
  },  
  {  
    "_id": ObjectId("675400b3ce1d5e8b1851a935"),  
    "cliente_id": ObjectId("675300d5ce1d5e8b1851a924"),  
    "data_compra": ISODate("2023-07-05T08:15:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67521f14ce1d5e8b1851a90d"),  
        "quantidade": 5,  
        "preco_unitario": 1.99  
      }  
    ],  
    "total": 9.95  
  },  
  {  
    "_id": ObjectId("675400c4ce1d5e8b1851a936"),  
    "cliente_id": ObjectId("675300e6ce1d5e8b1851a925"),  
    "data_compra": ISODate("2023-08-18T13:45:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67521e72ce1d5e8b1851a908"),  
        "quantidade": 2,  
        "preco_unitario": 599.99  
      }  
    ],  
    "total": 1199.98  
  },  
  {  
    "_id": ObjectId("675400d5ce1d5e8b1851a937"),  
    "cliente_id": ObjectId("675300f7ce1d5e8b1851a926"),  
    "data_compra": ISODate("2023-10-10T16:00:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67521e72ce1d5e8b1851a908"),  
        "quantidade": 1,  
        "preco_unitario": 599.99  
      }  
    ],  
    "total": 599.99  
  },  
  {  
    "_id": ObjectId("675400e6ce1d5e8b1851a938"),  
    "cliente_id": ObjectId("67530108ce1d5e8b1851a927"),  
    "data_compra": ISODate("2023-08-28T10:30:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67521f14ce1d5e8b1851a90d"),  
        "quantidade": 5,  
        "preco_unitario": 7.99  
      }  
    ],  
    "total": 39.95  
  },  
  {  
    "_id": ObjectId("675400f7ce1d5e8b1851a939"),  
    "cliente_id": ObjectId("67530119ce1d5e8b1851a928"),  
    "data_compra": ISODate("2023-09-20T19:00:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67521f03ce1d5e8b1851a90a"),  
        "quantidade": 3,  
        "preco_unitario": 1.99  
      }  
    ],  
    "total": 5.97  
  },  
  {  
    "_id": ObjectId("675400g8ce1d5e8b1851a940"),  
    "cliente_id": ObjectId("6753012ace1d5e8b1851a929"),  
    "data_compra": ISODate("2023-09-22T14:00:00Z"),  
    "produtos": [  
      {  
        "produto_id": ObjectId("67521f03ce1d5e8b1851a90a"),  
        "quantidade": 5,  
        "preco_unitario": 7.99  
      }  
    ],  
    "total": 39.95  
  }  
]);