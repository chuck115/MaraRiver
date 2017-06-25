## Eloquent 查询条件


	

### Like

Model::where('column', 'LIKE', '%value%')->get();

[reference](https://stackoverflow.com/questions/13386774/using-eloquent-orm-in-laravel-to-perform-search-of-database-using-like)

### 动态Where


* How do I say WHERE (a=1 OR b=1) AND (c=1 OR d=1)

```
$query = User::query();

if ($this == $that) {
  $query = $query->where('this', 'that');
}

if ($this == $another_thing) {
  $query = $query->where('this', 'another_thing');
}

if ($this == $yet_another_thing) {
  $query = $query->orderBy('this');
}

$results = $query->get();

```


```
Model::where(function ($query) {
    $query->where('a', '=', 1)
          ->orWhere('b', '=', 1);
})->where(function ($query) {
    $query->where('c', '=', 1)
          ->orWhere('d', '=', 1);
});
```

[query scope](http://laravel.com/docs/eloquent#query-scopes)


