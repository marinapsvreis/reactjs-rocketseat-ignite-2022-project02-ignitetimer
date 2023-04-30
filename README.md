Nesse módulo nos aprofundamos no react, aprendendo como usar o useEffect, o conceito de API Context utilizando o createContext e useContext e o padrão de reducers utilizando useReducer. Desenvolvemos um aplicativo para controlar ciclos de concentração/pomodoro, e foi necessário se aprofundar em logica com javascript para padronizar o comportamento do contador. Controlamos alguns comportamentos em cascata com base em mudanças de estados usando o useEffect. Evitamos o drop drilling que é o excesso de props sendo passadas para componentes com o uso de contexto. Tudo isso desenvolvido já em typescript com suas devidas tipagens implementadas. E o reducer entrou para padronizar e isolar comportamentos de estados mais complexos em arquivos separados.

![Ignite Timer - Tela Countdown](https://i.imgur.com/bJhUaua.png)
![Ignite Timer - Tela Countdown com ciclo ativo](https://i.imgur.com/fYDLHzy.png)
![Ignite Timer - Tela Historico de ciclos](https://imgur.com/yC5K1sn.png)

Utilizamos também bibliotecas como:
- Styled components (evitando criar componentes quando o que muda é apenas a estética)
- Phosphor react (biblioteca de icones)
- Date-fns (manipulação e calculo com datas)
- React router dom (configurando rotas da aplicação)
- React hook form (validando e monitoriando comportamentos em formulários)
- Zod (validanto e fazendo inferencia de tipos com typescript)
- Immer (evitando estrutura de código mais confusas por conta do conceito de imutabilidade no react)

OBS: A informação dos ciclos estão sendo salvar em localstorage o que te permite atualizar a página e não perder os dados dos ciclos passados no histórico e o ciclo atuando que está rodando.

Comando para rodar o projeto:
```npm run dev```