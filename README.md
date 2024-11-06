<img src="http://javaops.ru/static/img/logo/javaops_30.png" width="223"/>

<h2>Курс: Docker. Микросервисы. Kafka.<br>
Реактивный стек. Spring Cloud (<a href="https://javaops.ru/view/cloudjava">CloudJava</a>)</h2>

-----------------------------------------------------------------
<h3>Kafka Integration Part II. Dispatcher Service</h3>
<h4>Dispatcher Service вычитывает сообщение <code>AvroOrderPlacedEvent</code> из топика <code>v1.public.orders_outbox</code>, обрабатывает заказ и отправляет <code>OrderDispatchedEvent</code> в топик <code>v1.orders_dispatch</code>.
</h4>