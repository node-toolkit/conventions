# Emoji

We use [emoji](https://www.webpagefx.com/tools/emoji-cheat-sheet/) for more than expressing mood and reactions during conversations. Emoji also happen to be great for "tagging" useful information in a way that is semantic and easily recognizable for both humans and computers. 

**Why not use labels?**

We ju


**How it works**

A single emoji is not very useful as a "tag", since any user can add an emoji to any issue comment. Thus, to make it clear when emoji are being used as "tags", we pair them together. 

For example, when building the search index for a project's website, we might want ot automatically include links to useful issues or comments on the project's GitHub repository. To accomplish this, we would probably do a few things (each of which starts with getting all of the issues and comments through GitHub's API)""

- use issue labels to find potentially useful issues (this is the least desirable of the approaches, because it creates a temptation to begin using labels for something other than what they should be used for)
- filter and sort issues/comments using regular expressions or other similar logic.
- use emoji, like :mag: (`:mag:`), along with other emoji to indicate that the contents of a comment or issue is useful to show in search results. 

When combined, these approaches work well together. This encourages our filtering logic to be as specific as possible, and allows us to mark exceptions-to-the-rule manually. 

_(This will never be foolproof, but it's more than adequate for the purpose it serves)_

## Useful emoji

WIP (this is at the idea stage, I'm just throwing a few emoji in this table to spur ideas and discussion).

The following emoji can be paired with other emoji to denote significance.

| **base** (symbol/code) | **description** |
| --- | ---  |
| :mag: / `:mag:` | Indicates article is useful for search |
| :bar_chart: / `:bar_chart:` | Indicates article is useful for search |
| :bulb: / `:bulb:` | Indicates a useful idea | 
| :art: / `:art:` | Related to design / appearance | 