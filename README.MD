<h1 align="center">
  <br />
  <img
    src="./_docs/assets/futuristicMegaMan.png"
    alt="Meu Projeto API .NET Core"
    width="150"
  />
  <br />
  <b>Meu Projeto API .NET Core</b>
  <br />
  <sub
    ><sup><b>(MINHA-API-DOTNETCORE)</b></sup></sub
  >
  <br />
  <a
    href="https://github.com/seuUsuario/suaRepo/actions/workflows/build.yml"
  >
    <img
      src="https://github.com/seuUsuario/suaRepo/actions/workflows/build.yml/badge.svg"
      alt=""
    />
  </a>
  <a href="https://github.com/seuUsuario/suaRepo/releases/latest">
    <img
      src="https://img.shields.io/github/v/release/seuUsuario/suaRepo"
      alt="Latest Release"
    />
  </a>
</h1>

<p align="center">
  Este projeto de API .NET Core é projetado para servir dados formatados em JSON. É um serviço backend construído com .NET Core 3.1 e várias dependências modernas para gerenciamento de dados e manipulação de respostas da API.
  <br />
</p>

<p align="center">
  Desenvolvido com Entity Framework Core e outras tecnologias modernas .NET, este projeto visa fornecer uma API robusta para acessar dados de sua aplicação.
  <br />
</p>


## Endpoints da API

| Método | Endpoint                  | Descrição                                                 |
|--------|---------------------------|-----------------------------------------------------------|
| GET    | /api/v1/robots            | Retorna todos os robôs.                                   |
| GET    | /api/v1/robots/{id}       | Retorna um robô específico pelo ID.                       |
| POST   | /api/v1/robots            | Adiciona um novo robô (a ser implementado).               |

### Detalhes dos Endpoints

- **GET /api/v1/robots**
  - Retorna uma lista de todos os robôs disponíveis.

- **GET /api/v1/robots/{id}**
  - Parâmetros:
    - `id` (int): Identificador do robô.
  - Retorna um robô específico com base no ID fornecido. Caso o robô não seja encontrado, retorna uma mensagem "Nenhum robô encontrado".

- **POST /api/v1/robots**
  - Endpoint reservado para adicionar um novo robô (atualmente retorna um OK sem funcionalidade implementada).



## Techniques Used

<p align="center">
  - <b>Entity Framework Core:</b> ORM for data management.<br />
  - <b>RESTful API Design:</b> Ensures clear and effective communication
  endpoints.<br />
  - <b>Dependency Injection:</b> Used throughout to promote loose coupling and
  enhanced testability.<br />
</p>

## Dependencies

<table align="center">
  <tr>
    <th>Package</th>
    <th>Version</th>
    <th>Link</th>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore</td>
    <td>3.1.8</td>
    <td>
      <a
        href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.1.8"
        >NuGet</a
      >
    </td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.Design</td>
    <td>3.1.8</td>
    <td>
      <a
        href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/3.1.8"
        >NuGet</a
      >
    </td>
  </tr>
  <tr>
    <td>Microsoft.EntityFrameworkCore.SqlServer</td>
    <td>3.1.8</td>
    <td>
      <a
        href="https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/3.1.8"
        >NuGet</a
      >
    </td>
  </tr>
  <tr>
    <td>Newtonsoft.Json</td>
    <td>12.0.2</td>
    <td>
      <a href="https://www.nuget.org/packages/Newtonsoft.Json/12.0.2">NuGet</a>
    </td>
  </tr>
</table>

## :gear: Arch

```🌐
src
├── 📂 Controllers      [Routes for endpoints]
├── 📂 Models           [Database models]
├── 📂 Services         [Business rules]
├── 📂 Middlewares      [Intermediate functions between the HTTP request and the final server response]
├── 📂 Database         [Structures related to the database]
│   ├── 📂 DTOs             [Input Models and View Models (Data Transfer Objects)]
│   ├── 📂 EntityFramework  [Files related to the ORM Entity Framework]
│   │     ├── 📂 Context         [Entity context settings]
│   │     ├── 📂 Migrations      [Migrations for database updates]
│   ├── 📂 Repositories     [Repository pattern]
```

## License This software is licensed under the terms of the [MIT]

⌨️ HudsonCruz -
[Github](https://github.com/hcamposcruz/document_megaApi.git)
