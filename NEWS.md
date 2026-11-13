# assertive.base 0.0.9.9001

Renova release, based on CRAN assertive.base 0.0-9 (archived on CRAN 2024-04-12).

- `R/are-identical.R`, `R/coercion.R`, `man/are_identical.Rd` and `man/is2.Rd`: `\link[assertive.properties]{are_same_length}` and `\link[assertive.types]{assert_is_all_of}` became plain text naming the functions and their packages, because those packages are not dependencies.
- `NEWS`: reformatted to R's NEWS format (`Changes in version ...` headings with `*` items) so `news()` can read it; the entries are unchanged.
- `DESCRIPTION`: the stale optional `Date: 2021-02-07` field was removed (metadata only).
- `DESCRIPTION`: `Version` set to `0.0.9.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL text) was added; the `License` field is unchanged.
- `README.md` was replaced by a short Renova README and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.
