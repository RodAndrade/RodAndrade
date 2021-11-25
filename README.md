```php
<?php

namespace RodAndrade;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Veggi',
                'position' => 'Full Stack Developer'         
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
            NodeJS::class,
            TypeScript::class,
            Aws::class,
            Asterisk::class,
        ];
    }
}
```
