+++
title = "Projects"
slug = "projects"
+++

## [Exercism App for macOS](https://github.com/apps-fab)
* [Exercism](https://exercism.org/dashboard) is an online, open-source, free coding platform that offers code practice and mentorship on programming languages. Since the platform can only be used online we(I and [Dela](https://github.com/savekirk)) decided to build the macOS app for it.
* Our goal was; to have fun and learn a couple of new things. 
* The journey 
    - The first unforeseen challenge was for me was that I hadn't built an app for macOS before. Although we would be venturing in territory I have played in before(apple), I was surprised at how little learning material there is on macOS development.
    - We started off by learning SwiftUI, something both of us hadn't used extensively. It was fun but also really hair pulling. SwiftUI is a very declarative language and coming from a UIKit background things felt tough. Also, what's up with that new Navigation API Apple? 
    - Then we started to build this thing. Very quickly my UIKit brain led me down the path of MVVM+C. As we explored the architecture to use, I quickly discovered how using MVVM was overengineering. Combine is built into SwiftUI and so the views are already reactive and so there's no need to have something else observing them. So, how do we do this better? 
    - In comes [Async Await](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/concurrency), she's the new kid on the block. She's shiny, she's pretty but does she live up to the hype? We decided to dip a toe in and so only the [App](https://github.com/apps-fab/exercism-app) is built using this.
    [The Swift API](https://github.com/apps-fab/ExercismSwift) is still using completion handlers. 
    - Accesibility is also a big part of this process. I have been paying attention to the accesibility APIs that apple provides and so while building this, it was also a large part of our learning.
    - Design, this has been fun for me especially and I am still learning. I know how to build a simple product but I struggle with making it appealing. 


## Vaazi
* [Vaazi](https://github.com/vaazi) is a Kiswahili word that means outfit. This an e-commerce platfrom I am building with a bunch of insanely talented individuals. 

* **Once a Swift girl, always a swift girl? Nope!**
    *  I got interested in this project because [Flutter](https://flutter.dev/) has been calling to me and I am genuinely interested in it's hot reloading ways. Did I hear a gasp? Clutching of pearls? No?
    *  The journey so far is filled with a lot of learning and staring deeply at pull requests. Flutter reminds me a lot of SwiftUI and I am enjoying the familiarity.