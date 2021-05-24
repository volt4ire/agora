Obsidian
* you can change the file name at the top of this window, and Obsidian will automatically update all links to it.

# shortcuts
- ⇧⌘O: show outline view


like in this theme https://github.com/bcdavasconcelos/Obsidian-GDCT

# embedding
Obsidian native embed (uses double brackets instead of MD's single for images) (also works for eg .mp3, .pdf, .mp4)
![[Engelbart.jpg]]

## iframes
```html
<iframe src="INSERT YOUR URL HERE"></iframe>
```

youtube hack:
```html
<iframe src="https://www.youtube.com/embed/VIDEO_ID"></iframe>
```

> Some websites have quirks that don't allow you to embed them. For example, you can't embed a YouTube video by using its normal URL, but you can use its embed URL which is `https://www.youtube.com/embed/VIDEO_ID`. If you want to embed a website, try searching for "{website} embed iframe". Fore xample for Twitter:


Markdown files: md;
Image files: png, jpg, jpeg, gif, bmp, svg, tiff;
Audio files: mp3, webm, wav, m4a, ogg, 3gp, flac;
Video files: mp4, webm, ogv;
PDF files: pdf (`![[My File.pdf#page=number]]` to open to that specific page of the PDF directly)


## resize embeds & images
- For embeds, use `![[image.png|100x100]]`

- For markdown images, use `![AltText|100x100](https://url/to/image.png)`
    - To have the image scale according to its aspect ratio, omit the height `![[image.png|100]]`