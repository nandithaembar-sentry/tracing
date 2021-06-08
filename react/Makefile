# Must have `sentry-cli` installed globally
# Following variable must be passed in
# SENTRY_AUTH_TOKEN
SENTRY_ORG=testorg-az
SENTRY_PROJECT=javascript-nans-test
RELEASE=489ef29b0aafcfbfca2caaf7dc41513390a1d601
# RELEASE=`sentry-cli releases propose-version`
PREFIX=static/js

# setup_release: create_release associate_commits upload_sourcemaps

# create_release:
# 	sentry-cli releases -o $(SENTRY_ORG) new -p $(SENTRY_PROJECT) $(RELEASE)

# associate_commits:
# 	sentry-cli releases -o $(SENTRY_ORG) -p $(SENTRY_PROJECT) set-commits --auto $(RELEASE)

# upload_sourcemaps:
# 	sentry-cli releases -o $(SENTRY_ORG) -p $(SENTRY_PROJECT) files $(RELEASE) \
# 		upload-sourcemaps --url-prefix "~/$(PREFIX)" --validate build/$(PREFIX)
