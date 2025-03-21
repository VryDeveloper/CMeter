# CMeter - Calculadora de Pegada de Carbono

## 📌 Sobre o Projeto
O **CMeter** é um aplicativo que mede a pegada de carbono das pessoas com base em suas ações do dia a dia. Ele utiliza a API **Carbon Interface** para calcular as emissões de CO₂ de diferentes atividades, como transporte, consumo de energia e alimentação.

## 🚀 Tecnologias Utilizadas
- **Android Studio** - Ambiente de desenvolvimento
- **Jetpack Compose** - Construção da interface moderna e declarativa
- **Kotlin** - Linguagem principal do aplicativo
- **API Carbon Interface** - Para calcular as emissões de carbono
- **Retrofit** - Para consumo da API
- **MVVM** - Arquitetura utilizada para separação de responsabilidades
- **Room Database** - Para armazenamento local de dados

## 🎯 Funcionalidades
✔️ Cadastro de atividades diárias que geram emissões de carbono  
✔️ Cálculo automatizado da pegada de carbono com base na API Carbon Interface  
✔️ Histórico de emissões para acompanhamento  
✔️ Interface intuitiva e responsiva usando Jetpack Compose  
✔️ Suporte a múltiplas categorias de emissões (transporte, energia, alimentação)  

## 📦 Como Instalar e Executar
1. Clone este repositório:
   ```sh
   git clone https://github.com/seuusuario/CMeter.git
   ```
2. Abra o projeto no **Android Studio**.
3. Configure sua chave da API Carbon Interface no arquivo `gradle.properties`:
   ```properties
   CARBON_API_KEY= "SUA_CHAVE_AQUI"
   ```
4. Sincronize o projeto e execute o aplicativo em um emulador ou dispositivo físico.

## 🔗 API Utilizada
O CMeter utiliza a **Carbon Interface API** para obter informações precisas sobre emissões de carbono. Mais detalhes podem ser encontrados na [documentação oficial](https://www.carboninterface.com/docs).

## 🛠 Melhorias Futuras
🔹 Implementação de notificações personalizadas  
🔹 Suporte para novos tipos de atividades  
🔹 Sincronização com banco de dados na nuvem  

## 🤝 Contribuição
Fique à vontade para contribuir com melhorias! Para isso:
1. Faça um **fork** do projeto
2. Crie uma nova **branch** (`git checkout -b feature/sua-feature`)
3. Faça o **commit** das suas alterações (`git commit -m 'Adiciona nova feature'`)
4. Faça o **push** para a branch (`git push origin feature/sua-feature`)
5. Abra um **Pull Request**

## 📄 Licença
Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.

---
Desenvolvido por **Victor Augusto** 🚀
