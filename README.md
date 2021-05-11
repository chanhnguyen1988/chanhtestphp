# Test

Problem #1:

```
<?php
$array = ["Input.txt" => "Randy", "Code.py" => "Stan", "Output.txt" => "Randy"];
function groupByOwners($array) {
    $result = [];
    foreach ($array as $key => $item) {
        $result[$item][] = $key;
    }
    return $result;
}
$arr = groupByOwners($array);
print_r($arr);
```

Problem #2:
```
<?php
function unique_names($array1, $array2) {
    return array_unique(array_merge($array1,$array2));
}
$arr = unique_names(['Ava', 'Emma', 'Olivia'], ['Olivia', 'Sophia', 'Emma']);
print_r($arr);
```
Problem #3:
```
<?php
class TextInput {
    public $text;
    public funtion add($text) {
        $this->text.= $text;
    }
}
```
