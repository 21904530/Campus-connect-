 Campus-connect-
Campus Connect - Mobile App (Kotlin)
Topic 3 - Introduction to Mobile App Development | DUT

Campus Connect is an educational platform - Verified past papers, study notes, module circles, and AI study tools in one place.

Group Members
| Name | Student No | Role |
|------|------------|------|
| Nondumiso Gumede | 21904530 | Project Manager / Team Leader |
| Gcina Zwane | 22309743 | Frontend / UI-UX Designer |
| Phiwe Zondi | 25052694 | Research & Documentation |
| Siphosethu Mthembu | 25053103 | QA & Testing |
| Balindile Makhathini | 22132920 | Lead Developer / Backend |

 Architecture
User -> Platform -> Application -> Database (Firebase)

 Features Implemented in Kotlin
- Registration & Login - Secure login (LoginScreen)
- Past Papers - Search by module/year + verification badge
- Study Notes - Organised by module
- Module Circles - Chat for students doing same module (like WhatsApp but organised)
- AI Tools - Quizzes, Flashcards, Summary Generator
- Progress Tracking - 65% progress bar
- Search & Filtering

 Tech Stack
Kotlin, Jetpack Compose, Material3, Navigation Compose, Firebase (Auth + Firestore)

 Code Structure
- MainActivity.kt - Bottom Navigation (Home, Papers, Circles, AI)
- Models.kt - Data models (PastPaper, Note)
- Screens.kt - All screens: Login, Home, PastPapers, Circles, AITools
- FirestoreRepository.kt - Database (optional - for Firebase)

 How to Run
1. Clone: `git clone https://github.com/YOUR_USERNAME/campus-connect.git`
2. Open in Android Studio
3. Sync Gradle
4. Run

Screenshots
Add your app screenshots here

 GitHub Link
This repo: `https://github.com/YOUR_USERNAME/campus-connect`

Built with Kotlin for DUT Mobile App Development Project 2026
