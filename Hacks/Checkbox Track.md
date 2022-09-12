# Setting up tracks

Paste this in to a blank Obsidian note to read.

## Before you start

To do this you need to be familiar with CSS, Frontmatter
These pages should help:

- [Obsidian Docs on YAML Frontmatter](https://help.obsidian.md/Advanced+topics/YAML+front+matter)
- [Obsidian Docs on Custom Styles](https://help.obsidian.md/How+to/Add+custom+styles)
- [Obsidian Docs on Customising CSS](https://help.obsidian.md/Advanced+topics/Customizing+CSS)

Note that the track is a markdown list inside a Blockquote. It's unlikely you'll want to put a todo list inside a blockquote in real life so this allows you to keep tracks separate from other todo lists on the same page.

There are 3 steps to setting this up:

1. Edit the frontmatter on your page
2. Add markdown for your Track
3. Add CSS to custom CSS file (one time setup)

## The Doing Part

Put this in the frontmatter ...

```
cssClass: tracks
```

Then set up tracks like this ...

```
> - [x]
> - [x]
> - [ ]
> - [ ]
```

It will then use the following CSS to style...
(Settings > Appearance > CSS Snippets Folder Icons)

```css
.tracks {
  --background-modifier-border: #464646;
}

.tracks blockquote {
  margin: 0;
  padding: 0;
  border: 0;
}

.tracks blockquote * {
  display: inline-block;
  margin: 0;
}

.tracks blockquote ul {
  padding: 0;
  margin: 0;
}

.tracks blockquote li {
  text-indent: 0;
  display: inline-block;
}

.tracks blockquote .task-list-item-checkbox {
  margin: 0;
}

.is-mobile .tracks blockquote .task-list-item-checkbox {
  width: 40px;
}

.tracks .contains-task-list li {
  background: none;
  margin: 0;
  padding: 0;
}

.tracks ul > li.task-list-item .task-list-item-checkbox {
  margin-left: 0;
}
```
