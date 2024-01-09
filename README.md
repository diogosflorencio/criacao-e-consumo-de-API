# Criando e Consumindo uma Simples API com Node.js

![GitHub repo size](https://img.shields.io/github/repo-size/diogosflorencio/criacao-e-consumo-de-API?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/diogosflorencio/criacao-e-consumo-de-API?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/diogosflorencio/criacao-e-consumo-de-API?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/diogosflorencio/criacao-e-consumo-de-API?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/diogosflorencio/criacao-e-consumo-de-API?style=for-the-badge)

<img src="https://github.com/diogosflorencio/criacao-e-consumo-de-API/assets/33941005/15242e1a-de71-40f7-85e3-217dcb71b86b" style="width:100%" alt="Exemplo de imagem">

> Projeto desenvolvido para criar e consumir uma API simples usando JavaScript. Atualmente, apenas um valor randômico é gerado no backend e exibido no frontend. O objetivo final é permitir que os usuários adicionem palavras ao banco de dados por meio da API, sendo essas palavras acessíveis para qualquer usuário.
>
> As funcionalidades mencionadas acima foram implementadas em outro repositório. Este projeto aqui está concluído. <br>
> Link: [Novo Repositório](https://github.com/diogosflorencio/criacao-e-consumo-de-API-parte-2)
<br>

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

Link: https://f11ede4b-4075-43c5-a4cb-edef48e2313a-00-su5en0geflq3.riker.replit.dev/

---

### Ajustes e Melhorias

O projeto ainda está em desenvolvimento, e as próximas atualizações serão focadas nas seguintes tarefas:

- [x] Criar API
- [x] Consumir com fetch no front
- [x] Criar front e hospedar tudo
      
---

## Importante: Mudança Significativa no Projeto

O projeto passou por mudanças significativas, resultando em uma nova implementação. Para manter clareza e organização, criei um novo repositório para abrigar a versão atualizada do projeto.

- Novo Repositório: [Novo Projeto](https://github.com/diogosflorencio/criacao-e-consumo-de-API-parte-2)

Ambos os repositórios serão mantidos para referência, mas futuras atualizações e desenvolvimentos ocorrerão no novo repositório.

O proposito disso, é não perder o progresso feito até aqui, já que o outro mudou tanto.

--- 

- [ ] Modificar o back para selecionar palavras de um array
- [ ] Modificar o front para permitir a adição de novas palavras via API
- [ ] Modificar a API para aceitar POST ou PUT
- [ ] Finalizar o projeto

`As tarefas foram concluídas no novo repositório.`

## 💻 Pré-requisitos

Não há pré-requisitos para começar. Basta clicar no [link do projeto](https://f11ede4b-4075-43c5-a4cb-edef48e2313a-00-su5en0geflq3.riker.replit.dev/).

## 🚀 Instalando "Criando e Consumindo uma API com Node.js"

Para instalar o projeto, basta clonar o repositório:

```
git clone https://github.com/diogosflorencio/criacao-e-consumo-de-API.git
```

## ☕ Usando Criando e Consumindo uma API com Node.js

Para utilizar o projeto, siga estas etapas:

```
Basta clicar em "GERAR"
```

## 📫 Contribuindo para "Criando e Consumindo uma API com Node.js"

Para contribuir com o projeto, siga estas etapas:

1. Faça um fork deste repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_do_projeto>/<local>`
5. Crie a solicitação de merge.

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).


Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/diogosflorencio" title="Diogo Florencio">
        <img src="https://avatars.githubusercontent.com/u/33941005" width="100px;" alt="Foto do Diogo Florencio no GitHub"/><br>
        <sub>
          <b>Diogo Florencio</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

<!--## 🤝 Colaboradores

Quer fazer parte desse projeto? Clique [AQUI](CONTRIBUTING.md) e leia como contribuir.-->

## 📝 Licença

Este projeto é livre e não possui uma licença específica.
