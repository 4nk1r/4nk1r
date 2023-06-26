```kotlin
val 4nk1r = person {
    occupation = Freelancer
    skills = listOf(
        AndroidDev(
            level = Junior, 
            experience = (2..3).years
        ),
        EnglishLanguage(level = B1),
        RussianLanguage(level = C1)
    )
    petProjects = listOf(
        Project(
            name = "NetSchool",
            description = "Yet another app for NetSchool website",
            link = "https://github.com/4nk1r/netschool"
        ),
        Project(
            name = "HDRezka",
            description = "Yet another app for HDRezka website",
            link = "https://t.me/apphdr"
        )
    )
    links {
        telegram = "@fournkoner"
    }
}
```
