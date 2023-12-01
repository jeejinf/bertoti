# Tarefa de IHC (Interface Humano-Computador)
Atividade realizada no 3º Semestre de Desenvolvimento de Software Multiplataforma (FATEC Jessen Vidal - SJC), onde é necessário exemplificar e descrever as 10 heurísticas de Nielsen para o design de interface.

## Heurísticas de Nielsen
As heurísticas de Nielsen são princípios básicos para a avaliação da usabilidade de interfaces. Aqui estão elas:

1. **Visibilidade do status do sistema**: O sistema deve sempre manter os usuários informados sobre o que está acontecendo, fornecendo feedback apropriado e em tempo real.
2. **Correspondência entre o sistema e o mundo real**: O sistema deve falar a linguagem dos usuários, com palavras, frases e conceitos familiares ao usuário, e não termos orientados ao sistema.
3. **Controle e liberdade do usuário**: Os usuários muitas vezes escolhem funções do sistema por engano e precisam de uma "saída de emergência" claramente marcada para sair do estado indesejado sem ter que passar por um diálogo estendido.
4. **Consistência e padrões**: Os usuários não devem ter que se perguntar se diferentes palavras, situações ou ações significam a mesma coisa.
5. **Prevenção de erros**: Melhor do que boas mensagens de erro é um design cuidadoso que evita que um problema ocorra em primeiro lugar.
6. **Reconhecimento em vez de memorização**: Os objetos, ações e opções visíveis devem minimizar a memória do usuário.
7. **Flexibilidade e eficiência de uso**: Aceleradores - invisíveis para o usuário novato - podem frequentemente acelerar a interação para o usuário experiente.
8. **Estética e design minimalista**: Os diálogos não devem conter informações irrelevantes ou raramente necessárias.
9. **Ajude os usuários a reconhecerem, diagnosticarem e recuperarem-se de erros**: As mensagens de erro devem ser expressas em linguagem simples (sem códigos), indicar precisamente o problema e sugerir construtivamente uma solução.
10. **Ajuda e documentação**: Mesmo que seja melhor se o sistema puder ser usado sem documentação, pode ser necessário fornecer ajuda e documentação.

## Exemplos de Sites
Aqui estão alguns exemplos de sites que implementam corretamente as heurísticas de Nielsen:

| Regra | Site | Imagem | Descrição |
|:----:|:----:|:------:|:---------:|
| #1  | <a href="https://www.youtube.com/">YouTube<a/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra1.png" alt="Regra 1" width="50%"> | A barra do YouTube informa qual seu progresso no vídeo, a quantidade de vídeo já baixada, e a quantidade que ainda resta. |
| #2  | <p>MS Paint<p/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra2.png" alt="Regra 2"> | Ilusões ao mundo real, como o disquete (salvar), a lupa (zoom) e o sino (notificações) |
| #3  | <a href="https://gmail.com/">Gmail<a/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra3.png" alt="Regra 3" width="80%"> | Possibilidade de desfazer o ato de excluir um e-mail, facilitando a experiência do usuário. |
| #4  | <a href="https://unitvbrasil.pro/">UniTV Brasil<a/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra4.png" alt="Regra 4"> | A navbar de um site é uma maneira padronizada e consistente de mostrar o conteúdo de um site. |
| #5  | <a href="https://twitter.com/">Twitter<a/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra5.png" alt="Regra 5" width="50%"> | O limite de caracteres do nome do usuário permite a prevenção de um erro. |
| #6  | <a href="https://notepad-plus-plus.org/">Notepad++<a/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra6.png" alt="Regra 6" width="80%"> | O aviso sutil no "*", que o arquivo ainda não foi salvo, o disquete ficando vermelho pelo mesmo motivo, e a disposição do ícone de salvar acima do texto, nos lembra de salvar o documento. |
| #7  | <a href="https://www.atlassian.com/br/software/jira">Jira<a/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra7.png" alt="Regra 7"> | O design prático do Jira é muito autoexplicativo, facilitando a experiencia do usuário. |
| #8  | <a href="https://open.spotify.com/">Spotify<a/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra8.png" alt="Regra 8" width="70%"> | O minimalismo no Spotify pode ser percebido pelo uso de apenas ícones, na parte esquerda, enquanto a parte principal é bem simples, com as informações úteis explicitas. |
| #9  | <a href="https://gmail.com/">Gmail (Cadastro)<a/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra9.png" alt="Regra 9" width="50%"> | Ao colocar uma letra na hora do cadastro do Gmail logo é retornado um erro avisando que a data inserida não é válida. |
| #10 | <a href="https://bard.google.com/">Bard<a/> | <img src="https://github.com/jeejinf/bertoti/raw/main/IHC/imagens/regra10.png" alt="Regra 10" width="50%"> | Bem na tela principal do Bard, é possível ver um ícone de interrogação, onde há um FAQ (Perguntas frequentes) e uma outra aba para auxiliar o usuário com documentações mais específicas. |

-----

## Bot do Telegram (Encontrado na pasta IHC/bot_telegram)
# Configurar o .env (exemplo no arquivo .env.example) com as suas credenciais (do BotFather e OpenAI) você terá um bot integrado com o ChatGPT 4, que pode responder suas perguntas no Telegram.