```kotlin
class User(
    val nickname: String = "_LuK__",
    val site: String = "https://llukk.carrd.co/",
    var stars: Int = 6,
    var commits: Int = 1400,
    var pullRequests: Int = 1,
    var issues: Int = 1,
) :
    Person(
        name = "Kirill",
        birthDate = Date(1000, 11, 19),
        age = null,
    ) {
    init {
        getLogger().info("pog")
    }
}

```
