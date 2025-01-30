# Calculadora de IMC

Este projeto Flutter permite calcular o Índice de Massa Corporal (IMC) com base no peso e altura do usuário. O aplicativo fornece uma classificação do IMC e permite resetar os valores inseridos.

## 📌 Funcionalidades
- Entrada de peso (kg) e altura (cm).
- Cálculo automático do IMC.
- Exibição da classificação do IMC.
- Botão de reset para limpar os campos.

## 🛠 Tecnologias Utilizadas
- **Flutter**: SDK para desenvolvimento de aplicativos multiplataforma.
- **Dart**: Linguagem de programação usada no Flutter.
- **Material Design**: Design padrão para interface de usuário no Flutter.

## 📦 Dependências
```yaml
dependencies:
  flutter:
    sdk: flutter
```

## 🚀 Como Rodar o Projeto
1. **Clone o repositório**
   ```sh
   git clone https://github.com/seu-usuario/calculadora_imc.git
   cd calculadora_imc
   ```
2. **Instale as dependências**
   ```sh
   flutter pub get
   ```
3. **Execute o projeto**
   ```sh
   flutter run
   ```

## 🖼️ Estrutura do Projeto
```
/lib
  ├── main.dart            # Arquivo principal do aplicativo
  ├── home.dart            # Tela principal com a lógica do IMC
  ├── widgets/
      ├── imc_form.dart    # Widget responsável pela entrada de dados
/assets
  ├── logo_app_imc.png   # Ícone do aplicativo

```

## 🔍 Cálculo do IMC
```sh
double imc = peso / (altura * altura);
```

## 📄 Licença
Este projeto está licenciado sob a [MIT License](LICENSE).