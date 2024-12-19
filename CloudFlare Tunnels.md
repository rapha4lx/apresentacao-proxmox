# Como funciona?
- Esse software cria um túnel seguro baseado em HTTPS entre o seu servidor e a Cloudflare.
- Como a conexão é iniciada de dentro da sua rede, ela é considerado "saida" e, portanto, não depende de configurações de redirecionamento de portas.
- Conexão persistente. Quando o túnel é iniciado, ele mantém uma conexão ativa e aberta com a Cloudflare.
# Vantagens
- O túnel utiliza criptografia e autenticação. Garantindo que apenas a Cloundflare possa se comunicar com o seu servidor pelo túnel.
- Não expõe portas diretamente.
# [[Instalação]]