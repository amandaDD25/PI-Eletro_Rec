<div align="center">

# PI Eletro REC
#### A digital system for scheduling recyclable material collection

</div>

## Summary

The Eletro-Troca Project was developed to support the [Coopemape Catadores Maria da Penha](https://www.instagram.com/coopemape/?g=5) initiative, which focuses on recycling electronic waste. 
The main goal is to create a digital system (website or app) to organize donations, register donors and collectors, and improve transparency.

Using modern technologies and agile methods, the project helps the Cooperative control materials more efficiently and generate reports automatically.
The system promotes sustainability, social inclusion, and technological innovation, showing how technology can transform communities.

## Teams Members

- Cid José Espíndola Filho - Scrum Master
- Maria Amanda Ferreira de Almeida - Design
- Guilherme Freitas Pinheiros - FrontEnd
- Matheus de Araújo Martins - Designer UI/UX
- Carlos William Macedo da Silva - BackEnd

## Technologies Used 

### Programming Languages: 

- Python
- JavaScript
- SQL 

### Design Tools: 

- Figma
- Canva
- Miro

## How to use 

1. Install the app from a virtual store ([Google Play](https://play.google.com/store/apps), [App Store](https://www.apple.com/br/app-store/))
2. Create your account
3. Start using
    - Schedule material collection
    - Check recycling stats
  # PI Eletro REC Fluxograma.
  
 ![Imagem do WhatsApp de 2025-11-07 à(s) 11 00 19_4fa45f0f](https://github.com/user-attachments/assets/09ed84a2-1af1-41a5-a87b-a7fd5639c2d3)
    
 # PI Eletro REC Coding em Python.

    # -- coding: utf-8 --
"""
Sistema Eletro REC
Autor: [Seu Nome]
Descrição: Sistema simples de login e menu principal para agendamento de coletas de resíduos eletrônicos.
"""

def linha():
    """Exibe uma linha separadora padrão."""
    print("-" * 50)


def menu_principal():
    """Exibe o menu principal do sistema Eletro REC."""
    while True:
        linha()
        print("MENU PRINCIPAL - Eletro REC")
        print("1 Agendar Coleta")
        print("2Ver Coletas Agendadas")
        print("3 Perfil (em desenvolvimento)")
        print("4 Configurações (em desenvolvimento)")
        print("5 Sair")
        linha()

        opcao = input("Escolha uma opção: ").strip()

        if opcao == "1":
            agendar_coleta()
        elif opcao == "2":
            listar_coletas()
        elif opcao == "3":
            print(" A seção de perfil ainda está em desenvolvimento.")
        elif opcao == "4":
            print("As configurações estarão disponíveis em breve.")
        elif opcao == "5":
            print("Saindo do sistema. Até logo!")
            break
        else:
            print(" Opção inválida. Tente novamente.")


def agendar_coleta():
    """Função simulada de agendamento de coleta."""
    linha()
    print("Agendamento de Coleta")
    print("Função em desenvolvimento...")
    linha()


def listar_coletas():
    """Função simulada para listar coletas agendadas."""
    linha()
    print("Lista de Coletas Agendadas")
    print("Nenhuma coleta cadastrada no momento.")
    linha()


def login():
    """Realiza o login simples no sistema."""
    linha()
    print(" LOGIN - Eletro REC")
    usuario = input("Usuário: ").strip()
    senha = input("Senha: ").strip()

    # Login fictício para demonstração
    if usuario == "admin" and senha == "123":
        print(f"Login bem-sucedido! Bem-vindo(a), {usuario}.")
        menu_principal()
    else:
        print("Usuário ou senha incorretos. Tente novamente.")


if _name_ == "_main_":
    print("Bem-vindo ao Sistema Eletro REC")
   login()
   user = "tereza"
password ="0987k1m"

acess_user = input("qual e user?")
acess_pass = input("qual a senha?")

def login():
  if acess_user == user and acess_pass == passaword:
    print("login feito com sucesso")

