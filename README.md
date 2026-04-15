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
Com as configurações de hardware finalizadas, a máquina virtual aparece na lista do gerenciador, pronta para receber o sistema operacional.

![Resumo da Máquina](Imagens%20Ubuntu/P6.png)

---

### 6. Inserindo a Imagem ISO (Disco de Instalação)
Antes de ligar a máquina, precisamos colocar o "CD de instalação". Fomos em **Configurações > Armazenamento**. O drive óptico virtual aparece inicialmente como "Vazio".

![Armazenamento Vazio](Imagens%20Ubuntu/P7.png)

Clicamos no ícone de disco e adicionamos a ISO do Ubuntu que baixamos anteriormente.

![Adicionando ISO](Imagens%20Ubuntu/P8.png)

Com a imagem ISO carregada com sucesso, a máquina virtual está totalmente configurada e pronta para o primeiro boot.

![Pronto para Iniciar](Imagens%20Ubuntu/P9.png)

---

### 7. Inicialização e Boot
Ao clicar no botão verde **Iniciar**, a máquina liga e mostra o menu do GRUB. Selecionamos a primeira opção ("Try or Install Ubuntu").

![Menu de Boot](Imagens%20Ubuntu/P10.png)

Durante os primeiros segundos, o sistema carrega os arquivos básicos, mostrando os logs no terminal antes de subir o ambiente visual.

![Logs do Terminal](Imagens%20Ubuntu/P11.png)

---

### 8. Assistente de Instalação do Ubuntu
Quando a interface gráfica do instalador abre, somos recebidos pela tela inicial de configuração.

![Tela de Boas Vindas](Imagens%20Ubuntu/P12.png)

A primeira ação é alterar o idioma do instalador para **Português do Brasil**.

![Tela de Idioma](Imagens%20Ubuntu/P13.png)

Avançando nas etapas (teclado, rede, particionamento), chegamos na tela de criação de conta. Aqui definimos nosso usuário administrador, a senha e o nome da máquina.

![Criação de Usuário](Imagens%20Ubuntu/P14.png)

Logo chegamos a etapa de inicialização do sistema

![Inicialização sistema Ubuntu](Imagens%20Ubuntu/P15.png)

---

## 👥 Equipe

* **Piloto:** Miguel Regasson Garbeti (Configuração e Instalação)
* **Copiloto:** Matheus Luka Santos da Silva (Documentação e Prints)

---
