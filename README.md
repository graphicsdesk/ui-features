This is a collection of simple HTML and CSS components to be reused in Ellipsis. It is _not_ intended to be a general purpose component library.

## Components

| Folder | Description | Article(s) |
|--------|-------------|------------|
| `navbar-parts` | A navbar for news features with several parts. | [🔗](https://www.columbiaspectator.com/news-features/2019/04/11/up-against-the-invincible-a-professor-was-convicted-of-sexual-misconduct-why-is-he-still-on-campus-2/) | 
| `eye-navbar` | Just a prettier navbar for Eye articles. | |

## Useful links

[Ellipsis](https://spectator.arcpublishing.com/ellipsis)

[PageBuilder](https://spectator.arcpublishing.com/pb/admin/app/browse/pages.html)

[Kevin's PageBuilder fork](https://github.com/kevinl94303/Spectator-PageBuilder-Features)

## Before deploying an interactive on PageBuilder

* Remember `IntersectionObserver` and `position: sticky` polyfills.

* If a `transform: translate3d(0, 0, 0)` is needed for the sticky element, don't forget to add the webkit equivalent, `WebkitTransform`.

* Remember the Spec navbars.
