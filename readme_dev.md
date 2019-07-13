**Intent search_movie expressions:**

```
search person
search person prompt
search person with keywords
search person with keywords prompt

search title
search title prompt

search genre
search genre prompt
search genre keywords
search genre keywords prompt
search genre title
search genre title prompt
search genre with keywords
search genre with keywords prompt
search genre where person
search genre where person prompt
search genre person with keywords
search genre person with keywords prompt
search genre title with keywords
search genre title with keywords prompt
search genre where person with keywords
search genre where person with keywords prompt

genre where person with keywords
genre where person with keywords prompt
```

**Entities:**

```
search      --> [search_entities_it.json]
genre       --> [genre_entities_it.json]
where       --> [where_entities_it.json]
with        --> [with_entities_it.json]
prompt      --> [prompt_entities_it.json]

title       --> @sys.any
keywords    --> @sys.any
person      --> @sys.person
```
