# DoorDash

When a consumer places an order on DoorDash, they show the expected time of delivery. It is very important for DoorDash to get this right, as it has a big impact on consumer experience. In this exercise, I built a model to predict the estimated time taken for delivery.

Concretely, for a given delivery I predicted the total delivery duration in seconds, i.e., the time taken from
Start: the time consumer submits the order (created_at) to
End: when the order will be delivered to the consumer (actual_delivery_time)
