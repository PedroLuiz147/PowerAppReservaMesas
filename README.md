# 📌 Aplicativo de Reservas e Check-in/Check-out

Este aplicativo foi desenvolvido no **PowerApps** para gerenciar reservas de estações de trabalho, registrando **usuários, reservas e check-in/check-out**. Para o armazenamento dos dados, foram utilizadas **listas do SharePoint**.

## 🛠️ Tecnologias Utilizadas
- **PowerApps**: Desenvolvimento da interface e lógica do aplicativo.
- **SharePoint Lists**: Armazenamento de dados sobre usuários, reservas e check-in/check-out.

## 📂 Estrutura das Listas do SharePoint
O aplicativo utiliza as seguintes listas:

1. **Usuários**: Contém informações sobre os usuários cadastrados.
   - **Colunas**:
     - `Pessoas` (Coluna do tipo pessoas que traz informações dos usuário)
     - `PessoasEmail` (Apenas e-mail do usuário)
     - `Departamento`* (Coluna opcional para identificar o departamento do usuário)  
2. **Reservas**: Registra as reservas de estações de trabalho.
   - **Colunas**:
     - `ID` (Identificação da Reserva)
     - `Estacao` (Identificador da Estação)
     - `Data Reserva` (Data e hora da reserva)
     - `Responsável` (E-mail do usuário responsável pela reserva)
     - `Departamento`* (Coluna opcional para identificar o departamento do usuário)  
3. **CheckInCheckOut**: Controla os check-ins e check-outs das reservas.
   - **Colunas**:
     - `Título` (Nome da estação de trabalho)
     - `ID_Reserva` (Identificador da reserva)
     - `ResponsavelEmail` (E-mail do usuário responsável pela reserva)
     - `Check-In` (Data e hora do check-in)
     - `Check-Out` (Data e hora do check-out)
     - `Status` (Indica se a reserva está confirmada ou finalizada) 

## ⚙️ Funcionalidades do Aplicativo
- 📅 **Reserva de estações de trabalho**
- ✅ **Check-in com atualização de horário a cada minuto**
- 🚪 **Check-out com validação para evitar registros duplicados**
- 📊 **Consulta de registros salvos no SharePoint**

## 🚀 Como Utilizar
1. **Acesse o PowerApps** e abra o aplicativo.
2. **Realize login** com sua conta da organização.
3. **Faça uma reserva** de estação de trabalho.
4. **Realize o check-in** e o check-out conforme necessário.
5. **Os dados serão armazenados automaticamente** no SharePoint.

## 📝 Melhorias Futuras
- 🔔 Notificações automáticas de reserva via **Power Automate**
- 📆 Integração com calendário **Outlook**
- 📊 Relatórios dinâmicos no **Power BI**
- 🛠️ Ferramenta de Suporte para **HelpDesk** e reporte de problemas com o Aplicativo

## 🤝 Contribuição
Caso tenha sugestões ou melhorias, sinta-se à vontade para abrir um **Pull Request** ou relatar **Issues** no repositório!

📧 **Contato:** https://www.linkedin.com/in/pedro-luiz-santos/

