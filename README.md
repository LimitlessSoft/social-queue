# social-queue

Approved social posts about LimitlessSoft products, waiting to go out. This repository holds
no code.

- `posts/<id>/`: one post, with `post.yaml` and the images and videos it uses.
- `posted.json`: what has gone out, where, with links. Written by the publisher only.
- `PAUSED`: if this file exists, nothing posts.

**Pushing a post here approves it.** The publisher in `LimitlessSoft/limitlesssoft--ecosystem`
(`.github/workflows/social-publish.yml`) posts it at its time. People make and approve posts with
`/social` in Claude Code, which runs `marketing/social/tools/queue.mjs` there.

The repository is public because Instagram fetches post images from a public URL.
