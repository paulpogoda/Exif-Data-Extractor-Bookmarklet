# EXIF Data Extractor Bookmarklet

This bookmarklet scans all images on the current webpage and allows you to check their EXIF metadata easily using the service https://exif.tools/.

## How to Use

1. Add a new bookmark in your browser.
2. Name it `EXIF Data Extractor`.
3. Copy the contents of the `exif-data-extractor.js` file and paste it as the bookmark's URL.
4. Navigate to any webpage with images.
5. Click the bookmarklet, a panel will appear with image previews and links to check their EXIF metadata.
6. **Unexpected Bonus**: This bookmarklet can help you extract Facebook Cover Photos from non-public profiles

## Security and Limitations

* **URL Transmission:** The bookmarklet sends the image URLs to a third-party service (exif.regex.info). The content of your interaction with the site itself is not transmitted anywhere.
* **No access to local files:** The bookmarklet cannot analyze images uploaded from your computer or embedded into the page via `data:URI`.
* **Hotlink protection:** Some websites may block direct access to their images from other resources. In this case, the analysis service will not be able to retrieve the file and will return an error.

## Credentials

Created by [Pavel Bannikov](https://github.com/paulpogoda) for [Provereno Media](https://provereno.media)

## License

Distributed under the MIT License.

## Do You Like It? 

**[Support my team on Patreon](https://www.patreon.com/c/provereno)**
