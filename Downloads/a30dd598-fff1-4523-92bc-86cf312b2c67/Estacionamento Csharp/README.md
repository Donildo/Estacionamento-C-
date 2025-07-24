# 📘 README – Sistema Web com ASP.NET Core 8

Este projeto é um sistema web desenvolvido com ASP.NET Core 8, utilizando Entity Framework Core e integração com SQL Server. O objetivo principal é fornecer uma estrutura escalável e segura para aplicações modernas com autenticação integrada e organização em camadas.

## 🚀 Tecnologias Utilizadas

- ASP.NET Core 8  
- Razor Pages  
- Entity Framework Core  
- SQL Server  
- ASP.NET Identity  
- HTML, CSS, JavaScript (via wwwroot)

## 🏛️ Arquitetura do Sistema

O fluxo básico e os principais componentes são:

### 🌐 Interface Web

- **Usuário / Navegador**  
  Interage via HTTPS com a aplicação.
  
- **Razor Views**  
  Responsável pela renderização da interface.

- **wwwroot (CSS/JS)**  
  Arquivos estáticos servidos ao cliente.

### 🔧 Backend (ASP.NET Core App)

- **Controllers**  
  Recebem e manipulam requisições HTTP.

- **Services**  
  Contêm a lógica de negócio.

- **Models**  
  Representações dos dados usados pela aplicação.

- **EstacionamentoContext**  
  Contexto do Entity Framework Core para acesso ao banco.

### 🔐 Autenticação e Identidade

- **ASP.NET Identity**  
  Gerencia login, registro, roles e autenticação.

- **Identity Pages**  
  Páginas dedicadas ao controle de acesso.

### 🗄️ Banco de Dados

- **SQL Server**  
  Utilizado como base de dados relacional.

## 📂 Estrutura Sugerida de Pastas

```
/Controllers
/Models
/Services
/Views
/wwwroot
/Pages (ASP.NET Identity)
/Data (EstacionamentoContext)
```

## 📝 Requisitos

- .NET 8 SDK  
- SQL Server local ou remoto configurado  
- Visual Studio 2022 ou superior (recomendado)

## ▶️ Execução

```bash
dotnet restore
dotnet ef database update
dotnet run
```

## 🤝 Como Contribuir

1. Faça um fork do projeto  
2. Crie uma branch com sua funcionalidade (`git checkout -b minha-feature`)  
3. Faça commit das alterações (`git commit -m 'Minha nova feature'`)  
4. Envie um pull request

Fique à vontade para sugerir melhorias, corrigir erros ou adicionar funcionalidades!

## 📄 Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 📚 Referências

- Documentação oficial do [ASP.NET Core](https://learn.microsoft.com/pt-br/aspnet/core)  
- Exemplos de projetos com [Entity Framework Core](https://learn.microsoft.com/pt-br/ef/core/)  
- Guia de autenticação com [ASP.NET Identity](https://learn.microsoft.com/pt-br/aspnet/core/security/authentication/identity)

---


