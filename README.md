# Software design


ITMO CT



### Lab 1


**Goals:**
* Get hands-on experience of using dynamic checks (assertions)


Implement [LRUcache](https://www.interviewcake.com/concept/java/lru-cache) based on hash map and linked list.
Need to check pre/post-conditions and invariont of the class, write tests.


**Implementations:**
* [Clojure](./lab-1)



### Lab 2


**Goals:**
* Get hands-on experience of implementation modul tests and mock-objects based tests



With using [twitter api](https://developer.twitter.com/en/docs/api-reference-index) write module
that calculate count of twtts with some hash-tag.

```kotlin

/**
 * @param tag    - hash-tag that should be checked
 * @param houres - count of houres to ctreate diagramm. From 1 to 24
 *
 * @return array of [houres] length with information of twitts count.
 **/
fun checkTag(tag: String, houres: Int): List<Int>

```


**Implementations:**



### Lab 3


**Goals:**
* Get hand-on experience of using refactoring technics


Downloads application from: https://github.com/akirakozov/software-design/tree/master/java/refactoring
It's a wep server that poduse next functionality:
* http://localhost:8081/get-products - get all products in the base
* http://localhost:8081/add-product?name=...&price=... - add new product
* http://localhost:8081/query?command=... - produce some action with data in the base


Need to refactor code:
* Ommit duplicate code
* Agregate working with data base in the separate layout
* Agregate creating http-responce to the separate layout


**Implementations:**



### Lab 4


**Goals:**
* Get hand-on experience of using pattern **MVC (Model-View-Controller)**


Write simple web application for working with to-do lists.

Fuctionality:
* Browse to-do lists and deals in them
* Add/delete to-do lists
* Add deals
* Mark deals as comlated


**Implementations:**
