subst_rule = -e 's,[@]libexecdir[@],$(libexecdir),g'

%: %.in
	$(SED) $< > $@ $(subst_rule)

dist_bin_SCRIPTS = \
  bin/git-import-release \
  bin/git-package-debian \
  bin/git-package-debian-create \
  bin/git-packaging-merge-helper \
  bin/git-release

bin_SCRIPTS = \
  bin/git-packaging-find-lib

EXTRA_DIST = \
  bin/git-packaging-find-lib.in

CLEANFILES = \
  bin/git-packaging-find-lib

dist_libexec_SCRIPTS = \
  lib/gp-autoconf \
  lib/gp-cleanup \
  lib/gp-debian \
  lib/gp-git
