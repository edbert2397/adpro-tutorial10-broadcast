## 2.1 Original code of broadcast chat
#### Server
![](server.png)
#### Client
![](client1.png)
![](client2.png)
![](client3.png)
<br>
To run, just run `cargo run --bin <file_name>`.

server akan menjadi listener dan menerima connection dari tiap client. DServer akan menerima dan memberikan message baru yang diberikan oleh client. Setiap client dapat membuat message dan menerima message dari client lain yang terkoneksi dan diproses oleh server.


## 2.2 Modifying the websocket port
![](client8080.png)
![](server8080.png)

Mengubah menjadi port 8080 pada file client.rs dan server.rs. Apliaksi akan berjalan dengan port yang sama. Protocol pada server.rs dan client.rs berbeda. Client.rs menggunakan websocket sedangkan server.rs menggunakana protocol.

