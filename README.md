# goodreads-wordpress
Scraping all goodreads reviews of a profile to html that can be embedded in your wordpress blog posts to create your goodreads blog!

## FUTURE WORK
Please note that this is still a WIP. Please feel free to contribute. Some of the things that need to be worked on are as follows:

1. Currently it scrapes only the first page. During multiple pages scraping, it requires goodreads sign-in and after signing in, it redirects to the goodreads updates page so it loses track of where it was scraping and comes down with an error and the output consists of only the first page.
2. Currently, the shelves labels to which the books are added to are not being reflected and utilized. Adding these labels along with reviews would be a good addition.
3. In addition to the above point, trying to also cluster and add a navigation tool that you can use to access books/reviews belonging to a specific shelf or label would be a good feature.

## Acknowledgements
- The original source code to which I have made changes : https://github.com/ankitmodi/year_end_book_blog_using_python/tree/main
- The documentation for the above source code created by the author : https://ankitmodi.github.io/intro-to-web-scraping-using-python-on-goodreads/
