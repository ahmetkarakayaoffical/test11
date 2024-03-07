SUBDIRS = src

cronddir = $(sysconfdir)/cron.d

install-data-hook:
	mkdir -p $(DESTDIR)$(cronddir) && \
		cp -af debian/scndlp.cron $(DESTDIR)$(cronddir)/scndlp

