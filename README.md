# dtls

## client hello

```
0  0x00000000006c629d in github.com/pions/dtls.clientFlightHandler
   at /home/jinlei1/ksyun/src/github.com/pions/dtls/client_handlers.go:224
1  0x00000000006e8711 in github.com/pions/dtls.(*Conn).startHandshakeOutbound.func1
   at /home/jinlei1/ksyun/src/github.com/pions/dtls/conn.go:427
2  0x0000000000461821 in runtime.goexit
   at /home/jinlei1/os/go/src/runtime/asm_amd64.s:1337
   ```
