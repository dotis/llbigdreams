initial clone of the site

```
wget --mirror --convert-links --adjust-extension --page-requisites --no-parent llbigdreams.com
```

full output is included in another file.

The static html retrieved was put into the /docs/ folder.

github pages was enabled for the main branch /docs/ folder.

The site looks terrible because of a CORS issue fetching some javascript from a CDN.

Copied the rollbar js over to the local to resolve the CDN issue.

My adblocker is still blocking the js in firefox; hopefully that is just an issue for me.

The background image in the background is not showing up.

Modified the url for the bg image.

All looks good now I think.
