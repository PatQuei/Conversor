# 🌍💸 Conversor de Moedas — Java Edition

**Um projeto feito para quem gosta de tecnologia, aprendizado na prática e… dinheiro bem convertido!**
Com API em tempo real, menu interativo e aquele toque de cor no terminal pra deixar tudo mais vivo.

---

## 🚀 O que esse projeto faz?

✨ Converte moedas em tempo real (BRL, USD, EUR, GBP)
✨ Usa uma API de câmbio atualizada
✨ Valida entradas e evita erros bobos
✨ Formata valores com símbolo de moeda certinho
✨ Tem cores no terminal (porque a gente não nasceu pra viver no cinza)
✨ É organizado, modular e fácil de expandir

---

## 🖥️ Interface no Terminal

Uma vibe simples, direta e colorida:

```
==============================
      CONVERSOR DE MOEDAS     
==============================
1. USD -> BRL
2. BRL -> USD
3. EUR -> BRL
4. BRL -> EUR
5. GBP -> BRL
6. BRL -> GBP
0. Sair
```

---

## 📁 Estrutura do Projeto

Tudo pensado para manter o código limpo e organizado:

```
src/
 ├── Main.java                 → inicia o app e formata moedas
 ├── CurrencyMenu.java         → menu, cores, validações
 ├── CurrencyConverter.java    → lógica da conversão
 ├── ExchangeRateClient.java   → comunicação com a API
 └── ExchangeRateResponse.java → modelo da resposta JSON
```

---

## 🔧 Tecnologias que você vai ver aqui

🟣 Java 17+
🟣 Gson para ler JSON
🟣 HttpClient para requisições
🟣 ExchangeRate API
🟣 ANSI Colors
🟣 NumberFormat (formatação monetária)

---

## ▶️ Como rodar o projeto

1. **Clone o repositório:**

```bash
git clone https://github.com/PatQuei/Conversor/tree/main
```

2. **Entre no diretório e compile:**

```bash
javac Main.java
```

3. **Execute:**

```bash
java Main
```

E pronto! O menu aparece e você já pode converter à vontade.

---

## 💰 Exemplo de conversão

```
Digite o valor em USD:
100

Resultado: R$ 574,32
```

---

## 🌐 API utilizada

* ExchangeRate API
  (fornece taxas atualizadas de dezenas de moedas)

---

## 📘 O que eu aprendi construindo isso?

💡 Consumir APIs REST em Java
💡 Organizar um projeto modular
💡 Tratar exceções e inputs do usuário
💡 Formatar números e moedas
💡 Trabalhar com mapas, JSON e validação
💡 Deixar a experiência mais humana e divertida com cores

---

## 📌 Próximos passos (to-do)

* [ ] Permitir que o usuário digite as moedas (ex: “USD”, “JPY”)
* [ ] Adicionar mais moedas
* [ ] Criar logs de conversão
* [ ] Mostrar a data/hora da última taxa recebida
* [ ] Criar testes unitários
* [ ] Criar uma versão GUI usando JavaFX (por que não?)

---

## ✨ Autora

**Patricia Queiroz**
Desenvolvedora em transição | Apaixonada por tecnologia e inclusão

💼 LinkedIn: [https://www.linkedin.com/in/patricia-pq](https://www.linkedin.com/in/patyqueiroz/)

🌐 Portfólio: [https://portifolio-patricia.vercel.app/](https://portifolio-patricia.vercel.app/)


