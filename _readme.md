<p align="center">
  <img src="./assets/Megaman (1).png" alt="Logo Megaman API" width="300"/>
</p>


<h1 align="center">🎮 Megaman Bosses API 🎮</h1>

## 📌 Contexto
Este projeto é uma API desenvolvida em .NET Core 3.1 para listar os chefes (bosses) do jogo Megaman. O objetivo principal é fornecer um backend que retorna informações no formato JSON sobre os bosses do jogo.

### 🔹 Exemplo de resposta JSON:
```json
{
  "Id": 1,
  "Code": "DLN/DRN-003",
  "Name": "Cutman",
  "HP": 150,
  "Picture": "https://vignette.wikia.nocookie.net/megaman/images/2/22/Cutman.png"
}
```

## 🛠 Especificações do Projeto
Este projeto utiliza .NET Core 3.1 e Entity Framework Core para gerenciar os dados. Abaixo está a configuração do arquivo de projeto `.csproj`:

```xml
<Project Sdk="Microsoft.NET.Sdk.Web">

  <PropertyGroup>
    <TargetFramework>netcoreapp3.1</TargetFramework>
  </PropertyGroup>

  <ItemGroup>
    <PackageReference Include="Microsoft.EntityFrameworkCore" Version="3.1.8" />
    <PackageReference Include="Microsoft.EntityFrameworkCore.Design" Version="3.1.8">
      <IncludeAssets>runtime; build; native; contentfiles; analyzers; buildtransitive</IncludeAssets>
      <PrivateAssets>all</PrivateAssets>
    </PackageReference>
    <PackageReference Include="Microsoft.EntityFrameworkCore.SqlServer" Version="3.1.8" />
    <PackageReference Include="Newtonsoft.Json" Version="12.0.2" />
  </ItemGroup>

</Project>
```

## 🔗 Endpoints da API
Esta API possui os seguintes endpoints:

| Método | Rota | Descrição |
|--------|------|-----------|
| `GET`  | `/api/v1/robots` | Retorna todos os bosses cadastrados no sistema |
| `GET`  | `/api/v1/robots/{id}` | Retorna os detalhes de um boss específico |
| `POST` | `/api/v1/robots` | Adiciona um novo boss ao sistema |

## 📦 Dependências do Projeto
Este projeto utiliza as seguintes bibliotecas:

| Dependência | Versão | Descrição |
|------------|--------|-----------|
| [.NET Core](https://dotnet.microsoft.com/en-us/download/dotnet/3.1) | 3.1 | Framework principal para desenvolvimento da API |
| [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/) | 3.1.8 | ORM para gerenciar o banco de dados |
| [Entity Framework Core Design](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/) | 3.1.8 | Ferramentas para geração de migrações e estrutura do banco |
| [Entity Framework Core SQL Server](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/) | 3.1.8 | Provedor do Entity Framework Core para SQL Server |
| [Newtonsoft.Json](https://www.newtonsoft.com/json) | 12.0.2 | Biblioteca para manipulação de JSON |

## 📂 Estrutura do Projeto
A estrutura de diretórios do projeto segue o padrão MVC e está organizada da seguinte forma:

```
.vs                                 # Configurações do Visual Studio
.vscode                             # Configurações do VS Code
bin                                 # Arquivos binários gerados pelo build
Controllers                         # Contém os controladores da API
Database                            # Scripts e configurações do banco de dados
middlewares                         # Middlewares personalizados
Models                              # Modelos de dados usados no projeto
obj                                 # Arquivos temporários gerados pelo compilador
Properties                          # Configurações do projeto
Services                            # Implementação de regras de negócio
appsettings.Development.json        # Configuração para ambiente de desenvolvimento
appsettings.json                    # Configuração principal do projeto
global.json                         # Arquivo de configuração global do .NET
MegamanApi.csproj                   # Arquivo de configuração do projeto .NET
MegamanApi.sln                      # Arquivo de solução do projeto
Program.cs                          # Ponto de entrada da aplicação
Startup.cs                          # Configuração dos serviços e middleware
```

## 🚀 Como Executar o Projeto
### 🔹 Pré-requisitos
Antes de iniciar, certifique-se de ter instalado:
- [SDK do .NET Core 3.1](https://dotnet.microsoft.com/en-us/download/dotnet/3.1)
- [SQL Server](https://www.microsoft.com/pt-br/sql-server/sql-server-downloads) (ou outro banco compatível com EF Core)

---
🚀 **Pronto! Agora você pode consumir a API e listar os bosses de Megaman!**
---------------
# Documentação com IA

- [] Criar read-me mais profissional
- [] Utilizar um projeto pronto sem documentação
- [] Ver possibilidades de ferramentas para documentas um projeto

--
pré-requisitos
- [] Ter um projeto (opcional)
- [] Git/Github
- [] Ferramenta de IA através de chat


Karen Nascimento - https://github.com/KarenNascy 🎮🔥
