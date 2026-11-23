# dpmattos.github.io

GitHub Pages site for the ChargeLog Tesla Fleet API app (dpmattos/tesla-competition#154).

- `/.well-known/appspecific/com.tesla.3p.public-key.pem`: the app's public key, which Tesla
  fetches during partner registration. Public by design; the private key lives only in 1Password.
- `/tesla/callback/`: the OAuth redirect URI. It only shows the authorization code so it can be
  pasted into the ChargeLog setup; it sends nothing anywhere.
- `.nojekyll`: Jekyll would otherwise skip the `.well-known` folder.
