# 📱 Calculadora de IMC

Projeto desenvolvido para a disciplina de **Programação Mobile** do curso de **Análise e Desenvolvimento de Sistemas** - 3º Semestre.

## 👤 Informações do Aluno

- **Nome:** Felipe de Castro e Lima 
- **RA:** 24025867
- **Professor:** Vinicius Heltai  
- **Semestre:** 3º  
- **Disciplina:** Programação Mobile  
- **Instituição:** FECAP

## 🧾 Descrição Geral

Este aplicativo Android, desenvolvido em **Java**, tem como objetivo calcular o **Índice de Massa Corporal (IMC)** do usuário a partir dos dados inseridos (peso e altura) e fornecer um **feedback positivo** e personalizado de acordo com a classificação obtida. O app conta com múltiplas telas, interface intuitiva e design baseado em uma paleta de cores definida no enunciado do projeto.

## 🚀 Funcionalidades

- Tela inicial com logo da FECAP e botão de acesso à calculadora;
- Tela de cálculo com campos para entrada de peso e altura, botões de calcular, limpar e voltar;
- Telas de feedback distintas para cada faixa de IMC, com:
  - Exibição do peso, altura, IMC e classificação;
  - Imagem representativa da classificação;
  - Mensagem positiva e motivacional;
  - Botão para voltar à tela inicial;
- Troca de informações entre telas via **Intent** e **Bundle**;
- Utilização de componentes visuais como `PlainText`, `TextView`, `Button` e `ImageView`;
- Design consistente com paleta de cores:
  - Verde Escuro: `#006341`
  - Verde Claro: `#00A859`
  - Cinza Escuro: `#4D4D4D`
  - Cinza Claro: `#B3B3B3`
  - Branco: `#FFFFFF`

## 💡 Processo de Desenvolvimento

Durante o desenvolvimento do projeto, enfrentei certos obstáculos relacionados à navegação entre diversas Activities e à transferência de informações entre elas. Isso me motivou a aprofundar os conhecimentos sobre Intents e Bundles. Além disso, tive um cuidado especial com a organização dos layouts usando arquivos XML, centralizando todos os valores fixos no appValues.xml, o que ajudou a manter uma estrutura mais limpa e reutilizável.

A personalização das mensagens motivacionais e a seleção de imagens específicas para cada faixa de IMC foram pensadas com o objetivo de proporcionar uma experiência mais acolhedora e positiva ao usuário, independentemente de sua classificação.

## 📦 Como Executar o App

Você pode utilizar **qualquer uma das opções abaixo** para abrir e testar o projeto:

### ✅ Opção 1: Usando o link de repositório GitHub

1. Link Respositório:  
   https://github.com/Felima23/CalculadoraIMC-N1

2. Abra o projeto no Android Studio;

3. Conecte um dispositivo ou inicie um emulador;

4. Compile e execute o projeto.


📲 **Instalação direta do app (APK):**  
Tanto na pasta do projeto quanto no `.zip` extraído, você encontrará o arquivo **`app-calculadora-imc.apk`**, que pode ser instalado diretamente em um dispositivo Android.
