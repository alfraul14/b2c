# B2C DOCs 
## Custom Policy Hello World
- Declararemos los "ClaimSchema claims" que vamos a utilizar.
- En el "ClaimsProvider", declararemos un perfil técnico que invoque la llave de cifrado y su correspondiente desencriptado.
- A continuación, enviaremos otro "TP" necesario para cualquier "customPolicy".
- Crearemos un "userJourney" que contendrá "OrchestrationSteps", especificando qué debe ser llamado.
- Finalmente, en "RelyingParty", seleccionaremos el elemento del "userJourney" que se ejecutará, junto con lo que se devolverá en el token.