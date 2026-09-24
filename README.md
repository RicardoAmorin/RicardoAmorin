# Atualização do GitHub de Ricardo Amorin

Material preparado após leitura dos arquivos públicos em 23/09/2026. Nenhuma alteração foi publicada na conta. Os READMEs foram conferidos contra a estrutura consultada; o código dos projetos não foi executado.

## 1. Perfil

Em Edit profile, use:

- Nome: Ricardo Amorin
- Bio: Estudante de Ciência da Computação | Estagiário de TI | Automação com Python e Selenium | C#, SQL e desenvolvimento web
- Localização: Porto Velho, RO — Brasil
- Foto: uma foto sua nítida, com enquadramento simples.
- LinkedIn: copie o endereço correto diretamente do seu perfil. O link encontrado no HTML termina em `/w`; confirme o endereço antes de publicar.
- Website: adicione o endereço real do portfólio depois de confirmar que abre corretamente.

## 2. README do perfil

Crie um repositório PÚBLICO com o nome exato RicardoAmorin e coloque nele o arquivo RicardoAmorin/README.md deste pacote. Se esse repositório já existir, edite seu README em vez de criar outro. Esse arquivo deve ficar na raiz do repositório, sem uma subpasta adicional.

## 3. READMEs dos projetos

Cada pasta deste pacote corresponde a um repositório. Copie apenas o conteúdo correspondente para a raiz daquele repositório. Você pode editar o README pelo ícone de lápis, colar o novo conteúdo e usar Commit changes.

No banco de dados, o novo README deve ficar na raiz, mantendo o script onde está. O README antigo em projeto-bd-agregacao/README.md tem um diagrama que não corresponde exatamente às tabelas do SQL: ele apresenta EQUIPAMENTO, enquanto o script implementa alocacao_equipamento. Substitua o README antigo por um link `Veja a [documentação principal](../README.md).` para evitar duas versões conflitantes.

No laboratório SQL Injection, preserve o README existente, imagens e créditos. Acrescente apenas a seção do arquivo COMPLEMENTO-README.md ao final; esse arquivo é um trecho para colar, não um novo README completo.

## 4. Descrições e tópicos

Na página de cada repositório, use a engrenagem da seção About.

| Repositório | Description | Topics |
| --- | --- | --- |
| meu-portfolio-html | Portfólio pessoal desenvolvido com HTML e CSS para apresentar formação, conhecimentos e projetos. | html, css, portfolio |
| afya-poo-atv01 | Exercícios acadêmicos de orientação a objetos em C#: lâmpada, cofre, conta e RPG. | csharp, dotnet, oop, exercises |
| projeto-bd-agregacao | Modelagem relacional em PostgreSQL com autorrelacionamento, chaves estrangeiras e consultas com JOIN. | postgresql, sql, database, data-modeling |
| sql-injection-lab-study | Estudo documentado de SQL Injection em laboratório autorizado com Burp Suite e sqlmap. | cybersecurity, sql-injection, security-lab, burp-suite |

## 5. Organização do C#

Adicione o .gitignore incluído. Ele evita novos arquivos gerados, mas NÃO retira os que já foram enviados.

Para retirar apenas os artefatos gerados do versionamento, mantendo seus arquivos locais, abra o terminal na raiz desse repositório:

```bash
git rm -r --cached --ignore-unmatch -- Ex01_Lampada/bin Ex01_Lampada/obj Ex02_Cofre/bin Ex02_Cofre/obj Ex03_Conta/bin Ex03_Conta/obj Ex04_RPG/bin Ex04_RPG/obj
git add .gitignore README.md
git diff --cached --stat
```

Confira que a lista contém somente os arquivos gerados e a documentação pretendida. Depois:

```bash
git commit -m "Organiza documentação e remove artefatos de compilação"
git push
```

Os arquivos antigos ainda existirão no histórico, o que é normal. Não é necessário reescrever o histórico para essa organização.

## 6. Projetos fixados

Use Customize your pins. Para vagas em desenvolvimento, coloque primeiro o portfólio, depois o banco e os exercícios de C#. Mantenha o laboratório como complemento. Quando tiver uma automação demonstrativa completa, dê destaque a ela.

## 7. Automação para demonstrar sua experiência

Próximo projeto sugerido: triagem de chamados em uma aplicação local fictícia, com Python e Selenium.

Escopo inicial: ler chamados, procurar várias palavras-chave sem diferenciar maiúsculas e minúsculas, escolher o responsável e registrar o resultado. Use dados fictícios e uma página simulada. Documente como instalar dependências, iniciar a página e executar a automação. Registre um vídeo curto e explique as limitações.

Só apresente a automação como projeto público concluído quando código e demonstração estiverem disponíveis. Não publique código, dados ou telas internas da empresa sem autorização.

## 8. Verificação final

- Abrir o perfil e conferir a apresentação.
- Clicar em cada link e confirmar o destino.
- Executar os projetos conforme seus READMEs antes de dizer que estão testados.
- Conferir que as imagens existentes continuam aparecendo no laboratório.
- Confirmar o endereço do LinkedIn e do currículo no portfólio.
- Fazer commits conforme melhorias reais, sem criar atividade artificial.

Referência oficial do README de perfil: https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme
