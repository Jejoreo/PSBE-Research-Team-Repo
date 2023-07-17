`---`
## Technical POV
I'd like to customize this vault later on, if the changes is not yet satisfying, feel free to target the `.css` by hitting `ctrl + shift + i`. The targetted `.css` could be made and saved just like what I did in both `h2` and `h3`.

```css
/*Single Preview*/
.markdown-preview-view p{
	text-align: justify;
	text-justify: inter-word;
	text-indent: 0.5;
}

/*Heading 2*/
.cm-header-2, .markdown-preview-view h2{
	color: #450482;
}

/*Heading 3*/
/*Heading*/
.cm-header-3, .markdown-preview-view h3{
	color: #75048f;
}

/* Idk whether source should be treated the same >, This one's seperated*/
.markdown-source-view.mod-cm6 .cm-line {
	text-align: justify;
	text-justify: inter-word;
}

```

