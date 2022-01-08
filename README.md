# Android-Study-Jams

**Attendance Management**

![visitors](https://visitor-badge.glitch.me/badge?page_id=shadsheikh.attendancemanagment&left_color=green&right_color=red)
![vistors](https://visitor-badge.glitch.me/badge?page_id=yourstore) 

**Problem Statement:**

Over past two years, local businesses have faced lot of troubles due to Covid-19 and lockdown imposed. This has resulted in low sales, payroll cuts , unemployment in stores. 
Many businesses have permanently closed,  across the world, affecting the world economics. 
Local consumers also face a lot of difficulties buying the neccessary, daily products. Limited, open hours, covid protocols made the situation worse.


Covid has impacted almost every business be it small or medium, and it's effect is not going anywhere with new variants coming each year.

**Proposed Solution :**

This can be solved if there's a way to connect local buyers to local consumers. Yes there is, Android smartphones. there are over 3 billion active android users around the globe. I have worked on a Local e-commerce android applciation which connects local e-commerce to to potential consumers. Increasing Seller's branding, reach and sales. 

businesses can signup and  update info like store name, location and contact details. Then List products and share offers. 
<br>
local users can browse through product list , sellers list.  
This will lead to sales growth and increased reach to consumers. 

![attendace flow](https://user-images.githubusercontent.com/66586570/148637252-7dfb74ce-144b-4e94-9d0b-e915dd891194.jpg)
![time table flow](https://user-images.githubusercontent.com/66586570/148637258-5f99c0c0-97f0-4e7c-ba42-bb927df85309.jpg)

**Functionality & Concepts used :**

**Techstack**

I made **Yourstore** on Android ( Kotlin ) and Firebase for backend and authentication Firestore for database, storing sellers & consumers profile data, Products data in collection. Cloud Storage for storing products image. 

 - **Authentication** is implemented for Login, Signup with firebase function like SigninWithEmailAndPassword() and errors are catched and displayed with proper error.
 - **Navigation :** Users can navigate across activities and fragments.
 -  **Constraint Layout :**  activities in the app uses a flexible constraint layout, which is easy to handle for different screen sizes.
 - **RecyclerView :** List of products queried from firebase is presented in recyclerview efficiently, loading  just the items on focus. Learned using Adapter, view holder, layout manager.
 - **LiveData:** [Glide](https://github.com/bumptech/glide) dependency is used for loading images from cloud store to imageviews.
 -  **Kotlin** Class and Data model used for firestore queries.




**Application Link & Future Scope :**

The application is in active development, some more features are needed to be added.  
Thanx, Google Developer students club, BIT Mesra for the workshops. 

**APK :**   [Try app](https://github.com/Shad-Sheikh/Attendance-Managment/blob/main/APK/Attendance%20Managment.apk)

**Demo:**

https://user-images.githubusercontent.com/66586570/148635935-30463050-8f66-4230-9597-ff3d76b6701f.mp4





Learning materials: 

[developer.android.com](https://developer.android.com/courses/android-basics-kotlin/course)

