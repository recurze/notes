* Source: https://jesseduffield.com/beginners-guide-to-abstraction/
* Abstraction:
    - identify different chunks of code that are doing the same thing
    - create a method or a class with narrow interface which can be substituted
    - swap out the chunks with call to method/class
* Right abstraction:
    - Long time passes without having to expand (like optional flag).
    - Another developer doesn't find it hard to understand than if code was
      written without abstraction.
* You either:
    - Under abstract: if the feedback is to DRY your code
    - Over abstract: your methods are hard to understand
* Tips:
    - Minimize complexity
    - Right now doesn't mean right later (if it fits for 3 but not 4th)
    - Dont' be afraid to dismantle the wrong abstraction
    - When in doubt, do not abstract
    - When not in doubt, defend your decision


* Disc: https://news.ycombinator.com/item?id=23735991
* Is abstraction really combining duplicate code? Isn't it more of striping away
  irrelevant information by transforming between models. The main reason to
  abstract is not to DRY but to "abstract away" the unimportant.
* "I love software engineering, but the most satisfying moments in my work
  involve removing code or not relying on tech to solve problems whatsoever."
