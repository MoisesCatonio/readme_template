# Integração Clockify
Integração do banco de horas, relacionadas aos projetos desenvolvidos pelos funcionários da beAnalytic.

### Sumário 🔢
<!-- Lista com o conteúdo -->
<details>
  <summary>Seções</summary>
  <ul>
    <li>
      <a href="#método-de-integração-">Método de integração</a>
    </li>
    <li>
      <a href="#dependências-">Dependências</a>
    </li>
    <li>
      <a href="#execução-">Execução</a>
    </li>
    <li>
      <a href="#observações-">Observações</a>
    </li>
    <li>
      <a href="#documentação-relacionada-">Documentação relacionada</a>
    </li>
    <li>
      <a href="#responsável-">Responsável</a>
    </li>
  </ul>
</details>

## Método de integração 🎲
O clockify possui uma API (<a href="#documentação-relacionada-">Documentação relacionada</a>), na qual mediante o uso de uma API KEY, conseguimos acessar as diversas camadas de divisão de horários e tarefas.

<p align="left">(<a href="#sumário-">Voltar ao sumário</a>)</p>

## Dependências 🧩
- Python 3.x
- Requests (lib)
- beanalytic (lib interna).

<p align="left">(<a href="#sumário-">Voltar ao sumário</a>)</p>

## Execução ▶
Com os scripts em uma pasta única, e com o terminal acessando a mesma, executamos eles da seguinte forma:
```
py -3.x <nome_do_script>
```

<p align="left">(<a href="#sumário-">Voltar ao sumário</a>)</p>

## Observações ‼
Os scripts já se utilizam das funções mais novas criadas para tipagem automática e upload no banco, então deve-se seguir o padrão utilizado na função **insert_database_postgres** presente na biblioteca **beanalytic**.

<p align="left">(<a href="#sumário-">Voltar ao sumário</a>)</p>

## Documentação relacionada 📖
Link para documentação da API do clockify: https://clockify.me/developers-api

<p align="left">(<a href="#sumário-">Voltar ao sumário</a>)</p>



## Responsável 👔

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/MoisesCatonio">
        <img src="https://avatars3.githubusercontent.com/u/9872016" width="100px;" alt="Foto do Moisés Catônio no GitHub"/><br>
        <sub>
          <b>Moisés Catônio</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

<p align="left">(<a href="#sumário-">Voltar ao sumário</a>)</p>
