# Routing


```php
Router::register("GET", "/", "index"); //view
Router::register("GET", "/", "index@method"); //controller -> IndexController::method()
Router::register("GET", "/", function () { }); //callback
Router::register("GET", "/detail/(:num)", function ($id) { return $id; }); //with params
```