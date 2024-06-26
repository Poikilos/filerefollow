# FileReFollow

Follow redirects that are in the form of HTML files. Sometimes a URL that appears to point to a file is actually an HTML landing page for that file. This script digs deeper and gets the actual file link from each page in the current directory, as long as the URL is absolute.


## Usage
- Download a list of URLs from a page (such as using the "DownloadThemAll!" extension for Firefox. Neither DownloadThemAll nor Firefox endorse this project, and they are mentioned only under Fair Use and/or Nominative Use).
- Run `filerefollow` in the directory where the download files exist (files that have a binary extension such as ".mid" but actually contain HTML).
- That's it! After running the script, HTML will be moved to an "html" folder, and media will be downloaded to a "media" folder.
  - For each file that was skipped, the old file will not be moved. This allows continuing where you left off later after your connection, the website, or this program was improved.


## License
See [license.txt](license.txt).
