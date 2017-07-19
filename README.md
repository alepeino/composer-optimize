#### Regarding https://stackoverflow.com/a/45180156/3208258

---

From `/project`:

```
$ composer dump-autoload
$ php index.php
```

> `PHP Fatal error:  Uncaught Error: Class 'ModuleA\baseObjects\configClass' not found in ...`

---

```
$ composer dump-autoload --optimize
$ php index.php
```

> `.../composer-optimize/ModuleA/baseObjects/configClass.inc`

---

https://getcomposer.org/doc/articles/autoloader-optimization.md
