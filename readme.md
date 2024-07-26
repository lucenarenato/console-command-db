# Ideias de consoles commands e confs de banco

```php
 if (config('database.default') === 'pgsql') {
            $hashtag = Hashtag::where('name', 'ilike', $tag)->firstOrFail();
        } else {
            $hashtag = Hashtag::whereName($tag)->firstOrFail();
        }
```
