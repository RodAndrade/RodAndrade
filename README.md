```php
<?php

namespace RodAndrade;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'OnCar',
                'position' => 'Senior Full Stack Developer'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Vuejs::class,
            React::class,
            ReactNative::class,
            Aws::class,
            Asterisk::class,
        ];
    }
}
```
