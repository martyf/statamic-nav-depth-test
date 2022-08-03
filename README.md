## How to use

- Clone the repo
- Run `composer install`
- View the site

You will see 4 nested lists, all the same nav.

The first two are in one partial. The second two are in another partial, and that partial is cached.

The repo is configured to use the **runtime** engine, and highlights the second list in red to highlight the incorrect depths. Change to **regex** and the issue disappears.
