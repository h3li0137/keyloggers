# Projeto: Keyloggers em Python

Este repositório contém dois keyloggers desenvolvidos em Python com diferentes abordagens para captura e armazenamento de dados.

## Keylogger com Envio por E-mail

Este script registra as teclas pressionadas e envia os dados capturados para um e-mail especificado.

### Funcionalidades
- Captura de teclas usando `pynput`
- Reconhecimento de teclas especiais (espaço, enter, backspace)
- Envio automático por e-mail usando `smtplib` e `email.mime`
- Agendamento recorrente com `threading.Timer`

### Requisitos
- Python 3.x
- Bibliotecas:
  - `pynput`
  - `smtplib`
  - `email`

## Keylogger Local (Arquivo TXT)

Este script registra as teclas pressionadas e salva os dados localmente em um arquivo `log.txt`.

### Funcionalidades
- Captura de teclas usando `pynput`
- Ignora teclas modificadoras como Shift, Ctrl, Alt, etc.
- Reconhecimento de teclas especiais (espaço, enter, esc)
- Armazenamento em arquivo `.txt` com codificação UTF-8

### Requisitos
- Python 3.x
- Biblioteca:
  - `pynput`

## Instruções de Instalação

1. Clone o repositório:
```bash
git clone https://github.com/h3li0137/keyloggers
cd seu-repositorio
no própio code coloque um email e uma senha com verificação de duas etapas
```

2. Instale as dependências:
```bash
pip install pynput
 
```

## Aviso Legal

Este projeto é destinado exclusivamente para fins educacionais. O uso de keyloggers pode ser ilegal ou antiético dependendo do contexto. Não utilize este software sem o consentimento explícito do usuário alvo.

## Organização
- `keylogger_email.py`: Script com envio de dados por e-mail
- `keylogger_local.py`: Script com armazenamento local em `log.txt`

## Contato
Para dúvidas ou sugestões, entre em contato pelo GitHub.
