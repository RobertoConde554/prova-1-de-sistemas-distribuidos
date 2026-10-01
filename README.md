# prova-1-de-sistemas-distribuidos

## README

 # Servidor RPC com Python

 Projeto simples usando **XML-RPC** para consultar o saldo de unidades disponíveis.

  Como executar

 ### 1\. Inicie o servidor

```
python servidor.py
```

 O servidor ficará aguardando solicitações na porta **8002**.

 ### 2\. Execute o cliente

 Em outro terminal:

```
python cliente.py
```

 

 O cliente envia:

```
15 unidades iniciais
4 unidades vendidas
```

 Resultado:

```
Unidades restantes: 11
```

 Tecnologias

 - Python
- XML-RPC
- `SimpleXMLRPCServer`
- `ServerProxy`
