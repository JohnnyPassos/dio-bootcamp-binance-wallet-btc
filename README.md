# Bitcoin Wallet Generator (HD) – DIO + Binance (TESTNET)

> **Bootcamp DIO em parceria com Binance**  
> Desafio prático: Gerador de carteiras Bitcoin **na TESTNET**  
> Usa **BIP-32**, **BIP-39** e **BIP-44** para gerar:  
> → **Seed phrase**  
> → **Chave privada (WIF)**  
> → **Endereço P2PKH (Testnet – começa com `m` ou `n`)**

![TESTNET](https://img.shields.io/badge/Network-Testnet-orange?style=for-the-badge)
![DIO Bootcamp](https://img.shields.io/badge/DIO-Bootcamp-blue?style=for-the-badge)
![Binance Partner](https://img.shields.io/badge/Binance-Partner-yellow?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?style=for-the-badge)
![Node.js](https://img.shields.io/badge/Node.js-18%2B-green?style=for-the-badge)
![Status](https://img.shields.io/badge/status-concluded-brightgreen?style=for-the-badge)

---

## Funcionalidades

- Geração de **seed phrase** (BIP-39)
- Derivação HD: `m/44'/1'/0'/0/0` → **Testnet (coin type 1)**
- Chave privada em **WIF** (formato testnet)
- Endereço **P2PKH Testnet** (ex: `mv4rny92...`, `n2d...`)
- 100% seguro para testes — **sem risco de perda real**

---

## Tecnologias

| Biblioteca | Finalidade |
|----------|----------|
| `bip39` | Seed phrase |
| `bip32` | Derivação HD |
| `bitcoinjs-lib` | Rede Testnet + P2PKH |

---

## Como Executar

```bash
git clone https://github.com/JohnnyPassos/dio-bootcamp-binance-wallet-btc.git
cd dio-bootcamp-binance-wallet-btc
npm install
node src/wallet-generator.js
