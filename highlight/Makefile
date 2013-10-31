

all :  highlight

highlight:
	[ ! -d src ] && mkdir src || true
	[ ! -x src/highlight ] && cp `which highlight` src/highlight || true


install:
	[ ! -d $(DESTDIR)$(PREFIX) ] && mkdir -p $(DESTDIR)$(PREFIX) || true
	[ ! -x $(DESTDIR)$(PREFIX)highlight ] && cp src/highlight $(DESTDIR)$(PREFIX) || true


clean:
	rm -fr src

