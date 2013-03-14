Sublime Text snippets
=====================

My PHP Sublime Text 2 snippets

## Setter and getter generator, PSR-2 coding standard ##

### setget-cs ###

``` php
/**
 * Gets the camelName
 */
public function getCamelName()
{
    return $this->camelName;
}

/**
 * Sets the camelName
 */
public function setCamelName($camelName)
{
    $this->camelName = $camelName;
}
```

## Setter and getter generator, compact version ##

### setget ###

``` php
public function getCamelName() { return $this->camelName; }
public function setCamelName($camelName) { $this->camelName = $camelName; }
```

## Manual breakpoint, var_dump and die ##

### var_dump_die ###

``` php
var_dump(var);
die(__METHOD__.' ('.__FILE__.' at '.__LINE__.')');
```
