# markup-reset
Единый набор файлов для старта вёрстки проекта.

---

## Snipets

#### slick-hack mixin
```
.slick-hack () {
	.slide { .display (none);
		&:first-of-type { .display (block); }
	}

	&.slick-initialized .slide { .display (block); }
}
```
