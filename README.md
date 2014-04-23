# Error Page

A super-simple minimal HTML page, optimised to be used for a static 500 error page or similar.

HTML is pre-minified, minus a couple of line-breaks to allow easier editing. No external assets required – all CSS and images are embedded.

## Usage

Add a custom title element, logo, alt attribute, and optionally amend the text. By default the template is set up to be a 500 page.

### Logo Image

A logo image is included using a base64 data URI. You can add your own logo here using an online data uri conversion tool, or using cli.

To convert an image and save the base64 data to your clipboard, run:

```
openssl base64 < path/to/image.png | tr -d '\n' | pbcopy
```

## Example

![Screenshot](screenshot.png)
