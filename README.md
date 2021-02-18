.container { width: 1200px; margin-left: auto; margin-right: auto; padding-left:
15px; padding-right: 15px; /_ outline: 2px solid red; _/ }

/_ Хедер _/ .page-header { border-bottom: 1px solid var(--header-border); }

.page-cont, .page-nav { display: flex; align-items: center; }

.page-cont { justify-content: space-between; }

/_ Лого _/ .logo { color: var(--black-color); font-family: Raleway, sans-serif;
font-weight: 700; font-size: 26px; line-height: 1.19; }

.half-logo { color: var(--accent-color); }

/_ Страницы сайта _/ .site-nav { display: flex; margin-left: 93px; }

.site-nav .item + .item { margin-left: 50px; }

/_ .site-nav .item:not(:last-child) { margin-right: 50px; } _/

.site-nav .link { display: inline-block; padding-top: 32px; padding-bottom:
32px;

color: var(--primary-text-color); font-weight: 500; line-height: 1.15;
letter-spacing: 0.02em; }

.site-nav .link:hover, .site-nav .link:focus, .adr-nav .link:hover, .adr-nav
.link:focus, .link.current { color: var(--accent-color); }

/_ Ссылки на почту и телефон _/ .adr-nav { display: flex; }

.adr-nav .item + .item { margin-left: 50px; }

.adr-nav .link { display: inline-block; padding-top: 32px; padding-bottom: 32px;

color: var(--secondary-text-color); font-weight: 500; line-height: 1.15;
letter-spacing: 0.02em; }
