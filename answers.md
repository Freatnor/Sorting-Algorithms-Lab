##Practice##

###Bubble Sort###
```
func bubblesort( var a as array )
    bool isSorted
    for i from 1 to N
        isSorted is true
        for j from 0 to N - 1
           if a[j] > a[j + 1]
              swap a[j] and a[j + 1]
              isSorted is false
           if isSorted is true
              end func
end func
```





###Insert Sort###
```
func insertionSort( var a as array )
    for i from 1 to N
        for j from i to 1
            if a[j] < a[j-1]
                swap a[j] and a[j-1]
            else
                break
end func
```
