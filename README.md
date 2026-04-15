## 🖥️ Instalação Linux & Documentação
**Passo a passo da instalação do Ubuntu no VirtualBox, incluindo configurações de hardware virtual, Guest Additions e comandos de pós-instalação.**

## 🛠️ Pré-requisitos

**Para reproduzir este ambiente, você precisará de:**
* [Oracle VM VirtualBox](https://www.virtualbox.org/) (Versão 7.0+)
* Imagem ISO do [Ubuntu Desktop](https://ubuntu.com/download/desktop)
* No mínimo **25 GB** de espaço em disco e **4 GB** de memória RAM disponíveis na máquina hospedeira.
  
## 🚀 Passo a Passo da Instalação

### 1. Preparação e Criação da Máquina Virtual (VM)

Iniciamos o processo abrindo o VirtualBox para dar início ao assistente de criação.

![Busca e abertura do VirtualBox no Windows](Imagens%20Ubuntu/P1.png)
*Legenda: Acessando o VirtualBox via menu iniciar.*

Ao abrir o gerenciador, clicamos no botão **Novo** para começar.

![Tela principal do VirtualBox Gerenciador](Imagens%20Ubuntu/P2.png)
*Legenda: Janela inicial do VirtualBox, pronta para criação de uma nova VM.*

#### Definição de Nome e Sistema Operacional
Nesta etapa, atribuímos o nome "Ubuntu" à máquina e verificamos se o tipo (Linux) e a versão (Ubuntu 64-bit) foram detectados corretamente. Neste guia, não selecionaremos a ISO neste momento, optando pela instalação manual mais adiante.

![Configuração de Nome e OS da VM](Imagens%20Ubuntu/P3.png)
*Legenda: Tela de identificação da nova máquina virtual.*

### 2. Configuração do Hardware Virtual

Iniciamos o provisionamento detalhado dos recursos para garantir um bom desempenho da interface gráfica GNOME do sistema. Asseguramos que os recursos mínimos exigidos para a atividade fossem respeitados.

* **Memória RAM:** Alocamos **4096 MB** (4 GB).
* **Processador:** Reservamos **3 núcleos** de CPU para o ambiente virtualizado.

![Alocação de RAM e CPU](Imagens%20Ubuntu/P4.png)
*Legenda: Tela de configuração dos recursos de hardware.*

### 3. Configuração do Disco Rígido Virtual

Para o armazenamento do sistema e dados, criamos um novo disco rígido virtual. Alocamos o espaço solicitado de **25,21 GB**, utilizando o formato dinamicamente alocado (padrão do VirtualBox) para otimizar o uso de espaço no disco físico.

![Criação do Disco Virtual](Imagens%20Ubuntu/P5.png)
*Legenda: Etapa de definição do tamanho e tipo do disco virtual.*

👥 Autores

**[Miguel Regasson Garbeti] - Piloto (Configuração e Instalação)** 

**[Matheus Luka Santos da Silva] - Copiloto (Documentação e Prints)**
