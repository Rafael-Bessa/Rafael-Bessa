# Notas da versão profissional

## Por que os cards de métricas foram removidos

A versão anterior usava `github-readme-stats.vercel.app` para estatísticas e linguagens. Esses cards dependem de um serviço público externo e podem falhar temporariamente por limites da API ou indisponibilidade.

Além disso, o próprio projeto GitHub Readme Stats alerta que o card "Top Languages" não representa nível de habilidade; ele mede a quantidade de código detectada nos repositórios públicos não-forkados.

Para um perfil profissional voltado a recrutadores, esta versão privilegia:

- identidade clara;
- stack principal;
- projetos verificáveis;
- formação;
- portfólio e YouTube;
- links que continuam úteis mesmo se um serviço de terceiros cair.

## Se quiser estatísticas dinâmicas no futuro

A opção mais confiável é hospedar sua própria instância do GitHub Readme Stats (por exemplo na Vercel) com seu token GitHub e então apontar os cards para sua própria URL.
