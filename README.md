<h1 align="center">
<br>
Comunicação OPC-DA com Node-Red
</h1>

<p align="center">O projeto tem como objetivo documentar os testes de comunicação realizado entre um servidor OPC-DA e o Node-Red.</p>

<p align="center">
  <a href="https://www.apache.org/licenses/LICENSE-2.0">
    <img src="https://img.shields.io/badge/apache-2.0-blue" alt="License Apache">
  </a>
</p>
<hr />

## Desenvolvimento

O primeiro passo para iniciar os testes foi definir qual OPC-DA utilizar. Após análise chegamos em dois servidor:

1. KEPServer
	+ Utilizado a versão EnterpriseEX V6
	
O nosso [Node-red](https://nodered.org/) está na versão 2.1.4.

O node **OPC-DA** que utilizamos foi [node-red-contrib-opc-da](https://flows.nodered.org/node/node-red-contrib-opc-da).

Após configurado os servidores OPCs e instalado o node OPC, vamos às configurações:
