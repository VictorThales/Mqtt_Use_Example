<img alt="GoStack" src="https://lh6.googleusercontent.com/proxy/K5fmOf83OCmcXLL6A8C661JiY_kCgEehnEzR8zyhludeemsL9n4R3vq1Q2aQBN_Vvd1PucGHzvY21aQNl_mvkhHDVNTAeFlgTLxVWaAQ4_eX" />

# ABP Iot Aplicada

Trabalho desenvolvido pelos alunos Victor Thales Pereira de Limas e Gustavo Sebastião Scheffer, onde foi utilizado a IDE do arduíno para programar no ESP32 um projeto utilizando MQTT, o aplicativo MQTT Dash e o Cloud MQTT Broker dioty.co .

## Componentes 🛠
Componentes utilizados: 
- ESP 32
- Sensor de temperatura DHT11
- Led RGB
- Resistor 220 Ω
- Jumpers

### Configurando o arduíno:

![idearduino](https://media.discordapp.net/attachments/689821241023922194/786334688012009482/unknown.png)

### Acesse `Example Configuration` .

![port](https://user-images.githubusercontent.com/56330822/99081795-190acd00-25a2-11eb-8f07-d66c372a836d.PNG)

### Configure a Porta `Port`, caso queira, ou  pode deixar a padrão que está executando na porta 3333.

Retorne a tela anterior.

### Acesse `Example Connection Configuration` .

![Redeconfig](https://media.discordapp.net/attachments/689821241023922194/778959451876884520/unknown.png?width=845&height=475)

### Configure o Nome de sua rede `WiFi SSID`. 
### Configure A Senha da sua rede `WiFi Password`.
### Após os procedimentos. Salve as alteraçoes e saia do menuconfig..

### Build and Flash

Ainda na pasta do projeto, com seu console do SDK (ESP-IDF Command Prompt) 
Com tudo configurado conforme passado nos passos acima, execute a ferramenta de monitoramento para visualizar a saída serial utilizando o comando:

```
idf.py -p PORT flash monitor
```

### Após rodar o comando a seguinte tela deve aparecer:

![rodando](https://media.discordapp.net/attachments/689821241023922194/778960988601843732/unknown.png?width=845&height=475)

### Conectado!

#### Localize o `IP` que o servidor obteve e em sequência a `Porta` que definimos, pois será usado para estabelecer a conexão com o Cliente

### Para estabelecer a conexão cliente/servidor foi usado o Realterm.

### Com o RealTerm aberto vá até a Aba `Port`.

![realterm1](https://media.discordapp.net/attachments/689821241023922194/778961622202449920/unknown.png?width=845&height=475)

### Na Aba Port. Prencha o campo `Port` com `IP:PORT` obtidos anteriormente no terminal. 
Após isto Clique! em Open para fazer a conexão

### Conexão Cliente/Servidor estabelecida.

### Para testar o funcionamento pode enviar seus códigos ASCII ao servidor, como predefinidos antes, utilize `TEMP`, `UMID`, ou `DIST`.

### Exemplos dos comandos enviados.

![req](https://media.discordapp.net/attachments/689821241023922194/778955507419185162/TEMP.png?width=845&height=475)
![req](https://media.discordapp.net/attachments/689821241023922194/778955510145220618/umid.png?width=845&height=475)
![req](https://media.discordapp.net/attachments/689821241023922194/778955494454460416/dist.png?width=845&height=475)


### Montagem

![1605657509003](https://media.discordapp.net/attachments/689821241023922194/778964352933036042/image0.jpg?width=356&height=475)
![1605657508995](https://media.discordapp.net/attachments/689821241023922194/778964354690580480/image2.jpg?width=356&height=475)
