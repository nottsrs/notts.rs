layout: default.liquid
title: Notts.rs
---

With a broad aim to bring [Rust](https://www.rust-lang.org/) to Nottingham.

We will be starting with a weekly reading group for Rust.

[Twitter](https://twitter.com/NottsRs)

More to come very soon.

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
