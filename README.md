# 🖥️ Instalação Linux & Documentação Técnica

> **Projeto prático de virtualização focado na instalação e configuração do ecossistema Ubuntu no Oracle VM VirtualBox.**

---

## 📋 Visão Geral
Este repositório contém a documentação completa para a criação de um ambiente de desenvolvimento Linux. O guia aborda desde o provisionamento de hardware virtual até as configurações recomendadas para performance.

---

## 🛠️ Infraestrutura Necessária

Antes de iniciar, certifique-se de possuir os seguintes componentes:

| Item | Versão/Requisito | Link |
| :--- | :--- | :--- |
| **VirtualBox** | 7.0 ou Superior | [Download](https://www.virtualbox.org/) |
| **ISO Ubuntu** | Desktop (LTS) | [Download](https://ubuntu.com/download/desktop) |
| **RAM Livre** | 4 GB | - |
| **Disco Livre**| 25 GB | - |

---

## 🚀 Guia de Instalação Passo a Passo

### 1. Preparação e Inicialização
O primeiro passo consiste em localizar o software hospedeiro e iniciar o assistente de provisionamento.

<p align="center">
  <img src="Imagens%20Ubuntu/P1.png" alt="Busca VirtualBox" width="400px">
  <br><em>Legenda: Inicialização do Oracle VM VirtualBox via Menu do Sistema.</em>
</p>

Ao acessar a interface do gerenciador, utilizamos a opção **Novo** para definir os parâmetros básicos da nova instância.

<p align="center">
  <img src="Imagens%20Ubuntu/P2.png" alt="Tela Inicial" width="600px">
  <br><em>Legenda: Interface de gerenciamento pronta para nova instância.</em>
</p>

---

### 2. Definição do Sistema Operacional
Configuramos a identidade da VM. O nome "Ubuntu" permite que o VirtualBox identifique automaticamente o kernel adequado.

> [!IMPORTANTE]
> Optamos por **não selecionar a ISO** neste momento para realizar uma configuração granular dos recursos antes do primeiro boot.

<p align="center">
  <img src="Imagens%20Ubuntu/P3.png" alt="Identificação OS" width="500px">
  <br><em>Legenda: Configuração de nome, diretório e tipo de sistema.</em>
</p>

---

### 3. Alocação de Recursos (Hardware)
Para garantir uma experiência fluida com a interface GNOME, priorizamos o equilíbrio entre a máquina hospedeira e a convidada:

* **Memória Base:** 4096 MB (Ideal para multitarefa inicial).
* **Processadores:** 3 CPUs (Garante estabilidade em processos de atualização).

<p align="center">
  <img src="Imagens%20Ubuntu/P4.png" alt="Configuração Hardware" width="500px">
  <br><em>Legenda: Ajuste de RAM e Processamento.</em>
</p>

---

### 4. Armazenamento Virtualizado
Criamos uma unidade de disco virtual de **25,21 GB**. O formato utilizado é o **VDI (VirtualBox Disk Image)** com alocação dinâmica, garantindo que o espaço seja ocupado no disco físico apenas conforme o uso real.

<p align="center">
  <img src="Imagens%20Ubuntu/P5.png" alt="Disco Virtual" width="500px">
  <br><em>Legenda: Provisionamento de armazenamento persistente.</em>
</p>

---

## 👥 Equipe de Desenvolvimento

| Papel | Integrante | 
| :--- | :--- | 
| **Piloto** | Miguel Regasson Garbeti | 
| **Copiloto** | Matheus Luka Santos da Silva | 

---
