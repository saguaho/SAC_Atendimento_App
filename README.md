
 📲 SAC Atendimento App - Power Apps

Este repositório contém um modelo de aplicativo de tela desenvolvido com o **Microsoft Power Apps**, voltado para exibição de dados de atendimento ao cliente (SAC) a partir de um banco de dados **SQL Server local**.



 📌 Visão Geral

**SAC_Atendimento_App.msapp** é um app no-code criado para auxiliar empresas que utilizam sistemas locais de atendimento ao cliente com banco de dados SQL Server. Com esse app, é possível:

- Listar chamados de atendimento em tempo real;
- Filtrar por status ou prioridade;
- Exibir dados como cliente, data de abertura, resumo e status;
- Personalizar a interface com facilidade via Power Apps Studio.



 🛠️ Requisitos

Para utilizar o aplicativo, você precisará:

- Uma conta no **Microsoft Power Apps**;
- Instância do **Microsoft SQL Server** com tabela `Atendimentos` configurada;
- Instalar e configurar o **On-premises Data Gateway** (se o SQL estiver local);
- Acesso ao Power Apps Studio para importar e editar o app.



 🧩 Conexão Esperada

O app está preparado para usar uma fonte de dados chamada:

```powerapps
'[dbo].[Atendimentos]'
````

Certifique-se de que a tabela `Atendimentos` existe com as colunas mínimas como:

* `Id`
* `Cliente`
* `DataAbertura`
* `Status`
* `Resumo`

Você pode adaptar conforme sua estrutura real.



 ▶️ Como Usar

1. Faça o download do arquivo [`SAC_Atendimento_App.msapp`](./SAC_Atendimento_App.msapp);
2. Acesse [make.powerapps.com](https://make.powerapps.com);
3. Clique em **Apps** > **Importar pacote (canvas app)**;
4. Importe o `.msapp` e edite conforme necessário;
5. Conecte à sua base SQL Server usando um conector (via Gateway, se necessário);
6. Execute o app e comece a visualizar os chamados!



 📸 Capturas de Tela *(opcional)*

> *Adicione aqui prints da interface do app após a personalização.*



 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE). Sinta-se livre para usar, modificar e compartilhar.



 ✉️ Contato

Desenvolvido por **Herlon Sousa**
📧 Fale comigo no [LinkedIn](https://www.linkedin.com/in/herlonsousa)



 💡 Sugestões de Expansão

* Adicionar formulário para abrir novos chamados;
* Incluir filtros avançados por data, região ou responsável;
* Publicar o app no Teams para integração com atendimento interno.


```
