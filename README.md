# CSSGrid
impelements how grid layout works.

It has the following main blocks:
.container is the global wrapper that has small margins to the left and to
the right.

.main-header is the header that contains the .logo (occupies 20% of
space, floats to the left) and the .main-menu (occupies 79% of space,
floats to the right). The header is also assigned with a hacky fix to clear the floats.

.content-area-wrapper wraps the main .content-area
(occupies 66.6% of space minus 1rem reserved for margin, floats to the left)
and the .sidebar (occupies 33.3% of the space, floats to the right). The
wrapper itself is also assigned with a clearfix.

.sponsors-wrapper contains the logos of the sponsors. Inside, there is
a .sponsors section with the display property set to table. Each
sponsor, in turn, is displayed as a table cell.

.footer is our footer and spans to 100% of space.
