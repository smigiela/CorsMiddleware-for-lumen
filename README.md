# Cors Middleware for LUMEN
Put this file into app/Http/Middleware folder and register this into bootstrap/app.php file:
```
$app->middleware([
    ...
     \App\Http\Middleware\CorsMiddleware::class
 ]);
 ```
