# Nashira Deer // Hydrolink

An implementation of a Lavalink client made with tokio independent of the Discord library, used in production by Hydrogen.

[![PayPal](https://img.shields.io/badge/Paypal-003087?style=for-the-badge&logo=paypal&logoColor=%23fff)](https://www.paypal.com/donate/?business=QQGMTC3FQAJF6&no_recurring=0&item_name=Thanks+for+donating+for+me%2C+this+helps+me+a+lot+to+continu+developing+and+maintaining+my+projects.&currency_code=USD)
[![GitHub Sponsor](https://img.shields.io/badge/GitHub%20Sponsor-181717?style=for-the-badge&logo=github&logoColor=%23fff)](https://github.com/sponsors/nashiradeer)
[![Crates.io](https://img.shields.io/crates/v/hydrolink?style=for-the-badge&logo=rust&logoColor=%23fff&label=Crates.io&labelColor=%23000&color=%23000)](https://crates.io/crates/hydrolink)
[![docs.rs](https://img.shields.io/docsrs/hydrolink?style=for-the-badge&logo=docsdotrs&logoColor=%23fff&label=Docs.rs&labelColor=%23000&color=%23000)](https://docs.rs/hydrolink/)

Hydrolink is part of [Hydrogen Framework](https://github.com/nashiradeer/hydrogen-framework), this means that this crate is designed to be used on Discord bots created using [serenity](https://crates.io/crates/serenity) and [twilight](https://crates.io/crates/twilight), but is sufficiently generic to be used by any other application that does not use these Discord libraries.

## Donating

Consider donating to make Hydrolink development possible. You can donate through Nashira Deer's [PayPal](https://www.paypal.com/donate/?business=QQGMTC3FQAJF6&no_recurring=0&item_name=Thanks+for+donating+for+me%2C+this+helps+me+a+lot+to+continue+developing+and+maintaining+my+projects.&currency_code=USD) or [GitHub Sponsor](https://github.com/sponsors/nashiradeer).

## Features

- `lavalink-trace`: It always makes REST calls using the `trace` parameter which makes the error responses have the stacktrace that originated it.
- `rustls-webpki-roots`: Enables the use of Rustls with Webpki roots.
- `rustls-native-roots`: Enables the use of Rustls with native roots.
- `native-tls`: Enables the use of native-tls.
- `native-tls-vendored`: Enables the use of native-tls with vendored feature.

## Credits

Hydrolink is a Nashira Deer project licensed under the [MIT License](https://github.com/nashiradeer/hydrogen-framework/blob/main/hydrolink/LICENSE.txt).
