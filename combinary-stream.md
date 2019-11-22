# Combinary Stream

The documentation of the code and setup/config lives in the github repo  
[https://github.com/acolono/combinary-stream](https://github.com/acolono/combinary-stream)

### Mapping of elements per service

| Unified id | Twitter | Facebook | Youtube | RSS |
| :--- | :--- | :--- | :--- | :--- |
| url | tweet.url | fb.com/{?user?}/posts/{post.id} | youtube\#video:id + some magic | item:link |
| itemType |  | facebook |  |  |
| title |  | post.story | youtube\#video:snippet.title | item:title |
| body | tweet.text | post.message | youtube\#video:snippet.description | item:description |
| thumbnailUrl | user.profile\_image\_url | attachment.media\_url | youtube\#video:snippet.thumbnails.\(key\).url | item:media:image ? |
| authorName | user.name user.screen\_name |  |  | item:author |
| authorUrl | twitter.com/{user.name} | fb.com/{?user?} |  |  |
| publishedAt | [tweet.ts](http://tweet.ts) | post.created\_time | youtube\#video:snippet.publishedAt | item:pubDate |
|  | retweet\_count | shares | - |  |
|  | favorite\_count |  | youtube\#video:statistics.likeCount |  |
|  | quote\_count + reply\_count |  | youtube\#video:statistics.commentCount |  |
|  | coordinates |  |  |  |

