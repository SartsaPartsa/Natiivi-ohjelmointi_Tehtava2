# Lomake-App

##📱 **Android — Login Form (Jetpack Compose)**  
**Tekijä:** Sara Vehviläinen  
**Oppilaitos:** Oulun ammattikorkeakoulu  
**Kurssi:** Natiivi-ohjelmointi  
**IN00CT07-3009**  
**Lukukausi:** Syksy 2025


## 🧩 Tehtävän kuvaus

Tämän tehtävän tavoitteena on toteuttaa yksinkertainen Android-sovellus, joka näyttää kirjautumislomakkeen. Sovellus on tehty Kotlinilla ja Jetpack Compose -käyttöliittymäkirjastolla.

Tehtävä toimii johdantona seuraaviin aiheisiin:
- Jetpack Composen perusrakenteet
- State-hallinta (`remember`, `mutableStateOf`)
- UI-komponentit kuten `OutlinedTextField`, `Button`, `Column` ja `Icon`.
- Syötteen tyyppien määrittely (`KeyboardType`).

## ✨ Toiminnallisuus

- Käyttäjä voi syöttää sähköpostiosoitteen ja salasanan.
- Sähköpostikenttä on määritetty `KeyboardType.Email`.
- Salasanakenttä piilottaa syötetyn tekstin (`PasswordVisualTransformation`) ja käyttää `KeyboardType.Password`.
- Sovelluksessa on "Submit"-painike.
- Käyttöliittymä on keskitetty ruudulle.

## 🛠️ Käytetyt teknologiat ja komponentit

- Kotlin
- Android Studio
- Jetpack Compose
- Composable-funktiot
- State-hallinta: `remember`, `mutableStateOf`
- Material 3 -komponentit: `Scaffold`, `OutlinedTextField`, `Button`, `Icon`, `Text`
- Resource-hallinta: ikoneille `Icons.Default.Email`, `Icons.Default.Lock`

## 🎯 Oppimistavoitteet

- Jetpack Composen perustaidot.
- State-muutosten käsittely Composessa.
- Erilaisten syötekenttien (`OutlinedTextField`) ja näppäimistötyyppien käyttö.
- Androidin resurssien hyödyntäminen (vektorikuvakkeet).
- Sovelluksen perusrakenne Android Studiossa.

## 📚 Oppimisresurssit

### Jetpack Compose
- https://developer.android.com/jetpack/compose – Virallinen Compose-dokumentaatio
- https://developer.android.com/reference/kotlin/androidx/compose/material3/OutlinedTextField – Tekstisyötteen käsittely
- https://developer.android.com/jetpack/compose/layouts/basics – Layout-komponentit
- https://developer.android.com/jetpack/compose/state – Tilanhallinta (remember, mutableStateOf)

### Android-dokumentaatio:
- https://developer.android.com/docs – Virallinen Android-dokumentaatio
- https://developer.android.com/studio/intro – Android Studion käyttö

### Kotlin:
- https://kotlinlang.org/docs/home.html – Kotlin-kielen virallinen dokumentaatio
