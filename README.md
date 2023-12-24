**Descrição:**

Projeto simples de API em Node.js que gera e exibe valores aleatórios no frontend. Desenvolvido utilizando Replit para hospedar a API e a promise fetch para manipulação no frontend. Em caso de falha, verifique a disponibilidade da API.

**Código da API:**

```javascript
var http = require('http');

http.createServer(function(req, res){
  res.setHeader('Access-Control-Allow-Origin', '*');
  res.writeHead(200, {'Content-Type': 'application/json'});
  
  let numero = {
    valor: Math.round(Math.random() * 100)
  }

  res.end(JSON.stringify(numero));
}).listen(8080);
```

---

Link: https://consumindo-api.diogoflorencio.repl.co