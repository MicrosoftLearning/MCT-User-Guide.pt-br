# Guia do usuário do GitHub para MCTs

Os serviços de nuvem, como o Microsoft Azure, são atualizados com frequência, o que gera desafios para os Instrutores Certificados pela Microsoft (MCTs), pois eles ministram cursos e etapas de laboratório que não correspondem mais aos nossos serviços de nuvem. . Devido à frequência das alterações e ao fato de que pode não haver nenhuma notificação quando elas ocorrem, pode ser difícil para a equipe de desenvolvimento do curso identificar e ajustar rapidamente as alterações no laboratório.

Para resolver esses problemas, estamos usando o GitHub para publicar as etapas e os scripts de laboratório dos cursos que abrangem serviços de nuvem como o Azure. O uso do GitHub permite que os autores do curso e os MCTs mantenham o conteúdo do laboratório atualizado com as alterações do serviço de nuvem. O uso do GitHub permite que os MCTs forneçam comentários e sugestões para alterações no laboratório e, em seguida, os autores do curso podem atualizar prontamente as etapas e os scripts do laboratório.

Ao se preparar para ministrar esses cursos, você deve garantir que está usando as etapas e os scripts mais recentes do laboratório fazendo o download dos arquivos apropriados do GitHub.

Este guia do usuário é para MCTs que são novos no GitHub. Ele fornece etapas para conectar-se ao GitHub, fazer download e imprimir materiais do curso, atualizar os scripts que os alunos usam nos laboratórios e explicar como você pode ajudar a garantir que o conteúdo de um curso permaneça atualizado.

> **Observação**: O suporte do Microsoft Learning para acessar arquivos no GitHub e o suporte para navegação do GitHub são limitados apenas aos MCTs que ministram este curso.

O GitHub não deve ser usado para discutir o conteúdo técnico do curso ou como se preparar para o curso ou seus laboratórios. Ele serve especificamente para resolver alterações nos laboratórios.

 
> **Observação**: Para fazer comentários gerais sobre o curso e as demonstrações, ou sobre como se preparar para o curso, use os fóruns do MCT.

## Seções

- [Terminologia do GitHub](https://microsoftlearning.github.io/MCT-User-Guide/terminology/)

- [Receber notificações de atualização e colaborar em projetos](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/)

- Sugerir alterações ou enviar um problema para as instruções do laboratório

## Terminologia do GitHub

O GitHub apresenta uma terminologia que pode ser nova para você. A lista a seguir inclui os termos e conceitos usados em todo este documento. No entanto, para obter uma lista completa dos termos do GitHub, consulte o [Glossário do GitHub](https://docs.github.com/en/get-started/quickstart/github-glossary).

| Termo| Explicação |
| - | - |
| Git e GitHub| O Git é um programa de código aberto de rastreamento de alterações e o GitHub é um site/solução criado com base no Git. Há outros sites e soluções que usam o Git como back-end. Você usaria o GitHub principalmente para projetos de desenvolvimento de código aberto (público), e ele é gratuito para esses projetos. No entanto, se quiser usar o GitHub para projetos privados e que não sejam de código aberto, você deverá se inscrever em uma versão paga. |
| Repo ou Repositório| Cada projeto no GitHub está em um repositório, ou repo. Um repositório contém todos os arquivos de um projeto, inclusive a documentação, e dá suporte ao histórico de revisões. Um repositório pode ser público ou privado. Você pode ter uma cópia local do repositório no disco rígido do seu computador ou pode usar o repositório no GitHub. |
| Markdown| Formato de arquivo de texto que pode ser usado para criar a documentação. Ele é baseado em texto e muito simples de atualizar, o que o torna fácil de usar durante a colaboração. O GitHub então o renderiza como HTML. |
| Markdown otimizado do GitHub (GFM)| Existem muitas variações ou otimizações do formato de arquivo Markdown. A versão do GitHub, comumente chamada de GFM, é uma das variações mais comuns do Markdown. Para obter mais informações sobre o GFM e como você pode usar o formato Marcação para seus documentos GFM, consulte "Introdução à gravação e formatação no GitHub" em https://help.github.com/articles/getting-started-with-writing-and-formatting-on-github/. |
| Fork| Esta é uma cópia de outro repositório que reside em sua conta do GitHub, em comparação com uma ramificação, que reside no repositório original. Consulte a "Ramificação" logo abaixo. |
| Branch| Esta é uma cópia de um repositório que reside no mesmo repositório que o original. Você pode mesclar uma ramificação com o original. |
| Fetch| Esse é o processo de recuperação de uma cópia das alterações mais recentes de um repositório online. No entanto, uma buscar não mescla alterações. |
| Pull| Esse é o processo de obter as alterações mais recentes de um repositório online e mesclá-las com as alterações locais. |
| Mesclar| Este é o processo de buscar alterações de uma ramificação e aplicá-las a outro. Isso inclui recuperar as alterações de um repositório online e aplicá-las à versão local desse repositório. |
| Solicitação de pull| É um conjunto de alterações propostas para um repositório que um usuário envia, e os proprietários ou colaboradores de um repositório podem aceitar ou rejeitar a pull request. |
| Push| Este é o processo de enviar ou submeter suas alterações locais ao repositório online. |
| Colaborador| Este é um usuário do GitHub que tem permissões para adicionar, excluir ou alterar o conteúdo de um repositório. |

## Receber notificações de atualização, sugerir alterações e colaborar em projetos

Você pode configurar sua experiência no GitHub para receber notificações quando ocorrerem atualizações em um repositório do GitHub. Há várias maneiras de se inscrever para receber notificações, e muitas delas estão relacionadas às várias maneiras de colaborar em um projeto. Para receber notificações, você pode executar as seguintes ações.

| Ação| Descrição |
| - | - |
| [Inspeção dos repositórios](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/watching/)| Quando você monitora um repositório, o GitHub fará automaticamente a sua assinatura para receber notificações de quaisquer novas pull requests ou problemas criados nesse repositório específico. Observe automaticamente qualquer repositório criado por você ou para o qual você é um colaborador. |
| [Pull request](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Quando você cria uma pull request e propõe que os proprietários de um repositório aceitem uma alteração que você fez, você automaticamente se inscreve para receber notificações sobre a discussão relacionada à pull request. Para criar uma pull request, você deve primeiro criar uma ramificação. |
| [Comentários](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Quando você faz comentários sobre a pull request de outra pessoa, o GitHub fará automaticamente a sua assinatura no fórum referente a esse comentário, ou você pode assinar manualmente no fórum. |
| [Problemas](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Um problema é uma sugestão, pergunta ou solicitação relacionada a um repositório. Cada problema tem sua própria discussão, e você pode fazer a assinatura em problemas, ou o GitHub fará automaticamente a sua assinatura nos problemas que você criar. |
| [Menções](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/mention/)| Quando outro usuário menciona você em uma conversa, usando seu nome de usuário do GitHub ([@username](https://github.com/username)), o GitHub fará automaticamente a sua assinatura na discussão. |

> **Observação**: Você pode modificar como e quando recebe notificações e também pode cancelar a inscrição em qualquer uma ou em todas as discussões.

## Enviar problemas ou sugerir alterações nas instruções do laboratório

Se você tiver uma sugestão ou encontrar um erro em um laboratório, poderá enviar uma pull request e registrar um problema. Se você já conhece a correção para o erro, recomendamos que envie uma pull request; caso contrário, envie um problema.

| Ação| Descrição |
| - | - |
| [Pull request](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/pullrequest/)| Quando você cria uma pull request e propõe que os proprietários de um repositório aceitem uma alteração que você fez, você automaticamente se inscreve para receber notificações sobre a discussão relacionada à pull request. Para criar uma pull request, você deve primeiro criar uma ramificação. |
| [Comentários](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/comment/)| Quando você faz comentários sobre a pull request de outra pessoa, o GitHub fará automaticamente a sua assinatura no fórum referente a esse comentário, ou você pode assinar manualmente no fórum. |
| [Problemas](https://microsoftlearning.github.io/MCT-User-Guide/collaboration/issue/)| Um problema é uma sugestão, pergunta ou solicitação relacionada a um repositório. Cada problema tem sua própria discussão. Você pode assinar problemas, ou o GitHub fará automaticamente a sua assinatura nos problemas que você criar. |
