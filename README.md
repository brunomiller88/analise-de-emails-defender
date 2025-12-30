# analise-de-emails-defender
Pilares a validar na análise de confiabilidade do fluxo de e-mails no Defender.
Análise de e-mails – Microsoft Defender

Além de analisar o IP de origem (numa página externa), domínio e endereço do remetente.

Existem 3 pilares dentro do Defender que validam a confiabilidade desde a origem até o destino final desse envio:
![Pilares de validação de e-mail no Defender](https://raw.githubusercontent.com/brunomiller88/analise-de-emails-defender/main/pilares%20a%20validar%20e-mail%20001.png)


SPF

Basicamente valida se o servidor tem permissão para enviar e-mail em nome do domínio.

DKIM

Valida se o conteúdo foi alterado no caminho e compara a chave pública.

DMARC

Valida quem tentou enviar, de onde veio e se passou ou falhou, está linkado a validação dos protocolos anteriores.
