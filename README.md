# Por enquanto não é ensinado como se monta este circuito, mas é demonstrado cada componente e suas respectivas ligações

# Processador (CPU) de 4 Bits - Simulação Lógica - LOGISIM

Este repositório contém o projeto e a documentação de uma CPU de 4 bits desenvolvida no **Logisim**. O projeto foi realizado como requisito parcial do curso de **Engenharia da Computação** do **IFMA - Campus Santa Inês**.

## 🎥 Demonstração

Clique na imagem abaixo para assistir ao vídeo explicativo e ver a simulação em funcionamento:

[![Vídeo de Demonstração da CPU 4 Bits](https://img.youtube.com/vi/o9Nfv4Ewrzc/maxresdefault.jpg)](https://www.youtube.com/watch?v=o9Nfv4Ewrzc)

---

## 📋 Sobre o Projeto

O objetivo deste projeto é demonstrar o funcionamento interno de um processador básico, implementando componentes fundamentais de arquitetura de computadores, como Unidade Lógica e Aritmética (ULA), Banco de Registradores, Memória RAM e Unidade de Controle.

### Principais Componentes:
* **ULA (ALU):** Responsável por operações aritméticas e lógicas.
* **Banco de Registradores (RegFile):** Armazenamento temporário de dados.
* **Memória RAM/ROM:** Armazenamento de dados e instruções.
* **Decodificador de Instruções:** Interpretação dos opcodes.
* **Contador de Programa (PC):** Controle do fluxo de execução.

## ⚙️ Conjunto de Instruções (ISA Simplificado)

O processador opera com um conjunto reduzido de instruções, identificadas pelos seus códigos binários (Opcodes):

| Opcode | Mnemônico | Descrição |
| :--- | :--- | :--- |
| **00** | `DATA` | Carrega um valor imediato para um registrador. |
| **11** | `MOV` | Move dados entre registradores (ex: A -> B). |
| **10** | `STORE` | Armazena valor na memória (Modos: Direto ou via Registrador). |
| **10** | `LOAD` | Carrega valor da memória para um registrador. |

> *Consulte o arquivo `REL_CPU_4BITS.pdf` neste repositório para detalhes completos sobre o fluxo de dados e diagramas.*

## 🚀 Como Executar

Para visualizar e simular o funcionamento do processador:

1. Recomendo fortemente usar o logisim disponibilizado neste repositório para garantir que não dê erros.
2. Basta extrair a pasta dentro do .zip, entrar na pasta e clicar duas vezes no arquivo "logisim-dark-generic-0.9.9"
3. Lembre-se de que ée necessário ter o Java e creio que o JDK instalados previamente em sua máquina.

# Logisim-Dark Não abre ou tela preta:
1. Caso o programa não abra ou demore demais para entrar, basta abrir a pasta onde se encontra o arquivo .jar pelo CMD e digitar:
2. "java -jar logisim-dark-generic-0.9.9" (sem as aspas).

## 📄 Documentação

O relatório técnico completo (`REL_CPU_4BITS.pdf`) está disponível na raiz do projeto, contendo:
* Diagramas detalhados dos subcircuitos.
* Explicação passo a passo do ciclo de busca e execução.
* Detalhamento da lógica de controle.

## 👨‍💻 Autor

**Francisco Kleyton de Lima Saldanha**
* Instituto Federal do Maranhão (IFMA) - Campus Santa Inês
* Ano: 2025

---
*Este projeto é para fins educacionais.*
