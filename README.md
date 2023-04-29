```kotlin
val 4nk1r = person {
    education = listOf(
        School(
            grade = 10,
            finished = false
        ),
        SelfEducation(fields = listOf(AndroidDev))
    )
    tastes {
        music {
            genres = listOf(Rock, Metal, Alternative, Electronic)
            people = listOf("Smash Into Pieces", "RADIO TAPOK", "Цифей")
        }
        series = listOf("Stranger Things", "Breaking Bad", "11.22.63")
    }

    occupation = Freelancer
    skills = listOf(
        AndroidDev(
            level = Junior, 
            experience = (1..2).years
        ),
        EnglishLanguage(level = average(A2, B1)),
        RussianLanguage(level = C2)
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
