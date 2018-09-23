## Wordpress Instagram Plugin

### Project Scope
- Develop a Wordpress plugin where users can pull in specific posts based off of a hashtag from their own Instagram account
- The plugin should only allow users to setup one hashtag at a time e.g. the user would only be able to pull in posts for `#tb`, and not any other hashtag at the same time
- The plugin should also support the ability to just pull in posts from the user's Instagram account
- We will need to embed the pulled posts in a seamless way on the WordPress site - so that any user can place the content on their site
- At present, this is a personal project, so the plugin/app is not intended to be submitted for review
    - We will be using `Sandbox Mode`
    - This means that the plugin will be limited to accessing only `20` of the user's most recent posts
    - *This stance may change in the future depending on the quality of the end product*

### Considerations
- If you did go down the route of submitting this plugin/app for review, the `scope of access` which is specified in the Instagram API [docs](https://www.instagram.com/developer/authorization/) should just be `basic` as we only want to read the user's own content
