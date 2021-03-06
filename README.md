# language-spec
## Array

|                 | add front        | add back    | remove front   | remove back        |
| --------------- | ---------------- | ----------- | -------------- | ------------------ |
| Ruby Array      | unshift/prepend  | push/append | shift          | pop                |
| Python List     | insert(0, var)   | append      | pop(0)         | pop                |
| PHP Array       | array\_unshift   | array\_push | array\_shift   | array\_pop         |
| JavaScript      | unshift          | push        | shift          | pop                |
| JavaScript Node | prepend          | appendChild | N/A            | N/A                |
| jQuery          | prepend          | append      | first().remove | last().remove      |
| C++ deque       | push_front       | push_back   | pop_front      | pop_back           |
| Java            |                  |             |                |                    |
| C#              |                  |             |                |                    |
| Go              |                  |             |                |                    |
| Rust            |                  |             |                |                    |
| Swift Array     | insert(e, at: 0) | append      | removeFirst    | popLast/removeLast |
| Kotlin          |                  |             |                |                    |
| Lisp            |                  |             |                |                    |

## Range
Range
* Ruby  
1...5: [1, 5)  
1..5: [1, 5]  

* Swift  
1..<5: [1, 5)  
1...5: [1, 5]  

* Rust  
1..5: [1, 5)  
1..=5: [1, 5]  
