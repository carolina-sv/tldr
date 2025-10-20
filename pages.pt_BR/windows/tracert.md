# tracert

> Rastreia a rota dos pacotes ate um destino.
>  Mais informações: <https://learn.microsoft.com/windows-server/administration/windows-commands/tracert>.

- Exibir o caminho ate um host:
 `tracert {{endereco_ou_ip}}`

- Definir o numero maximo de saltos (hops):
`tracert -h {{30}} {{endereco_ou_ip}}`

- Impedir a resolução de nomes DNS:
  `tracert -d {{endereco_ou_ip}}`
  
