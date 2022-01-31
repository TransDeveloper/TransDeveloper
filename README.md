```php
<?php
namespace Edda\Van\Appenzeller;
class Me
{
    protected $name         = "Edda";
    protected $lazy         = false;
    protected $loc          = "Ilfov, Romania";
    protected $age          = 22;

    public function __construct()
    {
        $this->lazy = true;
    }

    public function getTinderProfile(): String{
        return $this->name . ", " . $this->age . ", " . $this->loc;
    }

    public function is2b2tplayer(): Bool{
        return true;
    }

    public function getName(){
        return $this->name;
    }

    private function girlCock(): Bool{
        return true;
    }
}
```

Note, i don't use github alot.
