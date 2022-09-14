# nlw-esports-server
Back-end em NodeJS da aplicação "Find your DUO". Curso: NLW eSports da Rockerseat.

## Entidades

### Game

- id
- title
- bannerUrl

### Ad
- id
- gameId
- name
- yearsPlaying
- discord
- weekDays
- hourStart
- hourEnd
- useVoiceChannel
- createdAt

## Casos de uso

- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por game
- Buscar discord pelo ID do anúncio
