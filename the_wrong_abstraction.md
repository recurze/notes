* Source: https://www.sandimetz.com/blog/2016/1/20/the-wrong-abstraction
* Existing code exerts a powerful presence. It's very presence argues that it's
  both necessary and correct.
* We know that code represents effort expended, and we are very motivated to
  presever the value of this effort.
* Once you completely remove the wrong abstraction, you can start anew.
* Don't get trapped in the sunk cost fallacy
* When the abstraction is wrong, the fastest way forward is back.

---

* Disc: https://news.ycombinator.com/item?id=23739596
* The argument made is not "don't make abstractions until 100% sure it's
  correct," but to make abstractions wherever appropriate but do away as soon as
  you realize it's wrong abstraction.
    - It seems many misunderstood the point of the post.
    - "Duplication is far cheaper than the wrong abstraction" holds when there
      is a wrong abstraction to begin with. The author's advice isn't to stop
      abstracting because it might be wrong, but rather to do away with wrong
      abstraction because it's costlier.
* Rule of three: Only once you've done it thrice will you truly begin to
  understand what the abstraction should look like.
* Abstractions which have become inadequate should be corrected asap. A
  corollary is that abstractions should be designed such that they can be
  replaced or removed without much difficulty
* Is it really sunk cost fallacy?
    - Unwilling to take ownership. Aren't you responsible for correctness after
      your refactoring.
    - They are not rewarded for it.
    - Social reasons, often not wanting to make a big PR that's going to be
      scrutinized.
* Prev disc: https://news.ycombinator.com/item?id=17578714
    - Optimize code to reduce State > Coupling > Complexity > Duplication
* https://www.youtube.com/watch?v=8bZh5LMaSmE
