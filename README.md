# megaforce-blog-redirect

Keeps old links to the archived WordPress blog working. GitHub Pages serves this
repo on **blog.megaforce.audio** and sends every request to the static blog at
https://megaforce.audio/blog/ (source: [Hikari-Tsai/megaforce](https://github.com/Hikari-Tsai/megaforce)).

| Old URL | New URL |
| --- | --- |
| `blog.megaforce.audio/?p=644` | `megaforce.audio/blog/post-644.html` |
| `blog.megaforce.audio/?cat=5` | `megaforce.audio/blog/#cat-5` |
| anything else | `megaforce.audio/blog/` |

`404.html` is a copy of `index.html`, so old paths such as `/wp-content/...` redirect too.
