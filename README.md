# ☁️ Tipos de Serviços em Nuvem: IaaS, PaaS e SaaS

## 📝 Descrição

Nesta etapa do curso de introdução ao **Microsoft Azure e computação em nuvem**, aprendemos sobre os três principais modelos de serviço em nuvem: **IaaS**, **PaaS** e **SaaS**. Cada um deles oferece diferentes níveis de controle, gerenciamento e flexibilidade para usuários e organizações.

---

## 🔍 O que aprendemos

### 🧱 IaaS (Infrastructure as a Service)

> "Infraestrutura como Serviço"

- Fornece **recursos de infraestrutura básicos** sob demanda, como máquinas virtuais, redes, armazenamento e servidores.
- O usuário é responsável por instalar e gerenciar o sistema operacional, aplicações e dados.
- É o modelo ideal para **maior controle e personalização**.

---

### ⚙️ PaaS (Platform as a Service)

> "Plataforma como Serviço"

- Oferece uma **plataforma gerenciada** para desenvolvimento e implantação de aplicações, sem precisar gerenciar a infraestrutura subjacente.
- Ideal para desenvolvedores que querem **focar no código** e na lógica de negócio.

---

### 💼 SaaS (Software as a Service)

> "Software como Serviço"

- Fornece **aplicações prontas para uso** que rodam na nuvem.
- O provedor gerencia tudo: infraestrutura, plataforma e software.
- Ideal para usuários finais que **precisam apenas utilizar a aplicação**, sem se preocupar com manutenção.

---

## 🧠 Reflexão

Esse módulo ajudou a compreender **os níveis de abstração e responsabilidade** em cada modelo de serviço. Entender essas diferenças é essencial para escolher o modelo mais adequado às necessidades de um projeto ou empresa, considerando fatores como custo, controle, escalabilidade e agilidade.

---

## 📌 Conclusão

- **IaaS**: Controle total sobre a infraestrutura.
- **PaaS**: Agilidade no desenvolvimento sem se preocupar com a base.
- **SaaS**: Uso simples e direto de aplicações.

Esse conhecimento é fundamental para **tomar decisões estratégicas em projetos de computação em nuvem** e aproveitar ao máximo os recursos que o Azure oferece.

---

# 🗄️ Criação de Instância de Banco de Dados na Azure

## 📚 Descrição

Nesta etapa do curso, realizamos a criação e configuração de uma **instância de banco de dados** no Microsoft Azure. O objetivo foi entender como provisionar recursos de banco de dados na nuvem e conhecer as opções de configuração oferecidas pela plataforma.

---

## 🚀 Etapas Realizadas

1. **Acesso ao Portal Azure**  
   Entramos no [portal oficial do Azure](https://portal.azure.com) com nossa conta de estudante.

2. **Criação de um novo recurso**  
   Selecionamos a opção `Criar um recurso` e buscamos por **Banco de Dados SQL**.

3. **Configuração do banco**  
   - **Nome do servidor lógico** criado.
   - **Nome da instância** do banco definida.
   - Escolha do **plano de desempenho** (modelo baseado em DTU ou vCore).
   - Seleção da **localização/região** mais próxima para melhor desempenho.

4. **Configuração de autenticação**  
   - Criamos um login e senha de administrador.
   - Optamos pelo método de autenticação SQL padrão.

5. **Regras de firewall e rede**  
   - Permitimos o acesso ao banco para o nosso IP atual.
   - Habilitamos conexões ao servidor para testes via ferramentas externas.

6. **Finalização e implantação**  
   Após a revisão, clicamos em `Criar`. A instância foi provisionada em poucos minutos.

---

## 🧪 Teste de Conexão

Com o banco de dados criado, realizamos testes de conexão utilizando:
- **Azure Data Studio**
- **SQL Server Management Studio (SSMS)**  
 
Fornecendo o nome do servidor, usuário e senha criados.

---

## 📌 Conclusão

A criação de um banco de dados no Azure foi **simples, intuitiva e eficiente**. A plataforma oferece opções flexíveis de desempenho e segurança, ideais tanto para ambientes de desenvolvimento quanto de produção.

> Esta experiência reforça a praticidade e a escalabilidade do uso de **serviços de banco de dados como PaaS** na nuvem, eliminando preocupações com infraestrutura física e manutenção.


