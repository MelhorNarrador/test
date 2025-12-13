# Manual de Utilizador — **Lane**

> **Lane** é uma aplicação móvel para descobrir, filtrar e criar eventos com base na localização (mapa).  
> O objetivo é simples: **ver o que está a acontecer perto de ti**, **encontrar eventos por categoria** e, se tiveres permissões, **criar/gerir os teus próprios eventos**.

---

## Índice

1. [Visão geral](#visão-geral)  
2. [Requisitos](#requisitos)  
3. [Criar conta](#criar-conta)  
4. [Iniciar sessão](#iniciar-sessão)  
5. [Navegação principal](#navegação-principal)  
6. [Explorar eventos no mapa](#explorar-eventos-no-mapa)  
7. [Filtrar por categorias](#filtrar-por-categorias)  
8. [Criar um evento](#criar-um-evento)  
9. [Perfil](#perfil)  
10. [Gerir eventos (Admin)](#gerir-eventos-admin)  
11. [Eventos a participar](#eventos-a-participar)  
12. [Rotas até ao evento](#rotas-até-ao-evento)  
13. [Boas práticas e erros comuns](#boas-práticas-e-erros-comuns)  
14. [Resolução de problemas](#resolução-de-problemas)  

---

## Visão geral

A Lane organiza eventos em **pontos no mapa**. Cada ponto representa um evento (ou conjunto de eventos) numa localização.  
Dentro da aplicação consegues:

- **Pesquisar/Explorar** eventos através do mapa e marcadores.
- **Filtrar** por categorias (ex.: Desporto, Música, Workshops, Social & Noite, etc.).
- **Criar eventos** (título, descrição, localização, categoria, data/hora, preço, limite de participantes e privacidade).
- **Gerir eventos** (editar/apagar) se fores administrador.
- **Ver eventos a participar** e sair desses eventos.
- **Abrir rotas** para navegar até ao local do evento.

---

## Requisitos

- Smartphone com ligação à internet.
- **Permissão de localização** recomendada (para resultados mais relevantes no mapa e rotas).
- Conta Lane (para participar/criar eventos e aceder ao Perfil).

---

## Criar conta

1. Na página de login, toca em **“Não tens uma conta? Regista-te”**.
2. Preenche os campos:
   - **Nome completo**
   - **Nome de utilizador**
   - **Email**
   - **Palavra-passe**
   - **Data de nascimento** (formato `YYYY-MM-DD`)
   - **Género** (seleção)
3. Toca em **“Criar Conta”** para concluir.

**Ecrã de referência:**  
![Criar Conta](LaneAppLogOn.jpg)

---

## Iniciar sessão

1. Abre a app Lane.
2. Introduz:
   - **Nome de utilizador ou email**
   - **Palavra-passe**
3. Toca em **“Iniciar Sessão”**.

**Ecrã de referência:**  
![Login](LaneAppLogIn.jpg)

---

## Navegação principal

A navegação principal é feita pela barra inferior:

- **Pesquisar**: abre o ecrã do mapa para explorar eventos.
- **Perfil**: abre o teu perfil, estatísticas e ações relacionadas com eventos/conta.

**Ecrã de referência (barra inferior):**  
![Mapa principal](LaneAppMainScreen.jpg)

---

## Explorar eventos no mapa

No ecrã **Pesquisar**, vês o mapa com vários marcadores coloridos:

- Cada marcador representa um evento (ou um ponto com eventos disponíveis).
- Podes fazer zoom e mover o mapa para explorar zonas diferentes.

Dicas rápidas:
- **Zoom in** para separar marcadores próximos e ver melhor as localizações.
- **Move o mapa** para procurar eventos noutras áreas.
- Se tiveres a localização ativa, os resultados ficam mais úteis.

**Ecrã de referência:**  
![Mapa principal](LaneAppMainScreen.jpg)

---

## Filtrar por categorias

Para filtrar os eventos, usa o botão de **filtros** (ícone no canto inferior esquerdo).

Categorias disponíveis (exemplos):
- Todos
- Desporto
- Música & Concertos
- Estudos & Workshops
- Networking & Carreira
- Social & Noite
- Gaming & eSports
- Arte & Cultura
- Voluntariado & Comunidade
- Tecnologia & Startups
- Saúde & Bem-estar

1. Abre o menu de filtros.
2. Seleciona uma categoria.
3. O mapa passa a mostrar eventos dessa categoria.

**Ecrã de referência:**  
![Filtros](LaneAppMainScreenFilters.jpg)

---

## Criar um evento

Para criar um evento, usa o botão **“+”** no canto inferior direito do ecrã do mapa.

Campos disponíveis na criação:
- **Capa** (imagem do evento)
- **Título**
- **Descrição**
- **Localização** (pesquisa e seleção)
- **Categoria**
- **Data**
- **Hora**
- **Preço (€)**
- **Participantes** (limite)
- **Privacidade** (ex.: Público)

Passos:
1. Toca em **“+”** no mapa.
2. (Opcional) Toca em **Adicionar Capa** para selecionar uma imagem.
3. Preenche os campos obrigatórios (recomendado: título, localização, data e hora).
4. Define preço, limite e privacidade conforme necessário.
5. Toca em **“Criar Evento”**.

**Ecrãs de referência:**  
![Criar evento (1)](LaneAppEventCreation1.jpg)  
![Criar evento (2)](LaneAppEventCreation2.jpg)

---

## Perfil

No ecrã **Perfil** consegues ver:

- Avatar e identificação do utilizador (ex.: username).
- **Estatísticas**, como:
  - **Eventos ativos**
  - **Eventos a participar**
- Botão para **Terminar sessão** (logout).

**Ecrã de referência:**  
![Perfil](LaneAppProfileScreen.jpg)

---

## Gerir eventos (Admin)

Se tiveres permissões de administração, o Perfil mostra uma lista de eventos ativos criados/geridos por ti, com ações:

- **Editar**: altera os dados do evento.
- **Apagar**: remove o evento.

> Atenção: apagar um evento deve ser uma ação deliberada. Se a app não pedir confirmação, considera adicionar um diálogo de confirmação no futuro.

**Ecrã de referência:**  
![Gestão de eventos](LaneAppProfileScreenEventManagement.jpg)

---

## Eventos a participar

Quando estás inscrito num evento, o Perfil pode mostrar a secção de participação:

- **Info**: abre informação/detalhes do evento.
- **Sair**: remove a tua participação.

**Ecrã de referência:**  
![Participação em eventos](LaneAppProfileScreenEventParticipation.jpg)

---

## Rotas até ao evento

A Lane pode encaminhar-te para navegação até ao local do evento (normalmente via app de mapas do telemóvel).  
O fluxo típico é:

1. Abrir detalhes do evento.
2. Selecionar **Rotas / Navegar**.
3. O telemóvel abre a navegação com o percurso sugerido.

**Ecrã de referência (exemplo de rota):**  
![Exemplo de rota](LaneAppRouteExample.jpg)

---

## Boas práticas e erros comuns

- **Data e hora**: confirma sempre antes de publicar (evita eventos “no passado”).
- **Localização**: escolhe um ponto exato (não “Lisboa” genérico se for num sítio específico).
- **Privacidade**:
  - **Público** → aparece para toda a gente.
  - (Se existir privado) → garante que só quem deve vê.
- **Participantes**: define um limite realista (evita overbooking).
- **Preço**: se o evento for gratuito, mantém **0€** para evitar confusões.

---

## Resolução de problemas

**Não aparecem eventos no mapa**
- Confirma a ligação à internet.
- Remove filtros (seleciona **Todos**).
- Faz zoom out e procura noutra zona.

**Não consigo criar conta**
- Confirma o formato da data: `YYYY-MM-DD`.
- Verifica se o email já está registado.
- Tenta uma palavra-passe mais forte.

**Não consigo iniciar sessão**
- Confirma se estás a usar o username/email correto.
- Verifica maiúsculas/minúsculas na palavra-passe.
- Se existir, usa recuperação de conta/word reset.

**Rotas não abrem**
- Confirma que tens uma app de mapas instalada (ex.: Google Maps).
- Dá permissão de localização à app.

---

### Anexo — Lista de imagens deste manual

- `LaneAppLogIn.jpg` — Login  
- `LaneAppLogOn.jpg` — Registo / Criar conta  
- `LaneAppMainScreen.jpg` — Mapa principal  
- `LaneAppMainScreenFilters.jpg` — Menu de filtros  
- `LaneAppEventCreation1.jpg` — Criar evento (com capa)  
- `LaneAppEventCreation2.jpg` — Criar evento (campos inferiores)  
- `LaneAppProfileScreen.jpg` — Perfil (estatísticas + logout)  
- `LaneAppProfileScreenEventManagement.jpg` — Perfil (gestão de eventos)  
- `LaneAppProfileScreenEventParticipation.jpg` — Perfil (participação em eventos)  
- `LaneAppRouteExample.jpg` — Exemplo de rota/navegação  

