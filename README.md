# 🌤️ MauiAppTempoAgora

Aplicativo de previsão do tempo desenvolvido com .NET MAUI, que consome dados da API OpenWeatherMap e exibe informações climáticas atualizadas com base na cidade informada pelo usuário.

## 🚀 Tecnologias Utilizadas

- [.NET MAUI](https://learn.microsoft.com/pt-br/dotnet/maui/what-is-maui)
- [C#](https://learn.microsoft.com/pt-br/dotnet/csharp/)
- [OpenWeatherMap API](https://openweathermap.org/api)
- [Newtonsoft.Json](https://www.newtonsoft.com/json)

## 📱 Funcionalidades

- Consulta da previsão do tempo por cidade
- Informações exibidas:
  - Temperatura mínima e máxima
  - Clima atual (ex: "nublado", "ensolarado")
  - Velocidade do vento
  - Visibilidade
  - Horário do nascer e pôr do sol
  - Latitude e longitude da cidade

## 🧱 Estrutura do Projeto

```bash
MauiAppTempoAgora/
├── Models/
│   └── Tempo.cs         # Modelo que representa os dados climáticos
├── Services/
│   └── DataService.cs   # Classe responsável por consumir a API
├── App.xaml             # Configuração da aplicação
├── App.xaml.cs          # Inicialização e definição da página principal
├── MainPage.xaml        # Interface principal do app
└── MainPage.xaml.cs     # Lógica da página principal

```

 ## 🔑 Configuração da API
Este projeto utiliza a API do OpenWeatherMap para obter os dados climáticos.

Crie uma conta gratuita no OpenWeatherMap

Gere uma chave de API

No arquivo DataService.cs, substitua o valor da variável chave pela sua key:

```
string chave = "SUA_CHAVE_AQUI";
```

## 💡 Exemplos de Uso
Ao digitar o nome de uma cidade, como São Paulo, o app retorna:

🌡️ Temp. mínima: 18°C

🌡️ Temp. máxima: 25°C

☁️ Clima: Nublado

💨 Vento: 2.5 m/s

👁️ Visibilidade: 10000 metros

🌅 Nascer do sol: 06:12

🌇 Pôr do sol: 18:09

 ## ⚠️  Avisos
Certifique-se de estar conectado à internet para que as requisições funcionem.

A interface pode variar conforme a plataforma (Android, iOS, Windows).

## 🛠️ Melhorias Futuras
Salvamento de cidades favoritas

Previsão para os próximos dias

Suporte a múltiplos idiomas

Tema claro/escuro


## 👩‍💻 Desenvolvido por
Jeisa Boaventura ⭐
