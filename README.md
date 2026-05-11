# Tutorial Modul 9 - Software Architectures

```
Nama : Nisrina Alya Nabilah
NPM : 2406425924
Kelas : AdvProg B
```

## Question Commit 2
**a. **How much data your publisher program will send to the message broker in one
run?****

Publisher akan mengirim 5 event/message dalam satu kali program dijalankan, karena terdapat 5 pemanggilan publish_event.

**b. The url of: `amqp://guest:guest@localhost:5672` is the same as in the subscriber
program, what does it mean**

Artinya publisher dan subscriber terhubung ke RabbitMQ yang sama, yaitu RabbitMQ yang berjalan di komputer lokal pada port 5672. Karena menggunakan username dan password yang sama, keduanya bisa berkomunikasi melalui message broker yang sama.