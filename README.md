# 🖥️ Instalação Linux & Documentação

Este projeto é um guia prático para a instalação do Linux Ubuntu usando o VirtualBox. Aqui documentamos todo o passo a passo da configuração da máquina virtual.

---

## 🛠️ O que você vai precisar

* **VirtualBox 7.0+** ([Baixar aqui](https://www.virtualbox.org/))
* **ISO do Ubuntu Desktop** ([Baixar aqui](https://ubuntu.com/download/desktop))
* **Espaço em disco:** 25 GB
* **Memória RAM:** 4 GB

---

## 🚀 Passo a Passo

### 1. Criando a Máquina Virtual
Primeiro, abrimos o VirtualBox e clicamos no botão **Novo**.

![Abertura do VirtualBox](Imagens%20Ubuntu/P1.png)


![Botão Novo](Imagens%20Ubuntu/P2.png)


---

### 2. Nome e Sistema
Damos o nome de **Ubuntu** para a máquina. O VirtualBox já reconhece automaticamente que o sistema é Linux.

> **Nota:** Não selecionamos a imagem ISO nesta tela para configurar o hardware primeiro.

![Nome do Sistema](Imagens%20Ubuntu/P3.png)


---

### 3. Configuração de Hardware (RAM e CPU)
**Escolhemos os recursos que a máquina vai usar:**
* **Memória RAM:** 4096 MB (4 GB)
* **Processadores:** 3 núcleos de CPU

![Configuração de Hardware](Imagens%20Ubuntu/P4.png)


---

### 4. Disco Rígido Virtual
Criamos um disco virtual com **25,21 GB** para instalar o sistema e guardar os arquivos.

![Disco Virtual](Imagens%20Ubuntu/P5.png)


---

### 5. Resumo da Máquina Criada
Com as configurações finalizadas, a máquina virtual aparece na lista do gerenciador, pronta para receber o sistema operacional.

![Resumo da Máquina](Imagens%20Ubuntu/P6.png)

---

### 6. Inserindo a Imagem ISO (Disco de Instalação)
Antes de ligar a máquina, precisamos colocar o "CD de instalação". Fomos em **Configurações > Armazenamento** e adicionamos a ISO do Ubuntu baixada no drive óptico virtual.

![Adicionando ISO](Imagens%20Ubuntu/P13.jpg)

---

### 7. Inicialização e Boot
Ao clicar em **Iniciar**, a máquina liga e mostra o menu do GRUB. Selecionamos a primeira opção para instalar o Ubuntu.

![Menu de Boot](Imagens%20Ubuntu/P11.jpg)

Durante os primeiros segundos, o sistema carrega os arquivos básicos mostrando os logs no terminal, antes de abrir a tela gráfica.

![Logs do Terminal](Imagens%20Ubuntu/P10.png)

---

### 8. Instalação do Sistema
Quando a interface gráfica do instalador abre, a primeira etapa é selecionar o idioma **Português do Brasil**.

![Tela de Idioma](Imagens%20Ubuntu/P8.png)

Seguindo o assistente, chegamos na etapa final de configuração, onde criamos o nosso usuário administrador, definimos a senha e o nome do computador.

![Criação de Usuário](Imagens%20Ubuntu/P7.png)

---

## 👥 Equipe

* **Piloto:** Miguel Regasson Garbeti (Configuração e Instalação)
* **Copiloto:** Matheus Luka Santos da Silva (Documentação e Prints)

---
