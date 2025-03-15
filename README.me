# Proxecto de Xogo en Rede

Este proxecto está deseñado para xestionar a conexión en rede e o control dun cubo de xogador nun xogo en 3D usando Unity. A continuación, descríbense os scripts e compoñentes que se usan para manexar as conexións e a interacción co xogador.

## Métodos e Variables

### `ConnectionManager.cs`

O script `ConnectionManager.cs` é o responsable de xestionar as conexións entre xogadores e servidores. Este script permite conectar, desconectar e supervisar o estado da conexión de rede durante o xogo.

- **Variables principais**:
  - `serverIP`: A dirección IP do servidor co que se establecerá a conexión.
  - `port`: O porto no que se conectará o cliente para establecer a comunicación.
  - `isConnected`: Un valor booleano que indica se o xogador está conectado ou non ao servidor.

- **Métodos principais**:
  - `ConnectToServer()`: Inicia a conexión co servidor, utilizando a IP e o porto especificados.
  - `DisconnectFromServer()`: Desconecta ao xogador do servidor actual.
  - `OnConnectionStatusChanged()`: Manteña actualizado o estado da conexión.

### `PlayerCubeController.cs`

O script `PlayerCubeController.cs` é o encargado de controlar as accións do cubo do xogador dentro do xogo.

- **Variables principais**:
  - `moveSpeed`: A velocidade coa que o cubo se move polo escenario.
  - `jumpForce`: A forza que se aplica cando o cubo salta.
  - `rotationSpeed`: A velocidade coa que o cubo rota.

- **Métodos principais**:
  - `MovePlayer()`: Xestiona o movemento do cubo en función das entradas do xogador (teclas de dirección ou analóxicas).
  - `Jump()`: Permite ao cubo saltar cando se presiona a tecla correspondente.
  - `RotatePlayer()`: Xestiona a rotación do cubo para que se dirixa cara á entrada do xogador.

## Compoñentes de `NetworkManager`

O GameObject `NetworkManager` é o núcleo para a xestión da rede en Unity. A continuación, descríbense os compoñentes que se atopan neste obxecto:

### **Network Manager**

O compoñente `Network Manager` é responsable de establecer e xestionar a conexión entre os xogadores e o servidor. Este compoñente permite que múltiples xogadores se conecten á mesma instancia do xogo en liña e xestiona a sincronización dos xogadores.

- Función: Xestiona a conexión en rede, permitíndolle aos xogadores unirse ou crear salas de xogo.
- Métodos clave: 
  - `StartHost()`: Inicia o servidor e establece a conexión como anfitrión.
  - `StartClient()`: Conéctase ao servidor como cliente.
  - `StopHost()`: Detén a conexión do anfitrión e todos os clientes conectados.

### **Unity Transport**

O compoñente `Unity Transport` proporciona o protocolo de rede para a comunicación entre os xogadores e o servidor. Utiliza a infraestrutura de baixo nivel para establecer comunicacións TCP/UDP e manexa a transmisión de datos entre clientes.

- Función: Garante que os datos de xogo viaxen entre os clientes e o servidor de forma eficiente e sen interrupcións.
- Métodos clave:
  - `Connect()`: Establece unha conexión co servidor.
  - `SendData()`: Envía datos entre os clientes e o servidor.
  - `ReceiveData()`: Recibe datos de outros xogadores ou do servidor.

### **Connection Manager**

O compoñente `Connection Manager` xestiona o ciclo de vida das conexións de rede, incluíndo a reconexión, a desconexión e a supervisión do estado da conexión. Este compoñente tamén permite xestionar as sesións de xogadores e asegurar que as conexións se mantéñan estables.

- Función: Manexa as conexións de rede, garantindo que os xogadores estean sempre conectados e sen problemas de latencia ou desconexións.

## Compoñentes de `PlayerCube`

O prefab `PlayerCube` é o obxecto que representa ao xogador no xogo. A continuación, explícanse os compoñentes asociados a este obxecto:

### **Network Object**

O compoñente `Network Object` é esencial para sincronizar o estado do xogador entre os diferentes clientes na rede. Este compoñente asegura que as accións realizadas polo xogador, como mover ou xirar, se transmitan correctamente aos demais xogadores.

- Función: Sincroniza o estado do cubo do xogador entre todos os clientes.
- Métodos clave:
  - `OnNetworkSpawn()`: Invocado cando o obxecto se instancia na rede.
  - `OnNetworkDespawn()`: Invocado cando o obxecto é destruído na rede.

### **Player Cube Controller**

O compoñente `Player Cube Controller` controla as accións do cubo do xogador, como movemento e rotación, e sincroniza estas accións con outros xogadores na rede.

- Función: Garante que os movementos e interaccións do xogador se realicen de forma correcta e se sincronicen entre os distintos clientes da rede.
