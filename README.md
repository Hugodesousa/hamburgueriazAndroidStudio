# 🍔 HamburgueriaZ

Aplicativo Android simples desenvolvido em Kotlin para simular um pedido de hambúrguer.

## 📱 Funcionalidades

* Inserir nome do cliente
* Selecionar adicionais:

  * Bacon (+ R$2)
  * Queijo (+ R$2)
  * Onion Rings (+ R$3)
* Escolher quantidade de hambúrgueres
* Exibir resumo do pedido
* Calcular preço total automaticamente
* Enviar pedido por e-mail

## 🧮 Regras de cálculo

* Preço base do hambúrguer: **R$ 20,00**
* Adicionais são somados ao valor base
* O total é multiplicado pela quantidade escolhida

## 📧 Envio de pedido

Ao clicar em **"Enviar Pedido"**, o app:

* Abre o aplicativo de e-mail do dispositivo
* Preenche automaticamente:

  * Assunto: `Pedido de (nome do cliente)`
  * Corpo: resumo completo do pedido

## 🛠️ Tecnologias utilizadas

* Kotlin
* Android SDK (API 23+)
* XML (Layouts)

## 🎯 Objetivo

Projeto acadêmico com foco em:

* Manipulação de interface (UI)
* Eventos de clique
* Lógica de cálculo
* Uso de Intents no Android

## ▶️ Como executar

1. Clone o repositório
2. Abra no Android Studio
3. Execute em um dispositivo físico ou emulador

---

Feito para fins de aprendizado 📚
