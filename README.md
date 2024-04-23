# Tutorial-8
---
#### Nama: Athira Reika
#### NPM: 2206031422
#### Kelas: Adpro B
---
### Refleksi
<ol>
<li>How many data your publlsher program will send to the message broker in one run?</li>
<p> Answer: The publisher will send 5 data to the message broker in one run because it calls publish_event 5 times in <code>main.rs/main()</code>.
<li>The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?</li>
<p>Answer: This means that the publisher and subscriber are connected to the same AMQP instance with the same authentication details (username and password are both guest, just like subscriber).
</ol>

![alt text](image.png)