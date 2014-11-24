dist_bin_SCRIPTS = suspenders

CLEANFILES = $(dist_bin_SCRIPTS)
EXTRA_DIST = suspenders.in

edit = sed \
       -e 's|@RUBY[@]|$(RUBY)|g' \
       -e 's|@rubydir[@]|$(rubydir)|g' \
       -e 's|@gemsetuppath[@]|$(gemsetuppath)|g'

suspenders: Makefile suspenders.in
	$(edit) $(srcdir)/$@.in > $@
	chmod +x $@
