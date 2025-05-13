📦 Sistema de Estoque — Documentação
🧩 Descrição
Sistema web de controle de estoque, prático e completo, com:

Tela de login para usuários autorizados,

Cadastro, edição, exclusão e busca de produtos,

Controle de quantidade e metros por item,

Confirmação ao excluir itens,

Estilização moderna e responsiva.

🚪 Funcionalidades
🔐 Login
Usuários cadastrados diretamente no sistema:

Usuário: corte / Senha: 1234

Usuário: loja / Senha: 4567

Login salvo localmente (localStorage).

Redirecionamento automático para o painel de estoque após login.

📋 Cadastro de Produtos
Para cada produto é possível registrar:

Nome do produto,

Quantidade (em unidades),

Medida (em metros).

Cadastro através de formulário dinâmico e intuitivo.

🖊️ Edição de Produtos
Permite editar produtos cadastrados:

Nome, quantidade e metros podem ser alterados.

Atualização imediata da lista após edição.

❌ Remoção com Confirmação
Exclusão protegida: o sistema solicita confirmação antes de apagar qualquer item.

Evita perdas acidentais de dados.

🔎 Busca e Filtro
Campo de pesquisa para localizar produtos rapidamente pelo nome.

Filtro dinâmico que atualiza a lista de produtos conforme o texto digitado.

Melhora a organização em estoques maiores.

🛒 Listagem de Estoque
Tabela organizada exibindo todos os produtos cadastrados.

Design limpo e responsivo, ideal para diferentes tamanhos de tela.

🏗️ Estrutura de Pastas
bash
Copiar
Editar
/estoque/
│
├── index.html        # Página principal do sistema de estoque
├── login.html        # Tela de login de usuários
├── style.css         # Arquivo de estilos gerais
├── login.js          # Script de autenticação de usuários
├── app.js            # Script principal de controle de estoque
└── README.md         # (Este arquivo)
⚙️ Tecnologias Utilizadas
HTML5 — Estrutura do site

CSS3 — Estilo e responsividade

JavaScript (ES6) — Lógica de funcionamento

LocalStorage — Armazenamento local de dados e sessão

🎨 Estilo Visual
Interface amigável e responsiva.

Formulários com inputs modernos.

Botões de ação com feedback visual (hover e cores diferenciadas).

Tabela estilizada com sombras e bordas arredondadas.

🛠️ Como Usar
Acesse login.html no navegador.

Faça login com um dos usuários cadastrados.

Na tela de estoque:

Adicione novos produtos preenchendo nome, quantidade e metros,

Utilize o campo de busca para localizar produtos rapidamente,

Edite informações de produtos existentes,

Exclua produtos após confirmação.

A tabela de estoque será atualizada automaticamente a cada ação.

✨ Melhorias Futuras (opcional)
Integração com banco de dados real para persistência completa dos dados.

Implementação de relatórios de estoque.

Adicionar filtros avançados (por quantidade mínima, por metros, etc).

Criar sistema de usuários e permissões (ex: apenas administradores podem excluir).

📋 Conclusão
Sistema de estoque ideal para pequenos negócios, lojas e operações internas, com:

Controle de produtos por quantidade e metros,

Edição e remoção segura,

Busca e filtro rápido,

Sistema leve, intuitivo e eficiente.

Pronto para ser utilizado ou expandido conforme a necessidade!

✅ Sistema de Estoque completo e funcional!