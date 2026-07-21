




🧪 Estrutura do Projeto

.
├── 📁 /pages                       # Contém os arquivos Page Object Model (POM) para mapeamento e interação com as páginas da aplicação
│   └── 🧪 SignUpPage.ts            # Abstração da página de cadastro de usuário
│   └── 🧪 LoginPage.ts             # Abstração da página de login
│   └── 🧪 TransferPage.ts          # Abstração da página de transferência
│   └── 🧪 BankStatementPage.ts     # Abstração da página de extrato
│ 
├── 📁 /tests                       # Contém as suítes de testes e seus respectivos casos
│   └── 🧪 signup.spec.ts           # Testes automatizados do cenário de cadastro de usuário
│   └── 🧪 login.spec.ts            # Testes automatizados do cenário de login na plataforma
│   └── 🧪 transfer.spec.ts         # Testes automatizados do cenário de transferência de valores
│   └── 🧪 bankstatement.spec.ts    # Testes automatizados do cenário de extrato da conta
│
├── 📁 /fixtures                    # Define dados fixos reutilizáveis, como criação de contas com ou sem saldo para os testes 
│   └── 🧪 accounts.ts              # Fixture responsável pela criação das contas e captura das informações de número da conta e dígito
│   └── 🧪 dataTest.ts              # Fixture com o papel de centralizar o uso das variáveis de ambiente dentro dos testes, deixando o código mais limpo, reutilizável e fácil de manter
│
├── 📁 /utils                       # Funções auxiliares que oferecem suporte à lógica dos testes
│   └── 🧪 dateUtils.ts             # Formatação de data no padrão PT-BR para uso nos testes
│   └── 🧪 formatUtils.ts           # Formatação de string em número e vice-versa para uso em ações nos testes
│
├── 📄 README.md                    # Documentação inicial do projeto
├── 📄 package.json                 # Gerenciador de dependências e scripts do projeto
├── 📄 package-lock.json            # Controle de versão exata das dependências instaladas
├── 📄 playwright.config.ts         # Configuração global dos testes no Playwright


