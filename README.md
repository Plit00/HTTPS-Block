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

-------
what is SHA-1?

1.Algorithm<br>
* SHA-1
 * HashSize : 160
 * BlockSize : 512
 * limit length : 64
 * Operator : +, and, or, xor, protocol

---------

SHA-1 Algorithm example<br>
  * <code> SHA1("The quick brown fox jumps over the lazy dog")
= 2fd4e1c67a2d28fced849ee1bb76e7391b93eb12</code>

* <code>SHA1("") = da39a3ee5e6b4b0d3255bfef95601890afd80709</code>


---------------------

