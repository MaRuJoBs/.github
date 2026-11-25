# MaruJob

**Projeto Integrador — Instituto Federal Catarinense, Campus Araquari**

O MaruJob é uma plataforma de conexão entre freelancers de Tecnologia da Informação e empresas que buscam profissionais para seus projetos.

## Acesse a plataforma

[**Acessar MaruJob**](https://front-marujob-virid.vercel.app/)

## Avaliação do projeto

A plataforma possui dois perfis: freelancer e empresa. As credenciais das contas demonstrativas são fornecidas diretamente ao professor no README de entrega, para evitar a exposição pública de senhas.

## Funcionalidades

- Cadastro e autenticação de freelancers e empresas.
- Divulgação e busca de oportunidades de trabalho em TI.
- Filtros de oportunidades, favoritos e candidaturas.
- Perfis profissionais e empresariais.
- Comunicação entre usuários e gerenciamento de oportunidades.

## Tecnologias

| Frontend | Backend | Infraestrutura |
| --- | --- | --- |
| Vue 3, JavaScript, Vite | Python, Django, Django REST Framework, PDM, JWT | Vercel, GitHub |

## Repositórios

| Repositório | Descrição |
| --- | --- |
| [Frontend](https://github.com/MaRuJoBs/Front_marujob) | Interface e integração com a API |
| [Backend](https://github.com/MaRuJoBs/Back_Marujob) | API, autenticação e regras de negócio |

## Execução local

### Frontend

```bash
git clone https://github.com/MaRuJoBs/Front_marujob.git
cd Front_marujob
npm install
npm run dev
```

### Backend

```bash
git clone https://github.com/MaRuJoBs/Back_Marujob.git
cd Back_Marujob
pdm install
cp .env.exemplo .env
pdm run migrate
pdm run dev
```

Configure as variáveis de ambiente conforme o ambiente local e os respectivos repositórios antes da execução.

## Equipe

- Breno Otávio Rohregger
- João Pedro Bachmann
- Ricardo Baron Rodrigues
- Mateus Oliveira Ramos

---

Projeto acadêmico desenvolvido no Instituto Federal Catarinense — Campus Araquari.
