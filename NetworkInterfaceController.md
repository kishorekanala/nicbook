# Chapter One
## Journey of Data Over Network

### What Application sees wrt Data Flow

Applications such as email, browser prepare buffer with content to be sent to destination by opening a socket and sending the content over the socket at the sender side. At the receiving side, applications such as email, browser opens socket and receives the content over the scokets.


<figure style="text-align: center;">
  <img src="./ApplicationLevelViewOfDataFlow.png" alt="Application Level Data Flow">
  <figcaption>Figure 1: Application Level Data Flow</figcaption>
</figure>


TxApplication allocates memory for SendBuffer and fills it with the content that it intends to send to RxApplication. TxApplication opens a socket by specifying the address and port of RxApplication. It provides SendBuffer as input to TxSocket. Contents of SendBuffer are received by RxSocket. RxApplication receives the contents in ReceiveBuffer.


### Under the Hood



# Chapter Two

## Context of NIC



