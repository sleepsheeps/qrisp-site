# Qrisp site

Support page and privacy policy for the Qrisp: QR Code Generator iOS app, served with GitHub Pages.

The app links here from Settings; the URLs are in `src/constants/app.ts` of the app project, and
App Store Connect has them as the support URL and privacy policy URL. Keep them in step:
`PRIVACY_URL` must resolve, or App Store review stops on it.

The privacy policy describes what the app actually does. If the app starts using the network,
a new permission or a third-party SDK, update `privacy.html` (and the App Store privacy label)
in the same change.
