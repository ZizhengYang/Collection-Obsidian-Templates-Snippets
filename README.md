# Collection-Obsidian-Snippets
This is a document collecting or different `Obsidian` snippets, how to write, how to use and how to expand

## How to use the Snippets?

- Find your `obsidian vault` directory
- Find `YOUR OBSIDIAN VAULT/.obsidian/` folder
- Find `YOUR OBSIDIAN VAULT/.obsidian/snippets/` folder
- Put the `css` files there
- Open obsidian app
- Enter `Settings`
- In the left bar, choose `Appearance`
- You may turn on your snippets in css-snippets

## Color and Icon

Here we have a sequence of snippets for coloring, labeling and make icons. Any way, they help you to mark up differences and organzie your vaults.

### colored-folders.css

Here is the discussion over coloring the navigation bar: https://forum.obsidian.md/t/adding-color-to-obsidian-a-rainbow-of-possibility/12805/11

- The `css code` is here: https://github.com/ZizhengYang/Collection-Obsidian-Snippets/blob/main/Color%20and%20Icon/colored-folders.css
- Original github.com repository: I didn't found
- Contributor: @Lithou: Colored Folders.css; [the forum](https://forum.obsidian.md/t/adding-color-to-obsidian-a-rainbow-of-possibility/12805/11
)

![](https://forum.obsidian.md/uploads/default/original/2X/a/af9ba0bf2fed2bf7299659a227424d4235aacf11.png)

```css
<!-- we can insert a new rule of coloring as below -->

.nav-folder.mod-root>.nav-folder-children>.nav-folder>.nav-folder-title[data-path^="YOUR-FOLDER-STARTING-LETTERS"],
    .nav-folder.mod-root>.nav-folder-children>.nav-folder>.nav-folder-title[data-path^="YOUR-FOLDER-STARTING-LETTERS"] + .nav-folder-children{
    background-color: var(--FoldF);}

.nav-folder.mod-root>.nav-folder-children>.nav-folder>.nav-folder-title[data-path^="YOUR-FOLDER-NAME"],
    .nav-folder.mod-root>.nav-folder-children>.nav-folder>.nav-folder-title[data-path^="YOUR-FOLDER-NAME"] + .nav-folder-children{
    background-color: var(--FoldF);}
```
