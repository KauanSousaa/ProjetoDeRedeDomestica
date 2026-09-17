# ProjetoDeRedeDomestica
Projeto focado na configuração e nos conceitos básicos de uma rede sem fio doméstica, demonstrando o funcionamento dos componentes de rede.
## 📌 Descrição do Projeto

Este projeto consiste na simulação e configuração de uma rede residencial completa no Cisco Packet Tracer, interligando dispositivos via cabo coaxial, cabeamento de rede Ethernet e conexão sem fio (Wi-Fi), garantindo a comunicação da rede local e o acesso à Internet.

---

## 🛠️ O Que Foi Feito (Passo a Passo)

### 1. Conexão dos Dispositivos
* **Infraestrutura Coaxial:** Conexão do cabo coaxial da tomada ao *Cable Splitter* (divisor), alimentando o *Cable Modem* e a TV residencial.
* **Cabeamento de Rede:**
  * Interligação da porta de Internet do *Home Wireless Router* ao *Cable Modem* usando cabo direto (straight-through).
  * Conexão dos computadores (*Office PC* e *Bedroom PC*) às portas LAN do roteador sem fio.

### 2. Configuração do Roteador Sem Fio (Wireless Router)
* **Acesso à Interface Web (GUI):** Acesso à página de administração do roteador a partir do *Office PC* via navegador web.
* **Configurações Básicas de Rede & DHCP:** Limitação do número máximo de IPs concedidos pelo servidor DHCP para **10 usuários**.
* **Segurança de Administração:** Alteração da senha padrão de acesso à GUI do roteador.
* **Configuração da Rede Wi-Fi:**
  * Alteração do nome da rede (SSID) de 2.4 GHz para **MyHome**.
  * Aplicação do padrão de segurança **WPA2 Personal** com senha de acesso personalizada.

### 3. Configuração de Endereçamento e Teste de Conectividade
* **Conexão Sem Fio:** Conexão do *Laptop* à rede Wi-Fi **MyHome** informando a senha WPA2 definida.
* **Validação de IP:** Confirmação do recebimento automático de IP via DHCP no *Bedroom PC* e demais hosts.
* **Teste Final de Navegação:** Teste de conectividade com a Internet acessando o domínio `skillsforall.srv` através do navegador dos computadores e do laptop.

---

## 📸 Topologia Lógica da Rede

<img width="1865" height="1010" alt="Captura de tela de 2026-09-17 18-13-34" src="https://github.com/user-attachments/assets/90d5e522-6710-4370-8980-6881718419b9" />
