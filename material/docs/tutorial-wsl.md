# Como Instalar e Configurar o WSL no Windows

O **WSL (Windows Subsystem for Linux)** permite rodar um ambiente Linux dentro do Windows sem precisar de máquina virtual ou dual boot. Se você nunca mexeu com Linux antes, este tutorial vai te guiar desde a instalação até a configuração do **Ubuntu** no WSL.

---

## Passo 1: Ativar o WSL no Windows  

1️⃣ **Abra o PowerShell como Administrador**  
   - Pressione **Win + S** e digite **PowerShell**  
   - Clique com o botão direito no **Windows PowerShell** e selecione **Executar como Administrador**  

2️⃣ **Ative o WSL com o comando:**  
   ```powershell
   wsl --install
   ```  
   Esse comando instala automaticamente o WSL e define o **Ubuntu** como a distribuição padrão.  

3️⃣ **Aguarde a instalação e reinicie o computador**  
   - O Windows precisará reiniciar para concluir a ativação do WSL.  

## Passo 2: Instalar o Ubuntu no WSL  

1️⃣ **Após reiniciar, abra o PowerShell novamente e verifique se o WSL está ativo:**  
   ```powershell
   wsl --list --verbose
   ```  
   Se não houver distribuições instaladas, você pode instalar manualmente com:  
   ```powershell
   wsl --install -d Ubuntu
   ```  

2️⃣ **Aguarde a instalação e abra o Ubuntu:**  
   - Após a instalação, o **Ubuntu será iniciado automaticamente**.  
   - Se não abrir, procure por **"Ubuntu"** no Menu Iniciar e clique nele.  

3️⃣ **Configurar usuário e senha:**  
   - Assim que o Ubuntu iniciar pela primeira vez, você verá uma tela pedindo um nome de usuário. Escolha um nome (exemplo: `seunome`) e pressione **Enter**.  
   - Agora, o sistema pedirá uma senha. **Digite sua senha e pressione Enter** (não se preocupe se não aparecer nada enquanto digita, é normal).  
   - Digite novamente a senha para confirmar.  

📌 **Exemplo:**  
```
Enter new UNIX username: seunome
New password:
Retype new password:
```
✅ **Agora o seu ambiente Ubuntu está pronto para uso!**  

---

## Passo 3: Atualizar e Testar o Sistema  

Agora que o Ubuntu está instalado, o primeiro passo é **atualizar os pacques**. No terminal do Ubuntu, digite:  
```bash
sudo apt update && sudo apt upgrade -y
```  
Esse comando **baixa e instala todas as atualizações mais recentes** do sistema.  

**Verifique a versão do Ubuntu instalada:**  
```bash
lsb_release -a
```  

**Teste se o Linux está rodando corretamente no WSL:**  
```bash
wsl --list --verbose
```
Se aparecer algo como **"Ubuntu Running"**, significa que está tudo funcionando. 🚀  

---

## Passo 4: Abrindo o Ubuntu e Alternando Entre Windows e Linux  

Agora que tudo está instalado, você pode abrir o Ubuntu sempre que precisar de um terminal Linux.  

📌 **Para abrir o Ubuntu no Windows:**  
- **Método 1:** Pesquise por **"Ubuntu"** no Menu Iniciar e clique no app.  
- **Método 2:** No **Prompt de Comando (cmd)** ou **PowerShell**, digite:  
  ```powershell
  wsl
  ```  

📌 **Para alternar entre o Ubuntu e o Windows no terminal:**  
- Para acessar arquivos do Windows no WSL:  
  ```bash
  cd /mnt/c/Users/SeuNome
  ```  
- Para acessar arquivos do Ubuntu no Windows, digite no Explorador:  
  ```
  \\wsl$\Ubuntu
  ```  

📌 **Para desativar ou reiniciar o WSL:**  
```powershell
wsl --shutdown
```
---

## Agora você tem um ambiente Linux rodando no Windows  
