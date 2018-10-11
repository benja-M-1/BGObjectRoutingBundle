## Notable changes since the original 1.0.0 release

* The `bg_object_routing.adapter.symfony_21` service has been removed. If
  you were redefining this service to make the object router use another
  `adapter` implementation (and thus, another Symfony `Router`?), you
  must update your service definition. The recommended approach is to 
  make the `bg_object_routing.adapter` alias point to an 
  `\JMS\ObjectRouting\RouterInterface` implementation of your choice.



