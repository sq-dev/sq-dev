### <img src="https://media3.giphy.com/media/cdZAGXI45pQ6Q/200w.webp?cid=ecf05e47bl9p22lqiw84me0ugiodtaksl8csls7m2f8toawc&rid=200w.webp&ct=s" width="50">  Hi I'm Asrorov Said
```php
<?php

namespace AsrorovSaid;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Alif Tech',
                'position' => 'Backend'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Python::class,
        ];
    }
}
```
