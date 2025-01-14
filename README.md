<a href="https://github.com/AdaoG0n" style="pointer-events: none;"> <img src="https://github.com/AdaoG0n/AdaoG0n/blob/main/assests/Followbutton.png" width="130" align="right"/></a>

# <a href="#" style="pointer-events: none;"><img src="https://img.shields.io/github/last-commit/AdaoG0n/GIT_Tutorial?style=flat-square&color=%2312bab9" /> </a>

![](https://github.com/AdaoG0n/AdaoG0n/blob/main/assests/bar.png)
<div align="center"> 

  # Guia de Instalação e Primeiros Passos no Git
</div>

O Git é um sistema de controlo de versão amplamente utilizado para gerir e versionar o código fonte dos projetos. Neste guia, vais aprender como instalar o Git em diferentes sistemas operativos e realizar os primeiros passos para começares a usar o Git de forma eficaz.

<p align="center">
  <a href="#1-linux-debianubuntu-e-derivados">Linux (Debian/Ubuntu e derivados)</a>  •  
  <a href="#2-linux-fedorarhelcentos">Linux (Fedora/RHEL/CentOS)</a>  •  
  <a href="#3-linux-arch-linux">Linux (Arch Linux)</a>  •  
  <a href="#4-macos">macOS</a>  •  
  <a href="#5-windows">Windows</a>  •  
  <a href="#6-verificação-da-instalação">Verificação da Instalação</a>  •  
  <a href="#7-primeiros-passos-no-git">Primeiros Passos no Git</a>
</p>

![](https://github.com/AdaoG0n/AdaoG0n/blob/main/assests/bar.png)
<div align="center"> 

  ## 1. Linux (Debian/Ubuntu e derivados)
</div>
No Linux, podes instalar o Git facilmente usando o gestor de pacotes.

Abre o terminal e executa o seguinte comando:

- `sudo apt update`
- `sudo apt install git`

![](https://github.com/AdaoG0n/AdaoG0n/blob/main/assests/bar.png)
<div align="center"> 

  ## 2. Linux (Fedora/RHEL/CentOS)
</div>

Se utilizas Fedora, RHEL ou CentOS, usa o `dnf` ou `yum`:

- `sudo dnf install git   # Fedora`
- Ou, para RHEL/CentOS:
- `sudo yum install git`

![](https://github.com/AdaoG0n/AdaoG0n/blob/main/assests/bar.png)
<div align="center"> 

  ## 3. Linux (Arch Linux)
</div>

Se estiveres a usar Arch Linux ou derivados (como Manjaro), usa o `pacman`:

- `sudo pacman -S git`

![](https://github.com/AdaoG0n/AdaoG0n/blob/main/assests/bar.png)
<div align="center"> 

  ## 4. macOS
</div>

No macOS, o Git pode ser instalado usando o Homebrew. Primeiro, certifica-te de que tens o Homebrew instalado. Se não tiveres, instala-o com o seguinte comando:

- `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

Depois, instala o Git com o Homebrew:

- `brew install git`

![](https://github.com/AdaoG0n/AdaoG0n/blob/main/assests/bar.png)
<div align="center"> 

  ## 5. Windows
</div>

No Windows, o Git pode ser instalado facilmente através do Git for Windows.

1. Descarrega o instalador do Git for Windows em: [Git for Windows](https://git-scm.com/download/win)
2. Executa o instalador e segue as instruções na tela.

![](https://github.com/AdaoG0n/AdaoG0n/blob/main/assests/bar.png)
<div align="center"> 

  ## 6. Verificação da Instalação
</div>

Após a instalação, podes verificar se o Git foi instalado corretamente com o comando:

- `git --version`

Este comando irá mostrar a versão do Git instalada no teu sistema.

![](https://github.com/AdaoG0n/AdaoG0n/blob/main/assests/bar.png)
<div align="center"> 

  ## 7. Primeiros Passos no Git
</div>

Agora que tens o Git instalado, é hora de configurar e começar a utilizá-lo. Vamos configurar o teu nome de utilizador e e-mail no Git:

- `git config --global user.name "Teu Nome"`
- `git config --global user.email "teuemail@exemplo.com"`

Essas configurações serão usadas em todos os repositórios Git no teu sistema.

### Criar um novo repositório

Para criar um novo repositório Git, usa o comando:

- `git init`

Este comando cria um repositório Git vazio no diretório atual.

### Clonar um repositório existente

Se quiseres clonar um repositório Git existente, usa:

- `git clone <url-do-repositorio>`

### Verificar o estado do repositório

Para ver o estado do teu repositório (quais arquivos foram modificados, adicionados, etc.), usa:

- `git status`

### Adicionar arquivos

Para adicionar arquivos ao teu repositório, usa o comando:

- `git add <arquivo>`

Se quiseres adicionar todos os arquivos modificados, usa:

- `git add .`

### Fazer um commit das alterações

Após adicionar os arquivos, podes guardar as alterações com o commit:

- `git commit -m "Mensagem do commit"`

### Enviar as alterações para o repositório remoto

Para enviar as tuas alterações para um repositório remoto, usa:

- `git push`

Se for a primeira vez que estás a fazer o push, pode ser necessário definir o repositório remoto:

- `git remote add origin <url-do-repositorio>`
- `git push -u origin master`

Agora já podes começar a usar o Git para gerir os teus projetos de forma eficiente!
