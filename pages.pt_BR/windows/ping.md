# ping

> Testa a conectividade com outro dispositivo de rede.
> Mais informações: <https://learn.microsoft.com/windows-server/administration/windows-commands/ping>.

- Enviar 4 pacotes para um host:
  `ping {{endereco_ou_ip}}`

- Enviar numero personalizado de pacotes:
  `ping -n {{10}} {{endereco_ou_ip}}`

- Fazer ping continuo ate ser interrompido:
  `ping -t {{endereco_ou_ip}}`

- Fazer ping sem resolver nomes DNS:
  `ping -n {{endereco_IP}}`
