O uso de `delegatecall` é particularmente arriscado e tem sido usado como um vetor de ataque em vários hacks históricos. Com ele, seu contrato está praticamente dizendo "aqui, -outro contrato- ou -outra biblioteca-, faça o que quiser com meu estado". Os delegados têm acesso completo ao estado do seu contrato. A função `delegatecall` é um recurso poderoso, mas perigoso, e deve ser usado com extremo cuidado.

Consulte o artigo [The Parity Wallet Hack Explained](https://blog.openzeppelin.com/on-the-parity-wallet-multisig-hack-405a8c12e8f7) para obter uma explicação precisa de como essa ideia foi usada para roubar 30 milhões de dólares.