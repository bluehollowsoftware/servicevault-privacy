# ServiceVault Privacy Policy Website

This folder contains the authoritative, locally saved ServiceVault privacy
policy. Open `index.html` in a browser to review it.

## Published address

https://bluehollowsoftware.github.io/servicevault-privacy/

This is the public address used by the Android app. The current policy was
approved for publication on July 20, 2026.

## Updating the policy

1. Edit `index.html`. Keep the app practices, effective date, and contact
   information accurate.
2. Open the file locally and review it at narrow and wide browser sizes.
3. Obtain owner approval before replacing the public version.
4. From this folder, publish the approved update with:

   ```bash
   git diff -- index.html
   git add index.html
   git commit -m "Update ServiceVault privacy policy"
   git push
   ```

5. Confirm the public address still works over HTTPS and shows the approved
   effective date and wording.
6. If the public address changes, update `privacy_policy_url` in Android string
   resources and this README before releasing the app.

Do not add analytics, advertising, remote fonts, or third-party scripts to this
page without reviewing and updating the privacy policy first.
