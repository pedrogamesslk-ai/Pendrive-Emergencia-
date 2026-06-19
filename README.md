# Pendrive Emergencia

Um Pendrive Emergencia para manutenção, recuperação, diagnóstico e reinstalação de sistemas operacionais.

O objetivo deste projeto é reunir em um único local as principais ferramentas que podem ser necessárias quando um computador apresenta problemas ou precisa ser formatado.

---

# Recursos

✅ Instalação de múltiplos sistemas operacionais com Ventoy

✅ Ferramentas de diagnóstico

✅ Programas essenciais para pós-formatação

✅ Drivers Intel e AMD

✅ Estrutura organizada para armazenamento de ISOs

✅ Compatível com pendrives e HDs externos

---

# Requisitos

Antes de utilizar este projeto, o dispositivo deve estar configurado com o Ventoy.

Recomendações:

- Utilizar esquema de partição GPT
- Utilizar Ventoy atualizado
- Possuir espaço suficiente para ISOs e programas
- Utilizar modo UEFI sempre que possível

---

# Estrutura do Projeto

```text
Pendrive Emergencia
│
├── ISOs
├── Programas
├── Drivers AMD
├── Drivers INTEL
├── ventoy
└── README.md
```

---

# Conteúdo do Kit

## Sistemas Operacionais

As imagens ISO não acompanham o projeto e devem ser baixadas manualmente.

Exemplos:

- Windows 10
- Windows 11
- Ubuntu
- Linux Mint

Sempre utilize fontes oficiais para baixar sistemas operacionais.

---

## Drivers

### Intel

- Drivers de Chipset
- Drivers de Rede Wi-Fi
- Utilitários Intel

### AMD

- Drivers gráficos
- Utilitários Ryzen
- Ferramentas AMD

---

## Programas Inclusos

- 7-Zip
- Google Chrome
- Mozilla Firefox
- VLC Media Player
- CPU-Z
- CrystalDiskInfo
- Steam
- Epic Games Launcher
- Notepad++
- WinRAR
- Rufus
- Ventoy

---

# Como Instalar o Ventoy

## 1. Baixe o Ventoy

Faça o download da versão mais recente do Ventoy.

## 2. Conecte o dispositivo

Conecte o pendrive ou HD externo que será utilizado.

⚠️ Todos os dados existentes serão apagados.

## 3. Abra o Ventoy

Execute:

```text
Ventoy2Disk.exe
```

como Administrador.

## 4. Configure o dispositivo

Recomendações:

- Secure Boot Support: Ativado
- Partition Style: GPT

## 5. Instale o Ventoy

Clique em:

```text
Install
```

e confirme as mensagens exibidas.

---

# Como Utilizar o Kit

## Passo 1

Extraia os arquivos do projeto.

## Passo 2

Copie as pastas para o dispositivo configurado com Ventoy.

## Passo 3

Adicione as ISOs desejadas.

Exemplo:

```text
Windows11.iso
Windows10.iso
Ubuntu.iso
LinuxMint.iso
```

## Passo 4

Reinicie o computador.

## Passo 5

Abra o Menu de Boot.

As teclas mais comuns são:

```text
F12
F11
F9
ESC
```

(depende do fabricante)

## Passo 6

Selecione o dispositivo onde o Ventoy foi instalado.

## Passo 7

Escolha a ISO desejada e prossiga normalmente.

---

# Exemplo de Utilização

Situações em que este kit pode ser útil:

- Formatação do Windows
- Recuperação de sistemas
- Teste de distribuições Linux
- Instalação de drivers
- Diagnóstico de hardware
- Recuperação de computadores sem sistema operacional

---

# Avisos

⚠️ Faça backup dos seus arquivos antes de qualquer instalação.

⚠️ O Ventoy apagará os dados existentes durante sua instalação.

⚠️ Utilize apenas ISOs obtidas de fontes confiáveis.

⚠️ O autor não se responsabiliza por perda de dados decorrente do uso incorreto das ferramentas.

---

# Changelog

## v1.0

- Primeira versão pública
- Estrutura inicial do projeto
- Programas essenciais adicionados
- Drivers Intel e AMD
- Guia de utilização do Ventoy

---

# Autor

PedroGamesSlk

Projeto desenvolvido para facilitar a manutenção e recuperação de computadores.
