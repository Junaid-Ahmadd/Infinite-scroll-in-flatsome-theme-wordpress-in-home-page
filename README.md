# Infinite-scroll-in-flatsome-theme-wordpress-on-any-page
Implement infinite scroll in any page of your wordpress flatsome theme other than catalog pages.

In the flatsome theme, they use a third party infinite library, so it is already present on the website and is being loaded and we don't need to modify it.

In the javascript file, you will see that we included only one page url "/page2" but what if we have many pages "/page3,4,5"?
Answer:
We only need to add the starting page url from which we first want to fetch items and after the first page is loaded it will automatically go the next pages.

Feel free to modify the script.
