# laravel9_clear_cache_of_route_view_config_event_commands
## 1:Application Cache Clear in Laravel 9
```Dockerfile
php artisan cache:clear
```
## 2:Application Cache Clear in Laravel 9
```Dockerfile
php artisan route:clear
```
## 3:Application Cache Clear in Laravel 9
```Dockerfile
php artisan view:clear
```
## 4:Application Cache Clear in Laravel 9
```Dockerfile
php artisan config:clear
```
## 5:Application Cache Clear in Laravel 9
```Dockerfile
php artisan event:clear
```
## 6:Application Cache Clear in Laravel 9
```Dockerfile
php artisan optimize:clear
```
## 7:Application Cache Clear in Laravel 9
- Thay vì sử dụng lệnh thì bạn có thể sử dụng router như bên dưới
```Dockerfile
Route::get('/clear-cache-all', function() {
    Artisan::call('cache:clear');
  
    dd("Cache Clear All");
});
```
