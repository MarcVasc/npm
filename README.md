1. Clone o repositório ou extraia o arquivo zip
2. Instale as dependências:

```bash
npm install
```

3. Inicie o servidor:

```bash
npm start
```

4. Acesse o sistema em seu navegador:

```
http://localhost:3001
```

## Configuração

O sistema pode ser configurado através de variáveis de ambiente ou editando o arquivo `config.js`. As principais configurações são:

- `PORT`: Porta em que o servidor será executado (padrão: 3001)
- `DATA_DIR`: Diretório para armazenamento de dados (padrão: './data')
- `LOG_LEVEL`: Nível de log (debug, info, warn, error) (padrão: 'info')

## Estrutura do Projeto

- `server-production.js`: Servidor principal otimizado para produção
- `config.js`: Configurações do sistema
- `public/`: Arquivos estáticos da interface do usuário
  - `index.html`: Página principal
  - `relatorios.html`: Página de relatórios
  - `js/`: Scripts JavaScript
  - `css/`: Estilos CSS
- `data/`: Armazenamento de dados (criado automaticamente)
- `logs/`: Logs do sistema (criado automaticamente)

## Funcionalidades

- Divisão de clientes entre vendedores
- Agendamento semanal de contatos
- Formulário completo de prospecção
- Sincronização em tempo real entre dispositivos
- Funcionamento offline com sincronização posterior
- Relatórios detalhados com filtros e gráficos
- Exportação para Excel com formatação avançada

## Licença
