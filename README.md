# ProtocolExtension


**Protocol Extension:**
```
let array = ["Ahmet", "Alex", "Marcus"]
let set = Set(["Alli", "Harry", "James"])
let dictionary = ["Ahmet": 1, "Ali": 2, "Alex": 3]

extension Collection {
    func protocolExtensionFunction() {
        print("\(count)")
        
        for index in self {
            print(index)
        }
    }
}
array.protocolExtensionFunction()
set.protocolExtensionFunction()
dictionary.protocolExtensionFunction()
```


```
protocol ExtendedProtocol {
    func extendedFunction() -> [String]
}

extension ExtendedProtocol {
    func extendedFunction() -> [String] {
        return ["Ahmet"]
    }
}
```
