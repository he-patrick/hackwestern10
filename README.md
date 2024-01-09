Devpost: [tranSLate](https://devpost.com/software/translate-dyu8jl?ref_content=user-portfolio&ref_feature=in_progress)

## Inspiration 💡 
With over 300 sign languages and 7000 dialects, the lack of translation resources bridging these forms of communication has been a significant barrier for deaf and speech-impaired communities. Despite the abundance of applications that can convert one verbal dialect to another, the world is still in search of a product that is capable of creating sign language accessibility. Thus, it is our goal to create a unique translation application that can help others to understand sign language and break down these language barriers one by one.

## What it does 💭 
By incorporating object detection and computer vision, our project, tranSLate, enables the user to gain real-time translation of ASL to a dialect of their choice. Whether it is English, Chinese, or French, we hope to provide more opportunities to the deaf and mute by allowing them to communicate in other countries across the world.

## How we built it ⚙️ 
In hopes of turning our ideas into reality, our team utilized various languages, tools and libraries to make this project possible. By using several Python libraries, our back-end team successfully implemented object and action detection to enable sign language recognition. Specifically, we used OpenCV to enable computer vision for data collection, Mediapipe for detecting specific landmarks and coordinates on the human hand, and Scikit-Learn to train the data into specific classifications. The data we collected was then converted into a dialect of the user’s choice through the Google Translate API, which gave us access to hundreds of possible translations. Finally, our front-end team tied everything together using Next.js and Tailwind, where they created an authentic, interactive interface that allows our users to access these resources comfortably.

## Challenges we ran into * 
From the number of languages and libraries we used for tranSLate, the majority of our conflicts resided in merging our code onto one Github branch and resolving individual errors. Whether it was inaccurate data collection or poor syntax (one of our problems was downloading 3.12.0 Python because Mediapipe is unable to run on versions higher than 3.11 😅), our whole team has faced many times of confusion and frustration that has made us even more proud of our final project.

## Accomplishments that we're proud of 💪
While there were many moments of frustration from errors, we kept trying to resolve our issues and managed to get everything working as individual projects. Unfortunately, we were unable to integrate all the components together successfully.

## What we learned 🧠 
While we learned several frameworks, tools and languages, the most important takeaway was the importance of planning to optimize our building time. From learning to integrate Python scripts, deploying Next.js frameworks, and training data into classifications, there were many complex concepts that we uncovered for the first time. Thus, planning our time accordingly will help us complete future projects more efficiently.

## What's next for tranSLate 🚀 
To improve the precision of our object and action detection, our next steps include expanding the vocabulary within our data set and enriching our training data to eliminate unnecessary human errors. Furthermore, while we successfully translated ASL into spoken languages, the time restraints limited our ability to extend this feature to other sign languages like CSL, JSL, and BSL. Moving forward, tranSLate is committed to promoting inclusivity in the deaf-mute community and elevating their communication to a global level.
