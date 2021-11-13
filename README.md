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
## Image relative

### img-centering.css

- The `css code` is here: https://github.com/ZizhengYang/Collection-Obsidian-Snippets/blob/main/Image%20relative/img-centering.css
- Original github.com repository: Doesn't exists
- Contributor: @猫老大的小站台; [the blog](https://publish.obsidian.md/maolaoda/%E5%AD%A6%E4%B9%A0/%E7%AC%94%E8%AE%B0%E8%BD%AF%E4%BB%B6/Obsidian%E9%85%8D%E7%BD%AE)

![screen shot from my notes](https://cdn.mathpix.com/snip/images/SLO9HUKRy8OJg3v87qyXyM9L22aoespys8auXczTc2A.original.fullsize.png)

```css
very simple ~ just look up the code
```

### img-shadow-roundedBorder.css

- The `css code` is here: https://github.com/ZizhengYang/Collection-Obsidian-Snippets/blob/main/Image%20relative/img-shadow-roundedBorder.css
- Original github.com repository: Doesn't exists
- Contributor: @猫老大的小站台; [the blog](https://publish.obsidian.md/maolaoda/%E5%AD%A6%E4%B9%A0/%E7%AC%94%E8%AE%B0%E8%BD%AF%E4%BB%B6/Obsidian%E9%85%8D%E7%BD%AE)

![screen shot from my notes](https://cdn.mathpix.com/snip/images/SsffNGNpN0DMq5Sm9z8SupYnXR6Uu4CL6x9HLBkp3TA.original.fullsize.png)

```css
.markdown-preview-view img {
    max-width: 100%;
    outline: none;
    -webkit-filter: drop-shadow(10px 10px 10px rgba(8, 8, 8, 0.5)); /* the setting for the shadow effect */
        background-clip: content-box,padding-box;
        border-radius: 20px 20px 20px; /* the setting for the border rounding */
}
```

## Starting of the templates section:

