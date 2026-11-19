# Introdução passo a passo ao framework ASP.NET Core MVC

**O curso está disponível online aqui: [https://stahe.github.io/br-aspnetcoremvc-sept-2026/](https://stahe.github.io/br-aspnetcoremvc-sept-2026/)**

## Visão geral

Este curso apresenta um guia passo a passo para construir uma aplicação web MVC com **ASP.NET Core MVC** (.NET 10, C#). As páginas HTML são geradas pelo servidor usando views **Razor**, sem um framework JavaScript no navegador.

Ele dá continuidade ao curso *Introdução passo a passo ao framework web NestJS* (2026) e segue exatamente a mesma estrutura:

1. **28 exemplos curtos**, cada um focado em um conceito específico:
   - controllers, actions e roteamento;
   - modelo de action: binding de parâmetros, conversão e validação;
   - views Razor: templates, views parciais, helpers e Tag Helpers;
   - formulários, validação e o padrão Post/Redirect/Get (TempData);
   - internacionalização (francês/inglês);
   - escopos de dados: Singleton, Scoped e Transient; cookies;
   - ciclo de vida da requisição: middleware, filtros, páginas de erro;
   - autenticação por meio de um token JWT em um cookie, papéis, CAPTCHA e limitação de taxa (rate limiting);
   - arquitetura em camadas (Web / Negócio / DAO) com **Entity Framework Core** e **MySQL**.
2. **Um estudo de caso completo**, *RdvMedecins*: uma aplicação de agendamento de consultas para um consultório médico, com três papéis (administrador, médicos, pacientes). O curso fornece explicações detalhadas para cada um de seus arquivos.

Os leitores não precisam de nenhum conhecimento prévio de ASP.NET Core: cada exemplo é comentado linha por linha, e o curso indica a URL exata a ser testada em cada um.

## Ambiente

- .NET SDK 10
- Visual Studio Code + extensão C# Dev Kit
- MySQL (por exemplo, com o Laragon)
- curl

## Autor

Este curso foi escrito por **Claude** (Anthropic) a pedido de Serge Tahé — setembro de 2026.
