# Original WordPress Site Archive

This file records the content recovered from the legacy WordPress installation at
`liyangyang.com/` (database export `liyangya_blog_1786886882.sql`, MySQL 5.7, ~30 MB).

The WordPress directory and the SQL dump are reference material only. They are git-ignored
(`liyangyang.com/`, `*.sql`) and must never be committed or published.

## Site identity

| Item          | Value                           |
| ------------- | ------------------------------- |
| Site title    | Dr. Yangyang Li                 |
| Tagline       | Homepage                        |
| URL           | http://www.liyangyang.com       |
| Platform      | WordPress 5.3.21                |
| Theme         | SlimWriter 1.2.1                |
| Database      | liyangya_blog (prefix `wp_yli`) |
| Admin account | `yli` (liyangyang@live.com)     |

The `yangyang.li` domain 301-redirected to `www.liyangyang.com`.

## Recovered pages

The original site was a single-page homepage. The `Blog` and `Contact` pages existed but were
marked private and were never public.

### Home (`Yangyang Li`, published)

```text
Senior Engineer （Professor-level）
Academy of Cyber, Beijing, China

Education
- Ph.D., Computer Science, July 2015, Beijing University of Posts and Telecommunications, Beijing, China
- Visiting Ph.D., Computer Engineering, March 2014 - September 2015, University of Toronto, Toronto, Canada
- B.Engr., Information Engineering, July 2009, Nanjing University of Information Science and Technology, Nanjing, China
```

This content is superseded by the current Home page (`_pages/about.md`). Note the Toronto visiting
dates in this archive (2014–2015) differ from the current site (2013–2014); the current site is
authoritative.

### Contact (private)

```text
Web: http://www.liyangyang.com/
Email: yli@csdslab.net
Phone: +86-(0)10-6889-3339
```

The current site intentionally uses the newer contact details (`liyangyang@live.com` + ORCID +
ResearchGate) instead of these.

### Blog (private)

Empty; the blog was never published.

## Attachments referenced in the database

`header.png` / `cropped-header.png`, `favicon.jpg` / `cropped-favicon.jpg`,
`cropped-148734238258433.png` (header crop), and three coffee photos uploaded as `浓缩咖啡`
(espresso), `三明治` (sandwich), and `咖啡` (coffee).

## Orphaned images (uploaded, never attached to any post/page)

These files exist under `wp-content/uploads/` but appear in no published content:

- `front.jpg` (6211×1988 banner), `photo.jpg`
- `coffee.jpg`, `espresso.jpg`, `sandwich.jpg`
- `contact.jpg`, `contact2.jpg`
- `research1.jpg` … `research5.jpg`
- `hertz_professional_services.jpg`, `Professional-1.png`
- `WechatIMG6.jpeg`, `WechatIMG7.jpeg`

They are not part of the current site by design.
