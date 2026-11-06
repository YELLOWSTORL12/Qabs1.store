# Testing status

As of 2026-11-06, a local QABS candidate passed 395 checks across seven suites using synthetic data and mocks where applicable. These are not cloud end-to-end tests or production acceptance.

A separate local Vendure experiment used two synthetic merchants and channels. An expanded test covered selected product, customer, draft-order and stock-location access; the corrected run passed 40 checks. The initial run reported two harness failures because ENTITY_NOT_FOUND was not recognized as a denial; the corrected run also checked that the other merchant's product remained unchanged. Files and all other API operations were not comprehensively tested.

A separate Medusa experiment started against synthetic local PostgreSQL and passed health and unauthenticated-admin checks. Two-merchant isolation remains untested. Neither engine has been selected for production.

The supplied theme archive contained 43 unreadable assets. A reconstructed local candidate is not a verified original or a release-ready theme.
