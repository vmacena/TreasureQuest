# TreasureQuest

## 📌 Sobre o Projeto
TreasureQuest é um sistema para criar e organizar caças ao tesouro, gerando automaticamente pistas e enigmas adaptados à idade das crianças, ao espaço disponível (aberto ou fechado) e aos brinquedos do local.

## 🚀 Funcionalidades
- Geração automática de pistas e enigmas.
- Adaptação ao ambiente e idade das crianças.
- Criação de um roteiro com sequência lógica das pistas.
- Opção de personalizar as pistas.
- Exportação das pistas em PDF.

## 🛠️ Tecnologias Utilizadas
- **Frontend:** React (ou Blazor para web)
- **Backend:** C# com .NET
- **Banco de Dados:** PostgreSQL
- **Hospedagem:** ?

## 📦 Como Rodar o Projeto
### Backend
```bash
git clone https://github.com/seu-usuario/treasurequest.git
cd treasurequest/backend
dotnet restore
dotnet run
```

## 📄 Estrutura do Banco de Dados
- **users** → Armazena os usuários do sistema.
- **hunts** → Representa cada caça ao tesouro criada.
- **clues** → Guarda as pistas e enigmas.
- **locations** → Define os locais onde as pistas podem ser escondidas.

## 🤝 Contribuindo
1. Faça um fork do repositório
2. Crie uma branch (`feature/minha-feature`)
3. Commit suas mudanças (`git commit -m 'Adiciona minha feature'`)
4. Faça um push para a branch (`git push origin minha-feature`)
5. Abra um Pull Request

## 📜 Licença
Este projeto está sob a licença MIT. Sinta-se livre para contribuir! 🎉

