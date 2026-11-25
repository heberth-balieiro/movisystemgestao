# MoviSystem Gestão

Sistema web de gestão para consultorias, da prospecção e elaboração de contratos ao planejamento de serviços e acompanhamento de entregas.

## Tecnologias

| Camada | Tecnologias |
| --- | --- |
| Frontend | Next.js, React e TypeScript |
| Backend | Delphi com Horse e API REST versionada em `/api/v1` |
| Banco de dados | MySQL |
| Hospedagem prevista | Servidor Linux na Contabo |

## Ordem de desenvolvimento

1. Montar o frontend com login, dashboard e navegação. Desenvolver **Acesso** (Usuários, Perfis e Permissões), **Cadastros**, **Configurações** e, por último, **Operações**. Usar estados vazios sem dados mockados e documentar as dependências da API de cada tela.
2. Implementar o banco e a API em Delphi com Horse, integrar as telas e validar os fluxos com dados reais de teste.

## Escopo funcional

- **Cadastros** de pessoas, funcionários, produtos e serviços, setores, funções, categorias, contas bancárias, participantes e instrutores. Cada tela de cadastro terá ajuda contextual.
- **Operações** de prospecção, contratos, aditivos, planejamento por serviço, marketing e recrutamento.
- **Configurações** de modelos de contrato, dados e parâmetros da empresa, WhatsApp, e-mail e integrações.
- **Acesso e acompanhamento** com usuários, perfis, permissões, relatórios e auditoria.
- **Portais** para clientes acompanharem seus contratos e para participantes consultarem os próprios certificados, conforme o serviço contratado.

## Arquitetura e documentação

- Organizar o frontend por módulo e responsabilidade, com componentes reutilizáveis, tipos e serviços de API.
- Separar rotas, serviços e repositórios no backend. Usar SQL parametrizado e migrações versionadas.
- Aplicar isolamento de dados por empresa e verificar na API as permissões e os vínculos de acesso. Proteger dados pessoais e armazenar senhas com hash seguro.
- Manter a estrutura de pastas, os passos de execução, os contratos da API e as regras de negócio documentados junto com o código.

O repositório está na fase de inicialização. Os comandos de instalação e execução serão documentados quando os projetos forem inicializados.
