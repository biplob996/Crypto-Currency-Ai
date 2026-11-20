# Crypto Currency AI — Android starter project

A dark Binance-inspired Android starter with:
- Demo mode: $10,000 virtual USD balance and simulated BUY/SELL.
- Live Market mode: public market prices fetched from CoinGecko's public markets endpoint.
- Selected coin, 24h change, refresh control and basic portfolio holdings.
- Clear read-only boundary in Live Market mode: no real orders, deposits, withdrawals, private keys or custody.

## Open and build
1. Install Android Studio (latest stable) on a computer.
2. Choose **Open** and select this `CryptoCurrencyAI` folder.
3. Let Gradle sync. Use JDK 17.
4. Connect an Android phone with USB debugging enabled, or start an emulator.
5. Press Run. To create an APK: **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
6. Debug APK is normally created at `app/build/outputs/apk/debug/app-debug.apk`.

## Important
This is a starter project, not a production exchange. Live mode displays public prices only. Demo trades are simulated and are not persisted after the app process is cleared. There is no real-money trading or wallet functionality.

A production exchange requires legal/regulatory review in every target jurisdiction, licensed/authorized exchange and custody/payment partners where required, security architecture, audited backend, KYC/AML controls, transaction monitoring, key management, incident response, and independent security testing. Do not add exchange API secrets or private keys to the Android app.

CoinGecko public API availability and rate limits may change. The app handles network errors by showing a status message.
