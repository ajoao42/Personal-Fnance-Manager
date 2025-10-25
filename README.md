# Personal Finance Manager - .NET MAUI Desktop

Aplicativo Desktop multiplataforma criado com **.NET MAUI**, voltado para gerenciamento financeiro pessoal.  
Permite registrar despesas e receitas, gerar relatórios e visualizar gráficos simples de gastos.

---

## 🚀 Tecnologias
- C# / .NET 8
- .NET MAUI (XAML + MVVM)
- SQLite (armazenamento local)
- Charting com Microcharts
- MVVM + Data Binding
- Suporte Windows e MacOS (opcional)

---

## ⚙️ Funcionalidades
- Cadastro de despesas e receitas
- Relatórios mensais e gráficos de despesas
- Filtros por categoria (alimentação, transporte, lazer etc.)
- Layout responsivo para Desktop
- Persistência local com SQLite

---

## 🧩 Como executar

```bash
# Clonar o repositório
git clone https://github.com/seuusuario/personal-finance-manager.git
cd personal-finance-manager

# Restaurar dependências
dotnet restore

# Executar no Windows
dotnet build -t:Run -f net8.0-windows10.0.19041.0

# Executar no MacOS
dotnet build -t:Run -f net8.0-macos
