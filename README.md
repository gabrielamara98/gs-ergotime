<h1 align="center">ErgoTime 🪑</h1>

## 🔴 Problema

Com a crescente adoção do trabalho remoto e do uso prolongado de computadores, problemas ergonômicos tornaram-se cada vez mais comuns. Entre eles, destacam-se:

- Desconforto nas pernas  
- Compressão da coxa  
- Má circulação sanguínea  
- Postura inadequada mantida por longos períodos  

Grande parte dessas dores é causada por **mesas muito baixas** ou **posicionamento incorreto**, que reduzem o espaço entre a coxa do usuário e a parte inferior do tampo da mesa.  
Quando esse espaço é insuficiente, ocorre compressão — muitas vezes imperceptível — que afeta diretamente a circulação e a postura.

A falta de percepção do usuário e a ausência de dispositivos acessíveis para monitorar esse tipo de risco contribuem para o agravamento do problema.


## 🏁 Solução

O **ErgoTime** foi desenvolvido para atuar como um monitor ergonômico inteligente inspirado em diretrizes de bem-estar no ambiente de trabalho.

Ele utiliza:

- **ESP32**, responsável pelo processamento e comunicação  
- **HC-SR04**, sensor que mede a distância entre a coxa e a mesa (O idela seria o sensor ToF)  
- **LED único**, que indica se o dispositivo está ligado e operando corretamente  

A solução funciona da seguinte maneira:

1. O sensor mede continuamente a distância.  
2. As informações são enviadas via **MQTT** para análise externa ou monitoramento remoto.  
3. O dispositivo pode oferecer resultados via **endpoint HTTP**, permitindo integração com dashboards e aplicativos.  
4. Tudo roda em um hardware de baixo custo, acessível e fácil de replicar.  

O objetivo principal do ErgoTime é **conscientizar**, **promover ergonomia** e **prevenir problemas físicos** causados por má postura.


## ▶️ Instruções de uso e replicação  
*(a preencher)*

> **Espaço reservado para escrever os passos completos:**  
> – Como montar o circuito  
> – Como configurar bibliotecas  
> – Como rodar o firmware  
> – Como acessar MQTT/HTTP  
> – Como testar  
> – Como replicar o protótipo  


## 🖼️ Imagem do protótipo  
*(a inserir)*  
> Adicione aqui a imagem (ou imagens) do dispositivo, montagem e simulação.


## 🔗 Link para Wokwi  
*(a inserir)*  
> Adicionar o link da simulação Wokwi aqui.


## 🎥 Vídeo Explicativo  
*(a inserir)*  
> Colocar o link do vídeo final (YouTube).


## 📡 Explicação técnica — MQTT  
*(a preencher)*

> **Espaço reservado para detalhes técnicos, incluindo:**  
> – Tópico utilizado  
> – Formato da mensagem  
> – Exemplo de payload  
> – Frequência de envio  
> – QoS, broker, autenticação (se houver)


## 📂 Códigos-fonte comentados  
*(a preencher)*

> **Espaço para adicionar os arquivos:**  
> – `.ino`  
> – `.cpp`  
> – `.h`  
> – Scripts Python / HTML se usados  
> Com explicações sobre cada bloco de código.


## 🧰 Tecnologias utilizadas

- ESP32  
- Sensor HC-SR04  
- LED único indicador  
- MQTT  
- HTTP Server  
- Arduino IDE / PlatformIO  
- Wokwi  
- GitHub  


## 🧑‍💻 Equipe

<table>
  <tr>
    <th><span>Integrantes</span></th>
    <th><span>Tarefas</span></th>
  </tr>

  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/202196268?v=4" width="100px" alt="Camila Martins Profile Image"/>
      <p><a href="https://github.com/dev-camila">Camila Martins</a></p>
      <span><b>RM:561492</b></span>
    </td>
    <td>
      <ul>
        <li>README</li>
        <li>Design</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://avatars.githubusercontent.com/u/80047823?v=4" width="100px" alt="Gabriel Amara Profile Image"/>
      <p><a href="https://github.com/gabrielamara98">Gabriel Amara</a></p>
      <span><b>RM:561403</b></span>
    </td>
    <td>
      <ul>
        <li>Desenvolvimento completo do código</li>
        <li>Gravação e edição do vídeo explicativo</li>
      </ul>
    </td>
  </tr>
</table>
