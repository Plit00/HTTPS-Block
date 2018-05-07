# HTTPS-Block
what is http/https?

HTTP | HTTPS
---- | ----
client <--> sever(request/ response)protocol | SSL /TLS protocol/session data encryption
Port 80 / TDP&UDP | Port 433 / TCP&IP
x | 1.1.1.1 block & All IP
-------------------------
SSL Correspondence courses?

 * HandShake
 * Client(Never server's certificate)<br>
 * Sever(Already loaded with certificate and private key)<br>

1.Client Hello<br>
2.Sever Hello(including certificate)<br>
 -Now i have everything to encrypt the data needed for our symmetric key<br>
3.Key info(encrypted with sever's public key)<br>
 -Decrypt key info using private Key<br>


         "Calculate symmetric" Key"
4.Finished message(encrypted with symmetric key)<br>
-Calculate symmetric Key <br>
5.Finished message(encrypted with symmetric key)
