# Calibre Wrapper

This provides a public crate that simply wraps the
private `calibre` crate, which is only accessible to
users affiliated with the Berkeley Wireless Research Center (BWRC).

This crate is completely empty, unless you enable the `commercial` feature flag,
which enables a dependency on `calibre`. If you do not have access to BWRC,
you likely won't have access to the BWRC GitLab instance, and this crate will not be of use to you.

If you have access to BWRC resources and would like access to the `calibre` crate,
please contact the authors.
