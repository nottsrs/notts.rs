layout: default.liquid
title: Notts.rs
---

With a broad aim to bring the [Rust programming language](https://www.rust-lang.org/) to Nottingham.

Each week we are sitting down to read through a chapter of the Rust programming language book.

Follow on [Twitter](https://twitter.com/NottsRs)

Join the conversation on [Slack](https://join.slack.com/t/nottsrs/shared_invite/enQtNDI3NjcwNjUzNTY5LWZkYzE0NjUxN2M4MGVjMDZmNmQ3NjBmMzExMjQzZDUyZGQyNjQzYmY2ODdjNjAzNDgzODcyZTQwNjFjOTE1ZjY)

Sign up to join on [Meetup](https://www.meetup.com/NottsRs/)

Watch out previous reading group sessions on [Youtube](https://www.youtube.com/channel/UCbpvVwbLkGxeWX0On10JvSA)

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
