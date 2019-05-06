# my-ideas
My ideas. Any.

## My quotes (any coincidences are just coincidences)

1. Any story can be dramatic. Just turn on dramatic music.

## Apps

1. Something that hepls read artciles from the web
2. Cute web site (+mobile app) where user can find chords(and music sheets) for songs for different instruments, also user can add chords, info about song/album. Kinda wiki for musicians + chords, maybe deep analysis of songs.
3. App for splitting mp3 files into layers and combine them in custom order and musical arrangement, probably I'd need some sort of AI.
4. App for ordering, selling and publishing audiobooks.
5. App that replaces recruiters, where you can find job or find programmers, it's also aggregator of information from github, stack overflow and so on. You can put there resume, find programmers for startup, search by skills and do many other things
6. Aggregator of video games like flickmetrix 
7. Application(AI) that posts new content every day(articles, videos, books, news, music, etc.) that based on user's preferences. The main point is to increase user's preferences.
8. App with html elements and templates with html code view. 
9. Create my AI(or not) version of chess (based on pure principles and logic)
10. Create website with analysis of lyrics and tunes of songs
11. App for checking availability of websites and notifying if something fail
12. multiple copy paste buffer
13. Time converter (simple and without bullshit)
14. SVG sheet music generator
15. Mobile app for ssh remote commands (start server or smth like this)
16. skizo - app for creating text drafts
17. App for code reviewers

# Articles

1. about certifications
2. What's wrong with async/await
3. Declarative Node.js (Promise compositions are not compositions)
4. Declarative javascript on UI
5. [How I use travis-ci](https://guseyn.com/posts/travis-control-quality?v=1.0.64)
6. We all don't need outsourcing companies
7. Is copy paste always bad?
8. Are you ready for freedom 
9. Use magic numbers, because they are not
10. Why do we really need programming? 
11. It does not matter how many arguments your function have.

## open source

Library that can predict by name of your object what it does and you don't have to write a big compoistion of async objects.

Let's say we have this

```js
new ParsedJSON(
  new StringFromBuffer(
    new ResponseBody(
      new ResponseFromHttpsGetRequest(
        requestOptions
      )
    )
  )
).call()
```

And now we instead can write smth like

```js
JSONFromHttpsRequest(requestOptions).call()
```



