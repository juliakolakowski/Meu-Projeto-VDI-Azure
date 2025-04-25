# Meu-Projeto-VDI-Azure

Projeto de criação e configuração de uma máquina virtual (VM) no Microsoft Azure.

---

## 📌 Descrição

Este repositório documenta a criação e configuração de uma máquina virtual (VM) no Microsoft Azure, com foco na instalação do papel de servidor web (IIS) e na utilização do ambiente Windows Server.

---

## 🖥️ Ambiente da VM

A imagem abaixo mostra o ambiente inicial após a criação da máquina virtual e acesso via Remote Desktop. A VM está rodando Windows Server e exibe o **Server Manager**, onde é possível gerenciar funções, recursos e configurações do sistema.

![Server Manager VM](./caminho/para/sua/primeira-imagem.jpeg)

---

## ⚠️ Tentativa de Instalação do IIS e Limitação

Durante a tentativa de instalação do papel de Servidor Web (IIS), ocorreu uma falha na tarefa de pré-implantação:

![Erro na Instalação do IIS](./caminho/para/sua/segunda-imagem.jpeg)

> **Erro:** `The WS-Management service cannot process the request. The service is configured to not accept any remote shell requests.`  
> Isso indica que a máquina virtual está configurada para não aceitar solicitações remotas via PowerShell, o que impediu a finalização da instalação.

🔎 **Observação**: Por conta da limitação de memória (RAM) da VM, não foi possível aumentar a capacidade ou modificar configurações adicionais, pois isso implicaria em custo extra no ambiente Azure.

---

## 📄 Conclusão

Apesar da falha na instalação do IIS, o processo de criação e acesso remoto à VM foi realizado com sucesso. O projeto demonstra a familiarização com o portal Azure, criação de recursos, configuração de acesso remoto e gerenciamento inicial de servidor.





